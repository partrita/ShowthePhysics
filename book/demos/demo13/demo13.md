# 줄다리기
<span style="font-size: 25px; color: gray;">한 명의 소녀가 네 명의 소년보다 강할 수 있을까?</span>
<table style="width: 100%; border-collapse: collapse; border: none;">
    <tr style="background-color: var(--background-color);">  
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">저자:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">프릭 폴스</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">시간:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">5분</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">연령 그룹:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">15 - 18세</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">개념:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">힘, 힘의 성분, 힘 분석</td>
    </tr>
</table>

## 소개
한 명의 소녀가 네 명의 소년보다 강할 수 있을까요? 물론이죠! 그녀가 영리하다면…

## 장비
* 소년 4명
* 소녀 1명
* 튼튼한 밧줄 1개

```{figure} demo13_figure1.jpg
---
width: 70%
align: center
name: demo13_fig1
alt: 두 사람이 수평으로 줄을 당기고 있고, 가운데 한 소녀가 손가락 하나로 줄을 아래로 누르고 있습니다.
---
젊은 아가씨가 항상 더 강할 것입니다.
```

## 준비
힘센 소년 네 명과 소녀 한 명을 자원봉사자로 요청하십시오.

## 절차
네 명의 소년에게 그들이 함께 소녀보다 강한지 물어보십시오. 네 명의 소년이 밧줄을 잡고, 양쪽 끝에 두 명씩 서서 밧줄을 수평으로 팽팽하게 유지하도록 격려하십시오. 그런 다음 젊은 아가씨에게 손가락으로 밧줄 중간을 아래로 누르도록 요청하십시오({numref}`그림 {number}<demo13_fig1>` 참조). 소년들은 밧줄을 팽팽하고 수평으로 유지하는 데 성공하지 못할 것입니다.

수업 중인 학생들에게 왜 소년들이 밧줄을 팽팽하고 수평으로 유지할 수 없는지 설명하도록 요청하십시오. 칠판에 간단한 그림을 그리고 소녀가 가하는 50N의 수직력이 밧줄과 수평 사이의 각도가 1°일 때 각 소년이 700N 이상의 힘을 가해야 함을 보여주십시오. 이것은 소녀의 손가락이 가하는 작은 수직력을 보상하기에는 놀라울 정도로 큰 힘입니다.

```{tip}
이 시연의 다른 버전은 {cite:t}`Vollebregt`에 의해 발표되었습니다. 그들은 맥주 상자 양쪽에 두 개의 밧줄을 연결하고 소년들에게 밧줄이 수평이 될 때까지 세게 당기라고 말했습니다. 불가능합니다!

```{figure} demo13_figure2.jpg
---
width: 70%
align: center
alt: 두 사람이 가운데에 곰 상자가 있는 줄을 수평으로 당기려고 합니다.
---
이 경우 밧줄을 수평으로 당길 수 없습니다.
```

## 물리 배경
소년들은 수평 방향으로 힘을 가합니다. 밧줄이 수평인 동안 이 힘은 수직 성분이 없습니다. 손가락으로 밧줄을 아래로 누르면 소년들의 힘의 수직 성분이 생기지만, 그것은 작습니다:

$$2\cdot F_{\text{밧줄에 가하는 소년들의 힘}} \cdot sin(\theta) = -F_{\text{밧줄에 가하는 아가씨의 힘}}$$

$$\Rightarrow  F_{\text{밧줄에 가하는 소년들의 힘}} = \frac{-F_{\text{밧줄에 가하는 아가씨의 힘}}}{2·sin(\theta)} $$

각도 $\theta$는 밧줄과 수평 사이의 각도이며 매우 작으므로 소년들의 힘의 수직 성분은 매우 작습니다. 따라서 밧줄을 아래로 구부리는 데는 최소한의 힘만 필요합니다.

```{code-cell} Python
tag: hide-input

import numpy as np
import matplotlib.pyplot as plt
from matplotlib.patches import Rectangle
from matplotlib.transforms import Affine2D
from ipywidgets import interact
import ipywidgets as widgets

# 상수
def update(theta,F_girl):
    # 화살표 끝 좌표 계산
    F_boys_y = F_girl / 2
    F_boys_x = F_girl*np.tan(theta)/2
    
    # 그림 지우기
    plt.clf()
    fig, ax = plt.subplots()
    ax.set_xlim(-20, 20)
    ax.set_ylim(-20, 20)
    ax.set_aspect('equal')
    ax.grid(True)

    # 화살표 그리기
    
    # 밧줄
    ax.arrow(0, 0, -20*np.sin(theta), 20*np.cos(theta),
             head_width=0, head_length=0, fc='black', ec='black')
    
    ax.arrow(0, 0, 20*np.sin(theta), 20*np.cos(theta),
             head_width=0, head_length=0, fc='black', ec='black')
    
    #힘
    ax.arrow(0, 0, 0, -F_girl,
             head_width=1, head_length=1, fc='green', ec='green')

    ax.arrow(0, 0, F_boys_x, F_boys_y,
             head_width=1, head_length=1, fc='red', ec='red')
    
    ax.arrow(0, 0, -F_boys_x, F_boys_y,
             head_width=1, head_length=1, fc='red', ec='red')

    
    plt.show()

# 부드러운 상호 작용을 위해 FloatSlider 사용
interact(update, theta=widgets.FloatSlider(min=0.1, max=np.pi/2, step=np.pi/16, value=np.pi/4),
         F_girl=widgets.FloatSlider(min=3, max=10, step=1, value=3))
```

## 후속 조치
케이블카 및 전력선 설정 사진을 사용하여 케이블의 장력을 계산하십시오. 예를 들어, 이 <a href="https://newsroom.nvon.nl/files/default/nah151vb.pdf" target="_blank">네덜란드 국가 시험 문제</a>를 참조하십시오.

## 참고문헌

```{bibliography}
:filter: docname in docnames
```
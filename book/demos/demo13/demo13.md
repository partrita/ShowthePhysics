# 줄다리기
<span style="font-size: 25px; color: gray;">여학생 한 명이 남학생 네 명보다 더 힘이 셀 수 있을까?</span>
<table style="width: 100%; border-collapse: collapse; border: none;">
    <tr style="background-color: var(--background-color);">  
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">저자:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">Freek Pols</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">소요 시간:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">5분</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">대상 연령:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">15 - 18세</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">관련 개념:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">힘, 힘의 성분, 힘의 분석</td>
    </tr>
</table>

## 소개
여학생 한 명이 남학생 네 명보다 더 힘이 셀 수 있을까요? 물론입니다! 지혜롭게 힘을 쓴다면요…

## 준비물
* 남학생 4명 
* 여학생 1명
* 튼튼한 줄 1개

```{figure} demo13_figure1.jpg
---
width: 70%
align: center
name: demo13_fig1
alt: 두 사람이 줄을 수평으로 당기고 있고, 가운데에서 여학생 한 명이 손가락 하나로 줄을 아래로 누르고 있는 모습
---
여학생이 언제나 더 힘이 셉니다
```

## 사전 준비
힘이 센 남학생 네 명과 여학생 한 명을 자원자로 모집합니다.

## 실험 과정
남학생 네 명에게 힘을 합치면 여학생 한 명보다 센지 물어봅니다. 남학생 네 명에게 줄의 양쪽 끝에 두 명씩 서서 줄을 잡게 하고, 힘껏 당겨서 줄이 팽팽하게 수평을 유지하도록 격려합니다. 그런 다음 여학생에게 손가락 하나로 줄의 한가운데를 아래쪽으로 누르라고 합니다({numref}`그림 {number}<demo13_fig1>` 참조). 남학생들은 줄을 팽팽한 수평 상태로 유지하는 데 실패할 것입니다. 

반 학생들에게 남학생들이 왜 줄을 팽팽하게 수평으로 유지할 수 없는지 설명해 보라고 합니다. 칠판에 간단한 그림을 그려, 여학생이 가하는 50 N의 수직 방향 힘에 맞서 줄과 수평면 사이의 각도가 1°일 때 각 남학생이 700 N이 넘는 힘을 내야 함을 보여줍니다. 이는 손가락으로 누르는 작은 수직 힘을 상쇄하기 위해 놀라울 정도로 큰 힘이 필요함을 뜻합니다.

```{tip}
이 시연의 또 다른 버전은 {cite:t}`Vollebregt`에 소개되었습니다. 그들은 맥주 상자 양쪽에 줄 두 개를 묶고 남학생들에게 줄이 수평이 되도록 힘껏 당기라고 했습니다. 역시 불가능합니다! 

```{figure} demo13_figure2.jpg
---
width: 70%
align: center
alt: 가운데에 맥주 상자를 매단 줄을 두 사람이 수평으로 당기려 하는 모습
---
이 경우에도 줄을 수평으로 당길 수 없습니다.
```

## 물리학적 배경
남학생들은 수평 방향으로 힘을 가합니다. 줄이 완벽히 수평인 동안에는 이 힘에 수직 성분이 없습니다. 손가락으로 줄을 아래로 누르면 남학생들이 당기는 힘에 수직 성분이 생기지만, 그 크기는 매우 작습니다:

$$2\cdot F_{\text{boys on rope}} \cdot sin(\theta) = -F_{\text{lady on rope}}$$

$$\Rightarrow  F_{\text{boys on rope}} = \frac{-F_{\text{lady on rope}}}{2·sin(\theta)} $$

줄과 수평면 사이의 각도 $\theta$가 매우 작으므로 남학생들이 당기는 힘의 수직 성분 또한 매우 작습니다. 따라서 줄을 아래로 구부리는 데는 아주 작은 힘만 있으면 됩니다. 

```{code-cell} Python
tag: hide-input

import numpy as np
import matplotlib.pyplot as plt
from matplotlib.patches import Rectangle
from matplotlib.transforms import Affine2D
from ipywidgets import interact
import ipywidgets as widgets

# Constants
def update(theta,F_girl):
    # Compute arrow end coordinates
    F_boys_y = F_girl / 2
    F_boys_x = F_girl*np.tan(theta)/2
    
    # Clear figure
    plt.clf()
    fig, ax = plt.subplots()
    ax.set_xlim(-20, 20)
    ax.set_ylim(-20, 20)
    ax.set_aspect('equal')
    ax.grid(True)

    # Draw arrow
    
    # rope
    ax.arrow(0, 0, -20*np.sin(theta), 20*np.cos(theta),
             head_width=0, head_length=0, fc='black', ec='black')
    
    ax.arrow(0, 0, 20*np.sin(theta), 20*np.cos(theta),
             head_width=0, head_length=0, fc='black', ec='black')
    
    #Forces
    ax.arrow(0, 0, 0, -F_girl,
             head_width=1, head_length=1, fc='green', ec='green')

    ax.arrow(0, 0, F_boys_x, F_boys_y,
             head_width=1, head_length=1, fc='red', ec='red')
    
    ax.arrow(0, 0, -F_boys_x, F_boys_y,
             head_width=1, head_length=1, fc='red', ec='red')

    
    plt.show()

# Use FloatSlider for smooth interaction
interact(update, theta=widgets.FloatSlider(min=0.1, max=np.pi/2, step=np.pi/16, value=np.pi/4),
         F_girl=widgets.FloatSlider(min=3, max=10, step=1, value=3))
```

## 후속 활동
케이블카나 송전선 설치 사진을 활용하여 케이블에 걸리는 장력을 계산해 보세요. 예를 들어 이 <a href="https://newsroom.nvon.nl/files/default/nah151vb.pdf" target="_blank">네덜란드 국가 시험 문제</a>를 참고할 수 있습니다.

## 참고문헌

```{bibliography}
:filter: docname in docnames
```
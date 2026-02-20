# 금속 구의 냉각

<table style="width: 100%; border-collapse: collapse; border: none;">
    <tr style="background-color: var(--background-color);">  
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">저자:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">노르베르트 반 빈</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">시간:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">20-30분</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">연령 그룹:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">15 - 18세</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">개념:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">냉각, 비열, FLIR, 적외선(IR)</td>
    </tr>
</table>

## 소개
고체 물체가 냉각되는 과정을 학생들이 경험할 수 있도록, 지름이 다른 철 구들의 냉각을 FLIR 카메라(C5)를 사용하여 관찰합니다. 가장 작은 구가 큰 구들보다 더 빨리 식는 것을 명확하게 볼 수 있습니다. 이 방식은 18세기에 조르주 루이 르클레르(George-Louis Leclerc)가 지구의 나이를 결정하기 위해 수행한 실험에서 사용되었습니다.

```{figure} demo75_figure1.jpeg
---
width: 50%
align: center
name: fig:demo75_setup1
---
구들을 올려놓기 위한 플라스틱 시험관 랙이 있는 설정.
```

## 장비
- 삼각대와 클램프 또는 카메라 삼각대가 있는 설정
- IR 카메라
- 금속 구를 올려놓을 비전도성 구조물 (플라스틱 시험관 랙)
- 지름이 다른 여러 개의 금속 구 (동일한 재질)
- 전기 포트
- 국자
- 행주.

이 설명에서는 측정 소프트웨어로 [Coach 7](https://cma-science.nl/coach7_desktop_downloads_en)을 사용합니다. 이 소프트웨어를 사용한 [측정 파일](./demo75coach.cma7)이 있습니다.

## 준비
1. 그림 {numref}`{number}<fig:demo75_setup1>` 및 {numref}`{number}<fig:demo75_setup2>`와 같이 측정 설정을 구성합니다.

```{figure} demo75_figure3.jpeg
---
width: 50%
align: center
name: fig:demo75_setup2
---
공을 올려놓을 시험관 랙과 이를 촬영하는 IR 카메라를 보여주는 설정의 다른 모습.
```
2. IR 카메라를 올바른 IR 거리와 가시 거리로 설정합니다. 측정 지점(spot)을 이용한 측정 또는 원하는 경우 '최고온도 사각형'(터치스크린에서 원하는 크기로 드래그)을 이용한 측정을 설정합니다. 방사율을 약 0.95(철의 경우)로 설정하고, 다른 재질의 구를 사용하는 경우 해당 금속의 방사율 값을 찾아보십시오.
3. Coach 7을 사용할 경우 '동기화된 디스플레이를 이용한 측정'을 설정합니다. 기기의 일반 카메라 앱으로 설정을 촬영한 다음 카메라로 FLIR C5를 선택할 수도 있습니다.

## 절차
1. 학생들에게 구를 보여주고 구의 지름을 알려줍니다. 재료의 밀도를 사용하여 질량을 계산하게 하십시오.
2. 학생들이 실온에서 특정 온도(예: 60°C)까지 가열되었을 때 구가 가지는 열 에너지가 얼마인지 계산하게 하십시오. (네덜란드 학생들은 BINAS에서 재료의 비열을 찾을 수 있습니다.)
3. 질문하고 짧게 토론합니다: *실험 시작 시 구들의 온도는 같을까요, 다를까요?*
4. 질문하고 토론합니다: *다음 옵션 중 어떤 일이 일어날 것으로 예상하나요?* 
    - 가장 큰 구가 가장 빨리 식을 것이다.
    - 가장 작은 구가 가장 빨리 식을 것이다.
    - 두 구 모두 같은 속도로 식을 것이다.
    가급적 선택한 이유와 설명을 적게 하십시오.
5. 전기 포트에 물을 끓이고, 뚜껑을 열어둔 채 구들을 국자에 담아 포트 안에 넣습니다. 금속 구들이 가열될 때까지 잠시 기다립니다. 포트에서 국자를 꺼내 구들을 행주 위에 올려 빨리 말립니다. 그런 다음 측정 설정의 원하는 위치에 구들을 놓습니다.
6. 측정을 수행합니다. 끓는 물에서 구들을 가열한 후, 즉시 설정 위치에 배치합니다. FLIR IR 카메라로 측정을 시작합니다.

```{figure} demo75_figure2.jpg
---
width: 50%
align: center
name: fig:FLIR_C5_measurement
---
FLIR C5 측정 스크린샷. 온도 범위는 수동으로 설정되었습니다.
```

7. 결과를 토론합니다. *어떤 설명이 가장 잘 맞나요?*
8. 선택적으로 <a href="https://www.sciencedirect.com/science/article/pii/S1631071317300731" target="_blank">조르주 루이 르클레르의 이야기</a>와 그가 지구의 나이를 어떻게 결정했는지 들려줍니다.

9. 학생들의 이해도를 확인하기 위한 질문: *이 방법으로 지구의 나이를 결정할 수 있을까요?*

```{tip}
* 컴퓨터를 통해 측정한 내용을 스크린이나 인터랙티브 화이트보드에 투사합니다. 카메라의 온도 측정 지점을 구에 맞춰 온도를 쉽게 관찰할 수 있도록 하십시오. FLIR C5 카메라는 실온이 보이지 않도록 온도 범위를 수동으로 설정할 수도 있습니다({numref}`그림 {number} <fig:FLIR_C5_measurement>` 참조).
* 구들을 초콜릿 바와 같은 표면 위에 놓아, 나중에 녹은 초콜릿의 양을 통해 구당 열 에너지의 양을 시각적으로 확인할 수 있게 합니다.
* 더 높은 온도에 도달하기 위해 구들을 오븐에 넣을 수도 있습니다. 이때 구를 다룰 때는 각별히 주의하십시오.
```


## 물리 배경
작은 구는 부피에 비해 표면적의 비율이 상대적으로 커서, 주변으로 에너지를 더 빨리 방출할 수 있습니다 (구의 경우 $\frac{A}{V} = \frac{3}{r}$). 반지름이 작을수록 주변으로의 에너지 손실이 더 빨라집니다. 더 자세한 설명은 아래 노트를 참조하십시오.

```{note}
이 실험에서는 지름만 다른 금속(철) 구들의 열 교환을 살펴봅니다. 물체는 열 에너지를 포함하고 있습니다. 물체의 온도가 주변 온도보다 높으면 더 많은 열 에너지를 가지고 있는 것입니다. 물체가 식을 때, 이 경우에는 적외선 복사를 통해 열 에너지를 잃게 됩니다. 구들은 다음과 같이 주변으로 에너지를 방출합니다.

$\frac{dQ}{dt} = P = -k \cdot A \cdot (T - T_{\text{env}})$

구들의 에너지는 다음과 같이 주어집니다.

$ Q = m \cdot c \cdot \Delta T $

여기서 다음이 유도됩니다.

$ \frac{dQ}{dt} = m \cdot c \cdot \frac{\Delta T}{dt} $

따라서 냉각되는 구의 에너지 균형은 다음과 같습니다.

$ m \cdot c \cdot \frac{dT}{dt} = -k \cdot A \cdot (T - T_{\text{env}}) $

이를 적분하면 다음과 같습니다.

$ \frac{T - T_{\text{env}}}{T_{\text{begin}} - T_{\text{env}}} = e^{-\left( \frac{k \cdot A}{m \cdot c} \right) t} $

지수 항의 계수가 냉각 속도를 결정합니다. 따라서 구들을 비교하려면 서로 다른 구에 대해 이 항을 비교해야 합니다. 큰 구의 반지름을 $R$, 작은 구의 반지름을 $r$이라고 합시다.

작은 구의 경우:

$ \frac{kA}{mc} = \frac{kA}{\rho \cdot V \cdot c} = \frac{k \cdot 4\pi r^2}{\rho \cdot \left( \frac{4}{3} \pi r^3 \right) \cdot c} = \frac{k}{\rho \cdot c} \cdot \frac{3}{r} $

큰 구의 경우 다음을 얻습니다.

$ \frac{k}{\rho \cdot c} \cdot \frac{3}{R} $

에너지 손실 속도의 비율은 다음과 같습니다.

$ \frac{\text{작은 구}}{\text{큰 구}} = \frac{\frac{k}{\rho \cdot c} \cdot \frac{3}{r}}{\frac{k}{\rho \cdot c} \cdot \frac{3}{R}} = \frac{R}{r} $

$ \frac{R}{r} $이 1보다 크므로, 작은 구의 에너지 손실이 더 빠릅니다.
```

## 후속 활동
큰 구와 약간 작은 구에 온도 센서를 부착하고 적절한 소프트웨어를 사용하여 측정을 수행합니다. 다음과 같은 질문을 던집니다.
* *이런 방식의 측정이 얼마나 의미가 있을까요?*
* *두 구가 얼마나 빨리 식나요?* 
* *온도 센서 자체가 어떤 영향을 미칠까요?*\
*센서 자체도 가열되어야 하므로, 구가 너무 작은 경우 구로부터 많은 열 에너지를 빼앗아 구가 훨씬 더 빨리 식게 됩니다.*

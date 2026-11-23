# 금속 구의 냉각

<table style="width: 100%; border-collapse: collapse; border: none;">
    <tr style="background-color: var(--background-color);">  
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">저자:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">Norbert van Veen</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">소요 시간:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">20~30분</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">대상 연령:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">15~18세</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">관련 개념:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">냉각, 비열, FLIR, 적외선(IR)</td>
    </tr>
</table>

## 소개
학생들이 고체 물체의 냉각 과정을 직접 경험할 수 있도록, 열화상 카메라(FLIR C5)를 사용하여 지름이 서로 다른 철 구들이 식는 모습을 관찰한다. 가장 작은 구가 더 큰 구들보다 더 빠르게 식는 것을 분명히 볼 수 있다. 이 접근 방식은 18세기에 조르주루이 르클레르(George-Louis Leclerc)가 지구의 나이를 결정할 목적으로 수행했던 실험에서 사용된 방법이다.

```{figure} demo75_figure1.jpeg
---
width: 50%
align: center
name: fig:demo75_setup1
---
구들을 올려놓을 수 있는 플라스틱 시험관 거치대가 포함된 실험 장치.
```

## 준비물
- 스탠드와 클램프 또는 카메라 삼각대
- 적외선(IR) 카메라
- 금속 구들을 올려놓을 비전도성 받침대(플라스틱 시험관 거치대)
- 지름이 서로 다른(같은 재질의) 금속 구 여러 개
- 전기 포트(주전자)
- 국자
- 행주(마른 수건)

이 설명에서는 측정 소프트웨어로 [Coach 7](https://cma-science.nl/coach7_desktop_downloads_en)을 사용한다. 이 소프트웨어를 사용한 [측정 파일](./demo75coach.cma7)도 제공된다.

## 사전 준비
1. 그림 {numref}`{number}<fig:demo75_setup1>`과 {numref}`{number}<fig:demo75_setup2>`에 나타낸 것과 같이 측정 장치를 설치한다.

```{figure} demo75_figure3.jpeg
---
width: 50%
align: center
name: fig:demo75_setup2
---
공을 올려놓을 시험관 거치대와 이를 촬영하고 있는 적외선 카메라를 보여주는 실험 장치의 또 다른 모습.
```
2. 적외선(IR) 카메라를 올바른 적외선 거리와 가시 거리로 설정한다. 측정 지점(spot)을 이용한 측정이나, 원하는 경우 '최고 온도 영역 사각형(hottest spot rectangle)'(터치스크린에서 원하는 크기로 드래그)을 이용한 측정을 설정한다. 방사율(emissivity)은 약 0.95(철 기준)로 설정하며, 다른 재질의 구를 사용하는 경우 해당 금속의 방사율 값을 찾아 설정한다.
3. Coach 7을 사용하는 경우 '동기화된 화면으로 측정(measurement with synchronized display)'을 설정한다. 기기의 일반 카메라 앱으로 장치를 촬영할 수도 있으며, 이 경우 카메라로 FLIR C5를 선택한다.

## 실험 과정
1. 학생들에게 구들을 보여주고 각 구의 지름을 알려 준다. 재료의 밀도를 이용해 질량을 계산해 보게 한다.
2. 실온에서 특정 온도(예: 60°C)까지 가열되었을 때 각 구가 지니는 열에너지가 얼마인지 학생들에게 계산해 보게 한다. 네덜란드 학생들은 BINAS 자료집에서 해당 재료의 비열을 찾을 수 있다.
3. 간단히 질문하고 토의한다: *실험 시작 시점에서 구들의 온도는 같을까, 다를까?*
4. 질문하고 토의한다: *다음 보기 중 어떤 일이 일어날 것으로 예상하는가?* 
    - 가장 큰 구가 가장 빨리 식을 것이다.
    - 가장 작은 구가 가장 빨리 식을 것이다.
    - 두 구 모두 같은 속도로 식을 것이다.
    가급적 자신의 선택과 그 이유(설명)를 글로 적게 한다.
5. 주전자에 물을 끓인 뒤, 주전자 뚜껑을 연 채로 국자에 구들을 담아 주전자 안에 넣는다. 금속 구들이 데워질 때까지 잠시 기다린다. 주전자에서 국자를 꺼내어 마른 수건 위에 구들을 올려놓고 물기를 빠르게 닦아 낸다. 그런 다음 구들을 측정 장치의 지정된 위치에 올려놓는다.
6. 측정을 수행한다. 끓는 물에 데운 구들을 재빨리 장치에 배치한다. FLIR 적외선 카메라로 측정을 시작한다.

```{figure} demo75_figure2.jpg
---
width: 50%
align: center
name: fig:FLIR_C5_measurement
---
FLIR C5 측정 화면 스크린샷. 온도 범위는 수동으로 설정되었다.
```

7. 결과를 토의한다. *어떤 설명이 가장 잘 들어맞는가?*
8. 선택 사항으로 <a href="https://www.sciencedirect.com/science/article/pii/S1631071317300731" target="_blank">조르주루이 르클레르(George-Louis Leclerc)의 이야기</a>와 그의 지구 나이 측정에 대해 들려준다.

9. 학생들의 이해도를 확인하는 질문: *이 방법으로 지구의 나이를 결정할 수 있을까?*

```{tip}
*	컴퓨터를 통해 측정 화면을 스크린이나 전자칠판에 투사한다. 예를 들어 카메라의 온도 측정 지점을 구에 맞추어 온도를 쉽게 따라갈 수 있도록 한다. FLIR C5 카메라를 수동 온도 범위로 설정하면 실내 온도가 배경에 나타나지 않게 할 수도 있다({numref}`그림 {number} <fig:FLIR_C5_measurement>` 참조).
*	초콜릿 바와 같은 표면 위에 구들을 올려놓으면, 녹은 초콜릿의 양을 통해 각 구가 지닌 열에너지의 양을 사후에 눈으로 확인할 수 있다.
*	더 높은 온도에 도달하게 하려면 구들을 오븐에 넣어 가열한다. 이때 구를 다룰 때 화상에 각별히 주의한다.
```


## 물리학적 배경
작은 구는 부피에 대한 표면적의 비율이 상대적으로 더 크기 때문에(구의 경우 $\frac{A}{V} = \frac{3}{r}$) 주위로 에너지를 더 빠르게 방출할 수 있다. 반지름이 작을수록 주위로의 에너지 손실이 더 빠르게 일어난다. 더 자세한 설명은 아래 참고(Note)를 확인하라.

```{note}
이 실험에서는 지름만 다른 금속(철) 구들 사이의 열 교환을 살펴본다. 물체는 열에너지를 지닌다. 어떤 물체가 주변 온도보다 높은 온도를 가지면 더 많은 열에너지를 가진다. 물체가 식을 때는 이 열에너지를, 이 경우에는 적외선(IR) 복사를 통해 잃게 된다. 구들은 다음 식에 따라 환경으로 에너지를 방출한다.

$\frac{dQ}{dt} = P = -k \cdot A \cdot (T - T_{\text{env}})$

구들이 가지는 에너지는 다음과 같다.

$ Q = m \cdot c \cdot \Delta T $

이는 다음으로 이어진다.

$ \frac{dQ}{dt} = m \cdot c \cdot \frac{\Delta T}{dt} $

따라서 냉각되는 구에 대한 에너지 균형 식은 다음과 같다.

$ m \cdot c \cdot \frac{dT}{dt} = -k \cdot A \cdot (T - T_{\text{env}}) $

이를 적분하면 다음을 얻는다.

$ \frac{T - T_{\text{env}}}{T_{\text{begin}} - T_{\text{env}}} = e^{-\left( \frac{k \cdot A}{m \cdot c} \right) t} $

지수 부분의 항이 냉각 속도를 결정한다. 따라서 구들을 비교하려면 서로 다른 구에 대해 이 항을 비교해야 한다. 큰 구의 반지름을 $R$, 작은 구의 반지름을 $r$이라 하자.

작은 구의 경우:

$ \frac{kA}{mc} = \frac{kA}{\rho \cdot V \cdot c} = \frac{k \cdot 4\pi r^2}{\rho \cdot \left( \frac{4}{3} \pi r^3 \right) \cdot c} = \frac{k}{\rho \cdot c} \cdot \frac{3}{r} $

큰 구의 경우 다음을 얻는다:

$ \frac{k}{\rho \cdot c} \cdot \frac{3}{R} $

따라서 에너지 손실 속도의 비는 다음과 같다.

$ \frac{\text{small}}{\text{large}} = \frac{\frac{k}{\rho \cdot c} \cdot \frac{3}{r}}{\frac{k}{\rho \cdot c} \cdot \frac{3}{R}} = \frac{R}{r} $

$ \frac{R}{r} $이 1보다 크므로, 작은 구의 에너지 손실이 더 빠르다.
```

## 후속 활동
큰 구와 그보다 조금 작은 구에 각각 온도 센서를 부착하고, 적절한 소프트웨어를 사용해 측정을 수행한다. 다음과 같은 질문을 해 보자.
* *이런 방식의 측정은 얼마나 의미가 있는가?*
* *두 구는 각각 얼마나 빨리 식는가?* 
* *온도 센서 자체는 어떤 영향을 미치는가?*\
*센서 자체도 데워져야 하므로, 구가 너무 작은 경우에는 구의 열에너지를 많이 빼앗아 구가 더욱 빠르게 식게 된다.*

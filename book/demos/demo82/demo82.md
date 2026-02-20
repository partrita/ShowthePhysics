# 행성의 통과 (Transit)
<span style="font-size: 25px; color: gray;">행성 통과 시뮬레이션</span> 

<table style="width: 100%; border-collapse: collapse; border: none;">
    <tr style="background-color: var(--background-color);">  
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">저자:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">노르베르트 반 빈</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">시간:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">10분</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">연령 그룹:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">14 - 18세</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">개념:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">통과, 행성, 관측, 외계 행성</td>
    </tr>
</table>

## 소개
대부분의 학생은 외계 행성의 통과(transit) 현상에 익숙하지 않겠지만, 외계 행성 자체에는 매력을 느낄 것입니다. 비교적 간단한 설정을 통해 학생들에게 이러한 관측이 어떻게 이루어지는지 엿볼 수 있게 할 수 있습니다. 계산 결과는 실제 시나리오로 확장하여 적용할 수 있습니다.

```{figure} demo82_figure1.jpeg
---
width: 80%
align: center 
---
통과 현상을 측정하기 위한 설정.
```

## 장비
* 홀더에 고정된 LED 램프 (큰 불투명 램프)
* 줄자
* 캘리퍼스
* 조도 센서
* 광학 기구용 라이더(rider)에 고정된 구체

```{tip}
통과 현상을 더욱 명확하게 보여주는 훌륭한 [시뮬레이션](https://astro.unl.edu/naap/esp/animations/transitSimulator.html)들이 있습니다.
```

## 준비
1. 조도 센서, 구체, 불투명 램프가 일직선이 되도록 설정을 정렬합니다.
2. 방을 어둡게 합니다.
3. 조도 센서를 실시간 측정 장치나 데이터 로거에 연결합니다. 램프의 빛이 조도 센서의 측정 범위를 넘지 않도록 주의하십시오.
4. 조도 센서와 램프 사이의 거리를 조절합니다. 지름이 램프 지름의 약 1/5 이하인 구체를 사용하십시오.
5. 컴퓨터 화면을 프로젝터나 인터랙티브 화이트보드를 통해 표시합니다.

## 절차
1. 측정을 시작합니다. 구체가 달린 라이더를 일정한 속도로 램프 앞을 지나가게 합니다. 측정을 중단합니다.
2. 마우스를 사용하여 그래프에서 빛이 줄어든 부분(dip)을 확대합니다. {numref}`그림 {number} <demo82transit>`를 참조하십시오.
3. 통과 지속 시간(transit duration)을 어떻게 결정할 수 있을까요?
4. 학생들에게 행성이 더 느리게/빠르게 이동할 경우 통과 곡선이 어떻게 보일지 스케치하게 합니다.
5. 학생들에게 행성이 더 크거나 작을 경우 통과 곡선이 어떻게 보일지 스케치하게 합니다.
6. 아래 공식을 제공하고 학생들에게 현재 상황에 적용해 보라고 합니다. 램프의 지름을 알려줍니다. 여기서 $H$는 수신된 빛의 밝기 또는 세기를 나타냅니다.
    $\frac{H_{dip}}{H_{star}} =1-(\frac{r_{planet}}{R_{star}})^2$
7. 학생들이 공식을 사용하여 행성의 반지름을 계산하게 합니다.
8. 학생들의 이해도를 확인하기 위한 질문: 이 시연은 실제 외계 행성 관측과 어떤 점에서 차이가 있나요?

```{figure} demo82_figure2.png
---
width: 70%
align: center 
name: demo82transit
---
Coach 소프트웨어를 사용하여 측정한 통과 현상에 의한 조도 감소.
```

## 물리 배경
이 설정에서는 불투명한 램프 앞의 구체를 사용하여 외계 행성의 통과를 시뮬레이션합니다. '실제' 별과 달리, 램프는 '행성'의 위치에서 퍼져나가는(발산하는) 광선을 갖게 됩니다. 또한 비율도 실제 상황과는 차이가 있습니다. 그럼에도 불구하고 조도 감소를 충분히 관찰할 수 있으며, 이를 통해 통과 현상 측정의 개념을 명확히 할 수 있습니다.

사용된 조도 센서는 50도의 공간 측정 각도를 가지고 있어 이 거리에서 불투명 램프의 빛 중 상당 부분을 측정할 수 있습니다. 이것이 측정되는 상대적으로 큰 조도 감소를 설명해 줍니다.

통과 과정에서 외계 행성은 항성(별)의 빛 중 아주 작은 부분을 가리게 되며, 매우 정밀한 장비를 통해 빛의 세기가 줄어드는 것을 측정할 수 있습니다. 포착된 별빛은 평행합니다. 연속적인 여러 번의 조도 감소를 측정함으로써 행성의 공전 주기를 도출할 수 있습니다. 항성의 질량과 광도가 알려져 있으므로, 케플러 제3법칙을 사용하여 외계 행성의 공전 궤도 반지름을 구할 수 있고, 이어서 질량, 밀도, 중력 가속도를 도출할 수 있습니다. 어떤 경우에는 행성 대기의 흡수 스펙트럼을 측정하여 대기 구성 가스를 알아낼 수도 있습니다.

```{tip}
- 우리는 지름 95mm의 8W LED 불투명 램프를 사용했습니다. LED 램프가 깜박이지 않는지 확인하십시오. 휴대전화의 슬로 모션 카메라 모드로 확인할 수 있습니다. 우리의 '행성'은 지름 18mm의 구체였습니다. 조도 센서는 1500 Lux로 설정했습니다.
- 라이터가 있는 설정은 램프의 빛을 반사하여 영점 밝기($H_0$)를 약간 높일 수 있습니다. 빛을 반사할 수 있는 모든 것을 가리십시오. 선택 사항으로, 산란광을 방지하기 위해 조도 센서 위에 PVC 파이프를 끼울 수도 있습니다.
```

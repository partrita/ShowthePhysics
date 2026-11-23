# 행성의 통과
<span style="font-size: 25px; color: gray;">행성 통과 현상 모의실험</span> 

<table style="width: 100%; border-collapse: collapse; border: none;">
    <tr style="background-color: var(--background-color);">  
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">저자:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">Norbert van Veen</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">소요 시간:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">10분</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">대상 연령:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">14 - 18세</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">관련 개념:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">통과(식 현상), 행성, 관찰, 외계 행성</td>
    </tr>
</table>

## 소개
대부분의 학생들은 외계 행성의 통과(식) 현상에 익숙하지 않지만, 외계 행성 자체에는 큰 흥미를 느낄 수 있습니다. 비교적 간단한 장치를 이용해 학생들에게 이러한 관측이 어떻게 이루어지는지 엿볼 기회를 줄 수 있습니다. 여기서의 계산은 실제 상황으로 확장하여 적용할 수 있습니다.

```{figure} demo82_figure1.jpeg
---
width: 80%
align: center 
---
행성 통과를 측정하기 위한 실험 장치.
```

## 준비물
* 홀더에 고정된 LED 전구 (큰 불투명 전구)
* 줄자
* 캘리퍼스
* 조도 센서(광 센서)
* 광학 레일의 이동자(라이더)에 고정된 구

```{tip}
통과 현상을 더욱 명확하게 이해할 수 있는 훌륭한 [시뮬레이션](https://astro.unl.edu/naap/esp/animations/transitSimulator.html)이 있습니다.
```

## 사전 준비
1. 조도 센서, 구, 그리고 불투명 전구가 일직선상에 놓이도록 장치를 정렬합니다.
2. 교실을 어둡게 합니다. 
3. 조도 센서를 실시간 측정 장치나 데이터 로거에 연결합니다. 전구에서 나오는 빛의 양이 조도 센서의 측정 범위를 초과하지 않도록 확인합니다. 
4. 조도 센서와 전구 사이의 거리를 조절합니다. 지름이 전구 지름의 약 1/5 이하인 구를 사용합니다.
5. 프로젝터나 전자칠판을 통해 컴퓨터 화면을 띄웁니다.

## 실험 과정
1. 측정을 시작합니다. 구가 고정된 이동자를 일정한 속력으로 전구 앞을 지나가게 움직입니다. 측정을 멈춥니다.
2. 마우스로 확대하여 그래프에서 빛이 감소한 구간을 크게 띄웁니다({numref}`Figure {number} <demo82transit>` 참조).
3. 통과 지속 시간을 어떻게 구할 수 있을까요?
4. 학생들에게 행성이 더 느리게 또는 더 빠르게 움직인다면 통과 곡선이 어떻게 달라질지 그려 보게 합니다.
5. 학생들에게 행성이 더 크거나 더 작다면 통과 곡선이 어떻게 달라질지 그려 보게 합니다.
6. 아래 공식을 제시하고 학생들에게 이 상황에 적용해 보도록 합니다. 전구의 지름을 알려 줍니다. 여기서 $H$는 수신된 빛의 밝기 또는 세기를 나타냅니다. 
    $\frac{H_{dip}}{H_{star}} =1-(\frac{r_{planet}}{R_{star}})^2$
7. 학생들이 이 공식을 이용해 행성의 반지름을 계산하게 합니다.
8. 학생들의 이해도를 확인하기 위한 질문: 이 시범 실험은 실제 외계 행성 관측과 어떤 점(들)에서 다른가요?

```{figure} demo82_figure2.png
---
width: 70%
align: center 
name: demo82transit
---
통과 시 나타나는 빛의 세기 감소, Coach 소프트웨어를 사용하여 측정함.
```

## 물리학적 배경
이 장치에서는 불투명 전구 앞에 구를 지나가게 함으로써 외계 행성의 통과 현상을 모의실험합니다. ‘실제’ 별과 달리, 전구는 ‘행성’ 위치에서 퍼져 나가는(발산하는) 빛줄기를 만듭니다. 또한 비율 역시 ‘실제’ 상황과 축척이 맞지 않습니다. 그럼에도 불구하고 빛의 세기가 뚜렷하게 감소하는 그래프를 얻을 수 있어, 통과 현상 측정의 원리를 설명하는 데 활용할 수 있습니다.

사용된 조도 센서의 공간 측정 각도는 50도이므로, 이 거리에서는 불투명 전구에서 나오는 빛의 상당 부분을 측정할 수 있습니다. 이것이 비교적 큰 폭의 밝기 감소가 측정되는 이유입니다.

통과가 일어나는 동안 외계 행성은 모항성에서 오는 빛의 아주 작은 일부를 가리게 되며, 매우 정밀한 장비를 통해 빛의 세기 감소를 측정할 수 있습니다. 포착되는 별빛은 평행 광선입니다. 연속적인 밝기 감소를 여러 번 측정하면 행성의 공전 주기를 구할 수 있습니다. 별의 질량과 광도가 알려져 있으므로 케플러 제3법칙을 이용해 외계 행성의 공전 궤도 반지름을 구할 수 있고, 이어서 질량, 밀도, 중력 가속도까지 도출할 수 있습니다. 경우에 따라서는 흡수 스펙트럼을 측정하여 행성 대기를 구성하는 기체의 성분도 알아낼 수 있습니다. 

```{tip}
- 저희는 지름이 95 mm인 8 W LED 불투명 전구를 사용했습니다. LED 전구가 깜빡이지 않는지 확인하세요. 휴대전화 카메라의 슬로 모션 모드로 이를 확인할 수 있습니다. 행성으로는 지름 18 mm의 구를 사용했습니다. 조도 센서는 1500 Lux 범위로 설정했습니다.
- 이동자가 포함된 장치 역시 전구의 빛을 반사하므로 기준 밝기($H_0$)가 약간 높게 측정됩니다. 빛을 반사할 수 있는 부분은 모두 가려 주세요. 선택적으로 조도 센서 위에 PVC 파이프를 끼워 산란광을 차단할 수도 있습니다.
```
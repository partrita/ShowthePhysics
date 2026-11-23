# 힘센 풍선 
<span style="font-size: 25px; color: gray;">놀랍도록 많은 것을 드러내는 측정</span>

<table style="width: 100%; border-collapse: collapse; border: none;">
    <tr style="background-color: var(--background-color);">  
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">저자:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">Norbert van Veen</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">소요 시간:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">5-10분</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">대상 연령:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">14-18세</td>
    </tr>
</table>


## 소개
모든 학생이 살면서 한 번쯤 풍선을 불어 보았겠지만, 보통은 풍선의 물리학이나 풍선 내부에서 일어나는 일에 대해서는 깊이 생각하지 않습니다. 이 시범 실험에서는 풍선 내부에서 일어나는 여러 과정을 보여 줄 수 있습니다. 여기서 풍선의 무게를 측정할 때 '뜻밖의' 결과를 얻게 됩니다.

```{figure} demo65_figure1.jpg
---
width: 75%
align: center
---
컴퓨터에 연결된 전자저울 위의 풍선. 이를 통해 저울이 나타내는 값을 그래프로 표시할 수 있습니다.
```

## 준비물
- 풍선
- USB 출력 기능이 있는 전자저울
- 전자저울 값을 읽어 들이는 소프트웨어가 설치된 컴퓨터 (또는 디지털 저울을 비추는 카메라)
- 풍선을 고정할 투명 스탠드

## 사전 준비
풍선용 스탠드를 올린 상태로 전자저울을 켭니다. 필요하면 '영점(tare)' 버튼을 눌러 저울의 눈금을 0.00 g으로 맞춥니다. 측정 빈도는 초당 2회로 설정합니다. 

## 실험 과정
1. 학생들에게 이 시범 실험이 어떻게 진행되는지 설명합니다.
2. 학생들에게 저울이 무엇을 나타낼지, 그리고 왜 그렇게 될지 예측하게 합니다.
3. 풍선을 불어 즉시 저울 위의 스탠드에 올려놓고 측정을 시작합니다.
4. 처음 2분 동안 풍선의 질량이 뚜렷하게 증가한다는 것을 그래프로 보여 줍니다.
    - *그 원인은 무엇일까요?*
6. 이 시범 실험의 원리를 설명합니다.
7. 학생들의 이해도를 확인하기 위한 질문: *물속에서 물체를 들어 올릴 때 왜 더 무겁게 느껴질까요? 열기구는 내부 공기가 더 따뜻할 때 왜 더 큰 부력을 받을까요? 실험 시작 직전(풍선을 분 직후)과 평형 질량에 도달한 후 풍선 내부의 압력과 온도는 어떠한가요?*

```{figure} demo65_figure2.jpg
---
width: 100%
align: center
---
풍선의 냉각으로 인한 질량 변화.
```


## 물리학적 배경
풍선에는 위쪽으로 작용하는 부력과 아래쪽으로 작용하는 중력, 두 가지 힘이 작용합니다. 입으로 분 풍선 내부의 공기 온도는 약 37 °C로, 풍선 바깥의 공기보다 따뜻합니다. 풍선 속 공기는 주변으로 열을 전달하면서 식게 됩니다. 온도가 낮아진 공기는 압력도 낮아집니다. 따라서 풍선의 부피는 줄어듭니다.

부력은 풍선의 부피에 비례하므로, 부피가 줄어들면 부력도 감소합니다. 그 결과 저울은 더 큰 질량을 가리키게 됩니다. 질량 변화는 수십 분의 1그램 정도이며, 전자저울로 정밀하게 측정할 수 있습니다. 부피 변화의 대략적인 크기는 부력 공식을 이용해 계산할 수 있습니다:

$$F_{buoyant} = \rho \cdot g \cdot V$$

질량 차이가 0.20 g일 때, 풍선의 부피 감소량은 150 mL로 계산됩니다. '반지름'이 10.0 cm인 풍선의 부피는 약 4.2 L입니다. 부피가 4.05 L로 줄어든 풍선의 반지름은 9.99 cm입니다. 이 정도의 부피 변화는 맨눈으로는 알아차리기 어렵습니다.

이 효과는 풍선을 분 직후에 가장 뚜렷하게 나타납니다. 몇 분이 지나면 평형 질량에 도달하며, 풍선 내부의 압력은 외부 대기압에 풍선 고무막이 가하는 압력을 더한 값과 같아집니다. 이때 풍선 내부 공기의 온도는 주변 온도와 같아집니다.

```{tip}
- 그래프와 함께 저울의 질량 수치도 화면에 띄울 수 있습니다. FLIR-C5 열화상 카메라로 촬영하면 풍선의 온도가 바깥 온도보다 높다는 것을 보여 줄 수 있습니다. 원한다면 헤어드라이어로 풍선(및 내부 공기)을 가열해 효과를 더 크게 만들 수도 있습니다. 공기의 흐름 등으로 풍선이 흔들리지 않도록 튜브나 컵 위에 올려두면 더 안정적으로 지지할 수 있습니다. 
```

## 후속 탐구
관련된 시범 실험이 더 있습니다. 예를 들어 [회전하는 풍선](../demo78/demo78.md), [무엇이든 할 수 있는 풍선](../demo76/demo76.md), [공기는 아무것도 아닌 것이 아니다: 공기 무게 재기](../demo30/demo30.md)를 참고해 보세요.

```{tip}
풍선 내부의 압력이 언제 최대가 되는지 알고 보여 주는 것도 흥미롭습니다. 놀랍게도 풍선이 아주 작을 때 압력이 가장 큽니다. 이는 비어 있을 때 풍선을 불어 넣기가 가장 힘들다는 점이나, 공기를 빼면서 소리를 낼 때 풍선이 거의 비어 가는 마지막 부분에서 음의 높이가 가장 높아진다는 점을 통해 확인할 수 있습니다.

<div style="display: flex; justify-content: center;">
    <div style="position: relative; width: 70%; height: 0; padding-bottom: 56.25%;">
        <iframe
            src="https://www.youtube.com/embed/McMa_XNx0fw?si=jCvbaPsF5YjwDFCN"
            style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
        ></iframe>
    </div>
</div>
```
# LED와 광자

<table style="width: 100%; border-collapse: collapse; border: none;">
    <tr style="background-color: var(--background-color);">  
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">저자:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">레오 테 브링케</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">시간:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">10분</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">연령 그룹:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">15 - 18세</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">개념:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">빛의 입자-파동 이중성, 양자화, 문턱 진동수, 광자</td>
    </tr>
</table>

```{figure} demo23_figure1.jpg
---
width: 70%
align: center
name: demo23_fig1
alt: 녹색 LED에 비추는 빨간색 레이저, 전압이 없음을 나타내는 디지털 멀티미터에 연결된 LED
---
녹색 LED에 비추는 빨간색 빛: 전압 없음.
``` 

## 소개
발광 다이오드(LED)가 광원이 아닌 광센서로 역방향 모드에서 사용될 수 있다는 것은 일반적으로 알려져 있지 않습니다. LED는 빛을 흡수할 때 전압을 생성할 수 있지만, 특정 조건이 충족될 때만 가능합니다... 광전지와 마찬가지로 LED는 LED 유형에 따라 달라지는 문턱 파장 또는 주파수를 가지고 있는 것으로 나타났습니다. 이것은 양자화된 빛으로만 설명할 수 있습니다. 이 시연은 광전지와 광전 효과 이전에 광자에 대한 첫 번째 수업에서 사용될 수 있습니다.

## 장비
* 색상이 명확하게 다른 두 개의 LED, 가급적이면 무색 홀더에 있음
* 케이블 및 적절한 저항기가 있는 가변 전압원
* 빨간색 레이저 포인터
* 백색광
* 녹색 레이저 포인터
* 내부 저항이 매우 높은 전압계(10M$\Omega$ 이상)

```{warning}
레이저 사용 시 일반적인 안전 규칙을 준수하십시오!
```

```{figure} demo23_figure2.jpg
---
width: 70%
align: center
name: demo23_fig2
alt: 녹색 LED에 비추는 백색광, 디지털 멀티미터에 연결됨, 출력 1.38V
---
백색광으로 DMM은 전압을 측정합니다.
``` 

## 준비
첫 번째 시연을 위해 각 LED를 저항기 및 전압원과 직렬로 순방향으로 연결하여 LED가 빛나도록 합니다. 후속 시연은 전압원 없이 수행되며, LED를 전압계에 직접 연결하고 레이저 포인터 또는 다른 광원으로 조명합니다({numref}`그림 {number} <demo23_fig1>` 및 {numref}`{number} <demo23_fig2>`). 전압계를 0 – 2V 범위로 설정하십시오.

## 절차
여기서는 빨간색과 녹색 LED를 사용하지만, 하나는 파장이 길고 다른 하나는 파장이 훨씬 짧은 한 다른 색상일 수도 있습니다. 두 LED를 전원 공급 장치에 연결하고 빛을 내게 합니다. LED는 전기 에너지를 빛으로 변환합니다. *반대로 빛을 전기 에너지로 변환하는 것이 가능할까요? 어떻게 조사할 수 있을까요?*

빨간색 LED를 전압계에 연결하고 빨간색 레이저로 조명합니다({numref}`그림 {number} <demo23_fig1>`). *백색광과 녹색광과 같은 다른 색상의 빛도 LED에 전압을 생성할까요?* 백색광과 녹색광 소스로 이것을 확인하십시오({numref}`그림 {number} <demo23_fig2>`).

*강도가 전압에 영향을 미칠까요? 어떻게 조사할 수 있을까요?* LED와 레이저 포인터 사이의 거리를 변경하거나 레이저 포인터의 강도를 줄이는 필터를 사용하십시오. 따라서 LED는 태양 전지처럼 작동할 수 있습니다.

```{note}
전압은 색상 외에 LED의 다른 속성 및 전압계의 저항(커야 함)과 같은 다른 요인에 따라 달라집니다.
```

그런 다음 백색광 소스와 녹색 레이저 포인터로 녹색 LED가 낮은 강도에서도 백색광과 녹색광으로 조명될 때 전압을 생성할 수 있음을 보여줍니다. 그러나 빨간색 빛으로 조명될 때는 그렇지 않습니다.

```{tip}
[POE](../../Pedagogy/PoE.md)에 설명된 대로, 이것이 광자에 대한 첫 번째 수업일 때 예측을 요청하는 것은 의미가 없습니다. 학생들은 아직 의미 있는 예측을 할 만큼 충분한 이해력이 없습니다.
```

이제 질문은 왜 백색광이나 녹색광의 적당한 강도조차도 녹색 LED에 전압을 생성하고 빨간색 빛은 그렇지 않은가입니다. 물리학자들의 설명은 빛 에너지가 패키지로 "양자화"되어 있으며 패키지의 에너지는 빛의 주파수에 따라 달라진다는 것입니다. 더 높은 주파수(따라서 더 작은 파장)는 더 많은 에너지를 가집니다. 따라서 녹색 패키지는 빨간색 패키지보다 더 많은 에너지를 가집니다. 녹색 LED는 빛을 전기 에너지로 변환하고 전압을 생성하기 위해 빨간색 LED보다 더 큰 에너지 패키지가 필요한 것으로 보이며, 녹색 LED에서 생성된 전압은 빨간색 LED보다 높습니다. 이러한 빛의 에너지 패키지는 광양자 또는 광자라고 불립니다(예: [형광 올리브 오일](../demo87/demo87.md) 참조).

이 아이디어를 더욱 뒷받침하기 위해 전기 에너지를 빛으로 변환하는 것을 다시 살펴볼 수도 있습니다. 빛을 내기 위해 녹색 LED는 빨간색 LED보다 더 높은 전압이 필요합니다! 그런 다음 LED로 플랑크 상수를 결정하는 것으로 넘어갈 수 있습니다.

```{figure} demo23_figure3.png
---
width: 70%
align: center
alt: 네 사람이 무슨 일이 일어나고 있는지에 대한 자신의 아이디어를 진술하는 개념 만화.
---
개념 만화는 학생들의 아이디어를 이끌어내는 데 사용될 수 있습니다.
``` 

## 물리 배경
주요 원리는 위에서 언급되었습니다. 이 시연 후에는 학생들이 광전지를 이해하기가 더 쉬울 것입니다. LED가 어떻게 작동하는지에 대한 설명에 들어가는 것은 피하는 것이 좋습니다. 이 시연에서 LED는 순전히 블랙박스이며, 그 행동은 연속적인 에너지 흐름으로서의 광파로는 설명할 수 없고, 우리가 광자라고 명명한 에너지 패키지 또는 광양자로만 설명할 수 있습니다.

동일한 현상의 실제적인 적용은 가시광선(유리창 뒤)으로는 강도에 관계없이 갈색 피부를 얻을 수 없다는 사실입니다. 자외선 에너지 패키지가 필요하며 그것들은 유리에 흡수됩니다. 분명히 우리 피부의 색소 세포는 적어도 자외선의 에너지를 가진 에너지 패키지가 필요합니다(선크림 사용에 대한 멋진 [네덜란드 시험 문제](https://newsroom.nvon.nl/files/default/nav191vb.pdf)가 있습니다). 교사는 또한 전통적인 인화지가 빨간색 빛에 민감하지 않다는 사실을 언급할 수도 있습니다.... 하지만 누가 아직 그것을 알겠습니까?

```{tip}
* 전압계의 내부 저항이 매우 높기 때문에 LED는 전류를 생성할 수 없고 고정된 전압을 유지합니다. 전압을 측정하려면 최소 10 $\text{M}\Omega$의 내부 저항이 필요합니다. 1 $\text{M}\Omega$에서는 LED가 이미 방전됩니다.
* 유색 홀더에 있는 LED는 홀더에서 특정 색상의 빛 흡수가 있을 수 있으므로 이 실험에서 작동하지 않을 수 있습니다.
* 우리 실험에서는 작은 LED가 큰 LED보다 더 잘 반응했습니다. 이유는 불분명합니다.
* 추가 저항은 LED가 켜져 있을 때 전류를 제한하는 데만 필요합니다. 저항의 크기는 전원 및 LED의 최대 전력에 따라 다릅니다. 대부분의 LED는 수십 mA의 전류를 견딜 수 있으며 이는 잘 보이는 빛에 충분합니다.
* 이 시연을 LED로 플랑크 상수를 결정하는 것으로 계속할 수 있습니다.
```

## 후속 조치
플랑크 상수의 대략적인 추정치를 만들 수도 있습니다. 빨간색 LED가 $1.6$ V를 생성하고 각 전자가 하나의 광자로 여기된다고 가정하면, 광자의 최소 에너지와 플랑크 상수의 최소값을 결정할 수 있습니다. $1.6$ V와 파장 $633$ nm(He-Ne-레이저)로 $5.4\cdot 10^{-34}$ Js를 얻습니다. ($1.6 \text{eV} = \frac{hc}{\lambda}$).
# 전구 불 끄기

<table style="width: 100%; border-collapse: collapse; border: none;">
    <tr style="background-color: var(--background-color);">  
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">저자:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">바우터르 스판</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">시간:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">15분</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">연령 그룹:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">13세 이상</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">개념:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">NTC(부온도 계수), 직렬 회로, 전력, 발열</td>
    </tr>
</table>

```{figure} demo31_figure1.jpg
---
width: 70%
align: center
name: demo31_fig2
alt: 분젠 버너를 사용하여 전구를 가열하는 시연자
---
유리 조각을 (조심스럽게!) 가열하면 저항값이 감소하고 전구에 불이 들어옵니다.
```

이 시연은 {cite:p}`Walravens2011`에서 각색되었습니다.

## 소개
이 시연의 주요 목표는 유리의 NTC 동작을 보여주는 것입니다. 다양한 수준에서 전기 공학 개념을 논의하고 학생들이 전류 흐름으로 인한 가열에 대해 생각하도록 유도할 수 있습니다.

## 장비
* 임의의 전구
* 40-60W 전구(팁 참조)
* 소켓 2개(주전원 전압용), 가급적 내화성을 위해 세라믹 1개
* 주전원 전압 스위치
* 접지가 있는 플러그
* 가스 버너

```{warning}
안전 안경을 착용하십시오(앞줄 학생들도 마찬가지이거나 스크린을 설치하십시오).
```

## 준비
* 전구 중 하나의 유리를 깨뜨립니다. 이것은 전구를 종이 층으로 완전히 감싼 상태에서 망치로 가장 잘 작동합니다. 그런 다음 전구에서 필라멘트를 제거합니다. 예를 들어 유리 톱으로 필라멘트 지지대도 제거합니다. 그러면 램프는 {numref}`그림 {number} <demo31_fig3>`과 같이 보일 것입니다(빛나지 않음).
* 수정된 전구와 온전한 전구를 가장자리가 너무 높지 않은 적절한 소켓에 놓습니다(나중에 가열하기 때문). 이 램프를 스위치와 직렬로 연결합니다.

```{warning}
 유리 파편은 면도날처럼 날카롭습니다!
```

```{figure} demo31_figure2.jpg
---
width: 70%
align: center
name: demo31_fig3
alt: 가열된 유리 전구
---
유리 조각은 불꽃에서 제거된 후에도 계속 전도됩니다. 이 유리에 바람을 불어 식히고 전구를 끌 수 있습니다.
```

## 절차
* 칠판에 회로를 그리고, 장비를 설정하고, 설정을 회로와 관련시킵니다. 분젠 버너는 보이지 않습니다.
* 스위치를 켜면 전구에 불이 들어올지 반에 물어보십시오. 토론 후 스위치를 켭니다.
* 분젠 버너를 가져옵니다. 맹렬한 불꽃 속에서 유리를 조심스럽게 가열합니다. 불꽃에 잠시 담갔다가 꺼냅니다. 잠시 가열하면 전구에 불이 들어옵니다. 계속 가열하면서, 가열을 멈추고 유리가 있는 피팅을 아래로 놓으면 어떻게 될지 반에 물어볼 수 있습니다. 이것은 보통 활발한 토론으로 이어집니다. 심도 있는 토론 후, 불꽃에서 유리를 제거합니다. 반의 상당 부분이 놀랍게도, 얼마나 오래 기다리든 전구는 계속 켜져 있습니다.
* 전구에 바람을 불어 불을 끌 수 있음을 보여줍니다. *그것을 어떻게 설명할 수 있습니까?*
* 바람을 멈추고 전구의 전력이 잘 선택되면 유리가 다시 가열되고 전구가 천천히 켜집니다.

```{figure} demo31_figure3.png
---
width: 50%
align: center
name: demo31_fig1
alt: 회로의 개략도, 유리는 저항으로 표시됨
---
설정의 회로도. 저항은 유리 조각으로 구성됩니다({numref}`그림 {number} <demo31_fig3>` 참조).
```

## 물리 배경
유리는 전자 구조 측면에서 반도체와 다소 유사하기 때문에 NTC처럼 작동합니다. 실온에서는 전도대가 비어 있고 밴드 갭이 너무 커서 전자가 건너갈 수 없습니다. 가열되면 전자는 밴드 갭을 건너기에 충분한 열 에너지를 얻고 유리는 점점 더 잘 전도됩니다. 유리의 이온은 전도에 아무런 역할을 하지 않습니다.

```{tip}
* 유리 조각의 정확한 속성 및 치수에 대한 전구의 전력은 중요합니다. 전력이 너무 낮으면 전류가 너무 작아서 유리를 따뜻하게 유지할 수 없습니다. 전력이 너무 높으면 램프를 불어서 끌 수 없습니다. 따라서 시도하고 최적화하십시오!
* 우리는 이 시연의 다른 버전에서 원하는 결과를 얻기 위해 $40$W, $60$W, 심지어 $75$W의 램프를 사용했습니다. 이것은 또한 학생들과 타는 램프의 전력 효과에 대해 논의할 수 있는 기회를 제공합니다.
* 잘 작동하는 조합을 찾으면 전구(정확히 같은 것)를 비축해 두십시오. 몇 년 후에는 더 이상 구할 수 없을 수도 있습니다.
```

## 참고문헌
```{bibliography}
:filter: docname in docnames
```
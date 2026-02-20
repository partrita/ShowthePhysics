# 유도관

<table style="width: 100%; border-collapse: collapse; border: none;">
    <tr style="background-color: var(--background-color);">  
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">저자:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">노르베르트 반 빈</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">시간:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">10-20분 </td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">연령 그룹:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">14 - 18세</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">개념:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">유도, 자석, 렌츠의 법칙</td>
    </tr>
</table>

```{figure} demo86_figure4.jpg
---
width: 70%
align: center
name: demo86_fig4
---
오실로스코프를 이용한 유도 전압 측정.
```

## 소개
코일을 통과하여 떨어지는 자석은 유도 전압을 발생시킵니다. 이 시연에서는 플라스틱 관과 알루미늄 관을 통해 떨어지는 자석을 관찰합니다. 두 관 모두 관을 따라 동일한 간격으로 배치된 동일한 수의 코일을 가지고 있습니다. 시간에 따른 측정된 유도 전압을 살펴봅니다.

```{figure} demo86_figure1.png
---
width: 90%
align: center
figclass: margin
---
왼쪽은 알루미늄 관, 오른쪽은 플라스틱 관이 있는 설정
```

## 장비
- 각각 최소 3개의 동일한 코일이 일정한 간격으로 감겨 있는 플라스틱 관과 알루미늄 관
- 측정 장치 및 소프트웨어 또는 오실로스코프
- 전압 센서 ($\pm$ 500 mV 및 $\pm$ 10 V)
- 스탠드
- 막대자석
- 관 아래에 놓을 부드러운 표면

## 준비
스탠드에 관을 고정합니다. 관을 완벽하게 수직으로 세웁니다. 플라스틱 관 주위의 코일에 전압 센서($\pm$ 10 V)를 연결합니다. 센서를 측정 장치나 오실로스코프에 연결합니다. 자석이 첫 번째 코일을 통과할 때 측정이 시작되도록 트리거를 설정합니다. 알루미늄 관의 경우 전압 센서($\pm$ 500 mV)가 더 적합합니다. 전압 센서를 0V로 맞춥니다.

{numref}`그림 {number}<demo86_fig2>`의 측정에서는 초당 1000회의 샘플링 속도, 0.1초의 트리거 시간(전압 센서 100mV에서 트리거)을 사용했으며 최대 1초 동안 측정을 수행했습니다.

## 절차
코일을 통해 자석을 움직여 전압이 발생하는 것을 보여줍니다. (자석이 코일을 한 번 통과할 때의 그래프를 칠판에 스케치합니다.)

1. 플라스틱 관을 통해 자석을 떨어뜨립니다.
2. 플라스틱 관을 통해 떨어지는 자석의 ($U$, $t$) 다이어그램을 표시합니다 ({numref}`그림 {number}<demo86_fig2>` 참조).

```{figure} demo86_figure2.jpg
---
width: 100%
align: center
name: demo86_fig2
---
플라스틱 관의 6개 코일 각각은 자석이 떨어지면서 통과할 때 신호를 생성합니다. 코일별 그래프 사이의 차이점은 토론의 주제가 됩니다.
```

3. 6개의 그래프가 서로 어떻게 비교되나요? 유사점과 차이점에 대한 설명을 제공하십시오.
4. 분석/처리 옵션 아래의 면적 결정 기능을 사용하여 각 코일 그래프의 피크 아래 면적이 같은 값을 가짐을 보여줍니다. 이러한 피크의 면적 값은 골(trough) 아래의 면적과도 같습니다 ({numref}`그림 {number}<demo86_fig3>` 참조).

```{figure} demo86_figure3.png
---
width: 560%
align: center
name: demo86_fig3
---
대부분의 측정 소프트웨어는 $V_s$ 단위로 면적 값을 결정할 수 있게 해줍니다.
```

5. *왜 이 면적이 같아야 할까요?*
6. 알루미늄 관으로 실험을 반복합니다.
7. 학생들의 이해도를 확인하기 위한 질문: *측정될 그래프에서 무엇을 예상하나요?*

## 물리 배경
접근하는 자기장은 코일에 전류를 유도하여 코일에 의해 유도된 자기장이 접근하는 자석의 자기장에 반대되도록 합니다 (렌츠의 법칙). 자석이 코일에서 멀어질 때 코일은 끌어당기는 자기장을 생성합니다. 따라서 코일 권선의 전류 방향이 바뀝니다.

자석이 떨어지면서 가속됨에 따라 각 코일에서의 속도는 달라지는데, 첫 번째 코일에서는 평균 속도가 낮고 마지막 코일에서는 평균 속도가 높습니다. 플라스틱 관에서는 6개의 코일 근처에서만 반대되는 자기장이 유도됩니다. 반면 알루미늄 관에서는 자석이 낙하하는 내내 반대되는 자기장을 "느끼게" 됩니다.

유도 전압은 패러데이의 법칙을 사용하여 계산할 수 있습니다: $U_{ind}=N\frac{\Delta \phi}{\Delta t}$ 따라서: $U_{ind}\Delta t=N\Delta \phi$

$N·ΔΦ$의 곱이 일정하기 때문에(코일당 권수, 자석의 세기, 코일의 면적이 같으므로), 그 곱 또한 같아야 합니다. 이 곱이 그래프 아래의 면적입니다. 자석이 더 빨리 떨어질수록 유도 전압은 증가하고 시간 간격 $\Delta t$는 작아집니다.

```{tip}
- 관당 코일이 3개만 있어도 실험이 가능합니다.
- $U_{ind}$의 절댓값을 취하면 시간에 따른 $U_{ind}$의 변화를 양의 피크로만 볼 수 있습니다. 그러면 낙하 속도의 증가가 명확하게 보입니다. 이를 잠재적으로 중력 가속도를 결정하는 데 사용할 수 있습니다.
```

## 후속 활동
시연 [자석이 중력에 도전하나요?](../demo16/demo16.md)가 적절한 후속 활동이 될 수 있습니다.

# 전자기 유도 관

<table style="width: 100%; border-collapse: collapse; border: none;">
    <tr style="background-color: var(--background-color);">  
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">저자:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">Norbert van Veen</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">소요 시간:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">10~20분 </td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">대상 연령:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">14 - 18세</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">관련 개념:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">전자기 유도, 자석, 렌츠</td>
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
코일 속으로 자석이 떨어지면 유도 전압이 발생합니다. 이 시범 실험에서는 플라스틱 관과 알루미늄 관을 통과하여 떨어지는 자석을 관찰합니다. 두 관에는 동일한 코일이 같은 개수만큼 관을 따라 일정한 간격으로 배치되어 있습니다. 시간에 따라 측정된 유도 전압을 살펴봅니다.

```{figure} demo86_figure1.png
---
width: 90%
align: center
figclass: margin
---
왼쪽의 알루미늄 관과 오른쪽의 플라스틱 관이 설치된 실험 장치
```

## 준비물
- 동일한 코일이 최소 3개 이상 일정한 간격으로 감겨 있는 플라스틱 관과 알루미늄 관 각각 1개 
- 측정 장치 및 소프트웨어, 또는 오실로스코프
- 전압 센서 ($\pm$ 500 mV 및 $\pm$ 10 V)
- 스탠드
- 막대자석
- 관 아래에 놓을 부드러운 바닥재.

## 사전 준비
스탠드에 관을 고정합니다. 관이 정확히 수직이 되도록 세웁니다. 플라스틱 관 둘레의 코일에 전압 센서($\pm$ 10 V)를 연결합니다. 센서를 측정 장치나 오실로스코프에 연결합니다. 자석이 첫 번째 코일을 통과할 때 측정이 시작되도록 트리거를 설정합니다. 알루미늄 관의 경우에는 ($\pm$ 500 mV) 전압 센서가 더 적합합니다. 전압 센서를 0 V로 영점 조정합니다. 

{numref}`Figure {number}<demo86_fig2>`의 측정을 위해서는 초당 1000회의 샘플링 속도, 0.1 s의 트리거 시간(전압 센서 100 mV에서 트리거)을 사용했으며, 최대 1 s 동안 측정을 진행했습니다.

## 실험 과정
코일 속으로 자석을 움직여 전압이 발생함을 보여 줍니다. (칠판에 코일을 통과하는 자석의 한 번의 움직임에 대한 그래프를 그려 둡니다.) 

1. 플라스틱 관 속으로 자석을 떨어뜨립니다.
2. 플라스틱 관을 통과하여 떨어지는 자석의 ($U$,$t$) 그래프를 화면에 띄웁니다({numref}`Figure {number}<demo86_fig2>` 참조).

```{figure} demo86_figure2.jpg
---
width: 100%
align: center
name: demo86_fig2
---
떨어지는 자석이 지날 때마다 플라스틱 관의 여섯 개 코일 각각이 신호를 생성합니다. 코일별 그래프 사이의 차이를 통해 토의를 진행할 수 있습니다.
```

3. 여섯 개의 그래프는 서로 어떻게 비교되나요? 유사점과 차이점에 대한 설명을 제시해 보세요.
4. 분석/처리(Analysis/Processing) 옵션의 면적 구하기 기능을 사용하여 코일 그래프의 각 봉우리(양의 피크) 아래 면적이 모두 같은 값을 가짐을 보여 줍니다. 이러한 봉우리 아래의 면적 값은 골(음의 피크) 아래의 면적과도 같습니다({numref}`Figure {number}<demo86_fig3>` 참조).

```{figure} demo86_figure3.png
---
width: 560%
align: center
name: demo86_fig3
---
대부분의 측정 소프트웨어에서는 면적 값을 $V_s$ 단위로 구할 수 있습니다.
```

5. *왜 이 면적이 같아야 할까요?*
6. 알루미늄 관으로 실험을 반복합니다.
7. 학생들의 이해도를 평가하기 위한 질문: *측정될 그래프는 어떤 모습일 것으로 예상하나요?*

## 물리학적 배경
다가오는 자기장은 코일에 전류를 유도하여, 코일에 의해 유도된 자기장이 다가오는 자석의 자기장을 방해하도록 합니다(렌츠의 법칙). 자석이 코일에서 멀어질 때는 코일이 끌어당기는 자기장을 만듭니다. 따라서 코일 권선에 흐르는 전류의 방향이 바뀝니다.

자석이 떨어지면서 가속됨에 따라 각 코일에서의 속력이 달라지며, 첫 번째 코일에서는 평균 속력이 낮고 마지막 코일에서는 평균 속력이 높습니다. 플라스틱 관에서는 여섯 개의 코일 부근에서만 반대 방향의 자기장이 유도됩니다. 반면 알루미늄 관에서는 자석이 떨어지는 전체 구간에 걸쳐 반대 방향의 자기장을 “느끼게” 됩니다. 

유도 전압은 패러데이의 법칙을 이용해 계산할 수 있습니다: $U_{ind}=N\frac{\Delta \phi}{\Delta t}$ 이므로, $U_{ind}\Delta t=N\Delta \phi$가 됩니다.

$N·ΔΦ$의 곱이 일정하므로(코일당 감긴 횟수가 같고 자석의 세기와 코일의 단면적도 같음), 이 곱의 값 역시 같아야 합니다. 이 곱이 바로 그래프 아래의 면적입니다. 자석이 더 빠르게 떨어질수록 유도 전압은 커지고 시간 간격 $\Delta t$는 작아집니다.

```{tip}
- 관마다 코일이 세 개만 있어도 실험을 수행할 수 있습니다.
- $U_{ind}$의 절댓값을 취하면, 시간에 따른 $U_{ind}$의 변화를 양의 봉우리만으로 볼 수 있습니다. 그러면 낙하 속력의 증가가 뚜렷하게 드러납니다. 이를 활용해 중력 가속도를 구하는 데 이용할 수도 있습니다.
```

## 후속 활동
시범 실험 [자석이 중력을 거스를까?](../demo16/demo16.md)가 적절한 후속 활동이 됩니다.

# 진자에 작용하는 장력

<table style="width: 100%; border-collapse: collapse; border: none;">
    <tr style="background-color: var(--background-color);">  
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">저자:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">Norbert van Veen</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">소요 시간:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">20-30분</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">대상 연령:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">14 - 18세</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">관련 개념:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">장력, 구심력</td>
    </tr>
</table>

```{figure} demo66_figure1.jpg
---
width: 50%
align: center
name: demo66_fig1
---
힘 센서에 공을 매단 실험 장치.
```

## 소개
진자 실험은 흔히 진자의 길이와 주기 사이의 관계를 이용해 중력 가속도 $g$를 측정하는 데 사용됩니다. 이 시범 실험은 그 변형입니다. 학생들은 시간에 따라 변하는 힘의 측정값을 관찰합니다. 진동의 주기를 구하기 위해 학생들은 장력이 어떻게 변하는지, 그리고 추의 위치가 이 장력의 크기에 어떤 영향을 미치는지 생각해 보아야 합니다.

## 준비물
- 스탠드와 힘 센서가 포함된 장치
- 가는 실
- 줄자
- 추 (또는 공)
- 측정 인터페이스

이 실험에서는 장치의 데이터를 읽기 위해 Coach 7을 사용했지만, 다양한 힘 측정 장치를 사용할 수 있습니다. 

## 사전 준비
1. 힘 센서를 읽어 들이는 소프트웨어를 실행합니다.
2. 힘 센서를 인터페이스에 연결하고 알맞은 측정 범위로 설정합니다. 
3. 힘 센서에 실을 매달고 센서의 영점을 맞춥니다. 
4. 실에 추(또는 공)를 매답니다. 전체 장치 구성은 {numref}`그림 {number}<demo66_fig1>`을 참조하세요.
5. 힘 센서는 음수 값을 표시할 수 있습니다. 교수학적 이유로 이 값을 양수로 표시하는 편이 좋습니다. 데이터 표에서 힘 센서 값에 -1을 곱하는 새 변수를 생성하세요.

## 실험 과정
1. 정지해 있는 추에 대해 측정된 힘을 바탕으로 학생들이 추의 질량을 계산하게 합니다.
2. 선택 사항으로, 조화 진동 그래프(시간에 따른 변위)를 보여 줍니다.
3. 실에 작용하는 장력을 항상 측정하고 있다는 점을 분명히 설명합니다.
    - *이 힘은 어느 방향을 향하나요?*
    - *추가 앞뒤로 흔들릴 때 시간에 따른 장력 그래프는 어떤 모양일까요?*
4. 측정을 진행합니다. 추를 (살짝) 당겼다가 놓고 Coach 7에서 시작(Start)을 누릅니다.
5. 측정된 그래프($F_{\text{tension}}$ 대 $t$)를 전자칠판에 크게 띄워 보여 줍니다.
    - *추의 어느 위치에서 장력이 최소가 되나요? 그리고 어느 위치에서 장력이 최대가 되나요?*
    - *이 그래프에서 진자의 진동 주기를 어떻게 읽을 수 있으며, 왜 그런 방식으로 읽어야 하나요?*
    ```{figure} demo66_figure2.jpeg
    ---
    width: 100%
    align: center
    ---
    길이가 0.55 m인 진자의 장력 측정값. Coach 7 다이어그램 창의 읽기 옵션을 사용해 극값을 읽어 낼 수 있습니다.
    ```

6. 학생들에게 평형 위치와 양 끝(최고점) 위치에서의 힘의 작도를 그려 보게 합니다.
    ```{figure} demo66_figure3.png
    ---
    width: 100%
    align: center
    ---
    양 끝 위치와 평형 위치에서의 힘의 작도.
    ```
7. 학생들에게 양 끝 위치에서의 진폭 각도를 계산하게 합니다.
8. 학생들은 구심력을 이용해 평형 위치에서의 속력을 계산합니다.
8. 학생들의 이해도를 확인하기 위한 질문: *그네를 탈 때 언제 몸이 가장 "무겁게" 느껴지나요? 왜 그럴까요?*


## 물리학적 배경
이러한 장력 값에서는 힘 센서 내부의 변형률 게이지(strain gauge) 길이가 변하지 않으므로 진자의 길이는 거의 일정하게 유지됩니다. 변위가 작다면 진자는 조화 진동을 합니다. 실의 장력은 항상 양수이며 변위처럼 부호가 바뀌지 않습니다. 진자의 양 끝 위치에서는 속력이 0이므로 장력이 최소가 됩니다. 평형 위치에서는 장력이 중력을 상쇄할 뿐만 아니라 구심력까지 제공해야 하므로 장력이 최대가 됩니다. 학생들은 평형 위치와 양 끝 위치에서 힘을 작도해 봄으로써 추의 위치에 따라 장력의 크기가 변한다는 것을 알 수 있습니다. 진자의 대칭성 때문에 진자가 한 주기를 왕복하려면 장력의 최솟값 두 개 또는 최댓값 두 개를 지나야 합니다. 자세한 내용은 {cite}`Pendrill2023`도 참고하세요.

추가 탐구로 에너지 보존 법칙을 이용해 평형 위치에서의 속력을 계산해 볼 수 있습니다. 측정된 그래프에서 구한 구심력을 이용해 이 속력을 검증해 보세요. 흔들리는 추를 영상으로 촬영해 영상 분석(video measurement)으로 계산 결과를 검증해 볼 수도 있습니다.

```{tip}
추가 한 평면 안에서 계속 흔들리도록 힘 센서의 고리가 실의 고리와 수직이 되게 걸어 주세요.
```

## 참고문헌
```{bibliography}
:filter: docname in docnames
```
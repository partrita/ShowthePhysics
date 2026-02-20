# 진자의 장력

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
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">14 - 18세</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">개념:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">장력, 구심력</td>
    </tr>
</table>

```{figure} demo66_figure1.jpg
---
width: 50%
align: center
name: demo66_fig1
---
힘 센서에 매달린 공이 있는 설정.
```

## 소개
진자 실험은 보통 진자의 길이와 주기 사이의 관계를 이용하여 중력 가속도 $g$를 결정하기 위해 수행됩니다. 이 시연은 그 변형입니다. 학생들은 시간에 따라 변하는 측정된 힘을 관찰합니다. 진동 주기를 결정하기 위해, 학생들은 장력이 어떻게 변하는지, 그리고 질량의 위치가 이 장력의 크기에 어떻게 영향을 주는지 생각해야 합니다.

## 장비
- 스탠드와 힘 센서가 포함된 설정
- 가는 줄
- 줄자
- 질량 블록 (또는 공)
- 측정 인터페이스

이 실험을 위해 우리는 기기 데이터를 읽는 데 Coach 7을 사용했지만, 많은 종류의 힘 측정 장치를 사용할 수 있습니다.

## 준비
1. 힘 센서의 데이터를 읽기 위해 소프트웨어를 실행합니다.
2. 힘 센서를 인터페이스에 연결하고 올바른 범위를 설정합니다.
3. 힘 센서에 줄을 매달고 센서의 영점을 조절합니다.
4. 줄에 질량 블록(또는 공)을 매답니다. 전체 설정은 {numref}`그림 {number}<demo66_fig1>`을 참조하십시오.
5. 힘 센서에는 음수 값이 표시될 것입니다. 교육적인 이유로 이를 양수 값으로 표시하는 것이 좋습니다. 데이터 테이블에서 힘 센서 값에 -1을 곱한 새로운 변수를 생성합니다.

## 절차
1. 학생들이 정지해 있는 블록의 측정된 힘을 바탕으로 질량을 계산하게 합니다.
2. 선택 사항으로 조화 진동(변위 대 시간) 그래프를 보여줍니다.
3. 줄의 장력을 측정하고 있음을 명확히 설명합니다.
    - *이 힘의 방향은 어디인가요?*
    - *블록이 앞뒤로 흔들릴 때 장력 대 시간 그래프는 어떤 모습일까요?*
4. 측정을 수행합니다. 블록을 (작은 각도로) 옆으로 당겼다 놓고 Coach 7에서 시작을 누릅니다.
5. 측정된 다이어그램($F_{\text{장력}}$ 대 $t$)을 학교 디지털 보드에 확대하여 표시합니다.
    - *블록의 어느 위치에서 장력이 최소인가요? 그리고 어느 위치에서 장력이 최대인가요?*
    - *다이어그램에서 이 진자의 진동 주기를 어떻게 읽을 수 있으며, 왜 그런 방식으로 해야 하나요?*
    ```{figure} demo66_figure2.jpeg
    ---
    width: 100%
    align: center
    ---
    길이 0.55m인 진자의 장력 측정값. Coach 7의 다이어그램 창에 있는 읽기 옵션을 사용하여 극값을 읽어보십시오.
    ```

6. 학생들이 진자의 평형 위치와 양 끝 위치(최대 변위 지점)에서의 힘의 구성을 그리거나 스케치하게 합니다.
    ```{figure} demo66_figure3.png
    ---
    width: 100%
    align: center
    ---
    양 끝 위치와 평형 위치에서의 힘의 구성.
    ```
7. 학생들에게 양 끝 위치에서의 변위 각도를 계산하게 합니다.
8. 학생들은 구심력을 사용하여 평형 위치에서의 속력을 계산합니다.
9. 학생들의 이해도를 확인하기 위한 질문: *그네를 탈 때 언제 몸이 가장 "무겁게" 느껴지나요? 그 이유는 무엇인가요?*


## 물리 배경
이 정도의 장력 값에서는 힘 센서 내부의 변형 게이지의 길이가 거의 변하지 않으므로 진자의 길이는 일정하게 유지됩니다. 변위가 작으면 진자는 조화 진동을 합니다. 줄의 장력은 양수이며 변위와 달리 부호가 바뀌지 않습니다. 진자의 양 끝 위치에서는 속력이 0이므로 장력이 최소가 됩니다. 평형 위치에서는 장력이 중력을 보상할 뿐만 아니라 구심력도 제공해야 하므로 최대가 됩니다. 힘의 구성(평형 위치와 양 끝 위치)을 통해 학생들은 장력의 값이 블록의 위치에 대한 함수로 변한다는 것을 알 수 있습니다. 진자의 대칭성 때문에 진자의 한 주기 동안 장력의 최소값 두 개 또는 최대값 두 개를 지나야 합니다. {cite}`Pendrill2023`도 참조하십시오.

추가 연구를 위해 에너지 보존 법칙을 사용하여 평형 위치에서의 속력을 계산할 수 있습니다. 측정된 그래프에서 결정된 구심력을 사용하여 이 속력을 검증하십시오. 흔들리는 블록을 비디오로 촬영하고 비디오 분석을 통해 계산 결과를 확인해 보십시오.

```{tip}
블록이 한 평면에서 계속 흔들릴 수 있도록 힘 센서의 고리가 줄의 고리와 수직이 되도록 하십시오.
```

## 참고 문헌
```{bibliography}
:filter: docname in docnames
```

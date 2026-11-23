# 전구에 걸리는 교류 전압

<span style="font-size: 25px; color: gray;">교류 전압과 밝기를 측정하는 빠른 컴퓨터 측정 실험</span>

<table style="width: 100%; border-collapse: collapse; border: none;">
    <tr style="background-color: var(--background-color);">
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">저자:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">Norbert van Veen, Freek Pols</td>
    </tr>
    <tr style="background-color: var(--background-color);">
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">소요 시간:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">10~20분</td>
    </tr>
    <tr style="background-color: var(--background-color);">
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">수준:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">9학년(중3) 이상</td>
    </tr>
    <tr style="background-color: var(--background-color);">
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">관련 개념:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">교류 전압, 전류의 방향, 전력, 밝기(광도), 진동수</td>
    </tr>
</table>

## 소개
이 시범 실험은 (자전거용 백열) 전구에 걸리는 교류 전압과 이에 따라 변하는 전구의 밝기를 보여 줍니다. 두 변화의 진동수는 같을까요? 전압과 밝기는 위상이 같을까요?

```{figure} demo48_figure1.JPG
---
width: 70%
align: center
name: demo48_fig1
alt: 직렬로 연결된 전구들과 전압계가 있는 실험 장치
---
전압 센서(측정 범위 -10 ~ 10 V)와 조도(밝기) 센서를 포함한 실험 장치.
```

## 준비물
* 전구와 교류 전원이 포함된 실험 장치
* 백열전구(6V)
* 전압 센서
* 조도(밝기) 센서
* 과학 실험용 소프트웨어 또는 오실로스코프
* 선택 사항: 탁상용 형광등 세트({numref}`그림 {number}<demo48_fig3>` 참고)

```{figure} demo48_figure3.jpg
---
width: 70%
align: center
name: demo48_fig3
alt: 백열전구와 포토다이오드로 구성된 실험 장치
---
선택 사항으로 형광등에 대해서도 측정을 진행할 수 있습니다.
```

## 사전 준비
{numref}`그림 {number}<demo48_fig1>`과 같이 장치를 설치합니다. 전압 센서와 조도 센서를 측정 장치에 연결합니다. 모든 학생이 디지털 측정값을 잘 볼 수 있도록 화면을 배치합니다. 조도 센서를 시험 작동해 보고, 측정되는 밝기가 센서의 측정 범위 안에 들어오도록 전구와의 거리를 조절합니다. 두 신호가 깔끔하게 표시되도록 트리거(trigger) 조건을 설정합니다.

```{tip}
조도 센서를 스탠드에 고정하여 전구 위 적정 높이를 유지하게 하면 빛이 너무 많거나 적게 들어오는 것을 방지할 수 있습니다.
```

```{figure} demo48_figure2.JPG
---
width: 70%
align: center
name: demo48_fig2
alt: 인가된 전압과 측정된 밝기를 하나의 그래프에 나타낸 그림. 전구 밝기의 진동수가 전압 진동수의 두 배입니다.
---
하나의 그래프에 나타낸 두 측정 결과: 시간에 따른 전구 양단의 교류 전압과 전구의 밝기.
```

## 실험 과정
1. 천장에 있는 형광등을 가리키며 학생들에게 시간에 따른 밝기 그래프를 그려 보게 합니다. 밝기가 일정할까요, 아니면 시간에 따라 변할까요?
2. 조도 센서를 이용해 형광등 불빛의 진동수를 측정합니다. 이때 정확한 진동수 값의 이유는 아직 설명하지 않고, 시범 실험 뒷부분에서 다룹니다. 탁상용 형광등 세트가 있다면 위치에 따라 밝기가 어떻게 달라지는지 보여 줄 수 있습니다(형광등 양 끝부분에서는 밝기가 훨씬 약합니다).
3. 빛의 깜빡임을 더 자세히 탐구하기 위해 이 시범 실험을 도입합니다.
4. 실험대 위에 장치를 올려놓고 회로를 설명합니다. 칠판에 회로도를 그린 뒤, 우선 전구 양단에 걸리는 교류 전압만 측정해 보여 줍니다.
5. 학생들과 교류 전압의 파형에 대해 토의합니다. 전류의 방향이 어떻게 바뀌는지 질문하고, 진동수에 대해 이야기하며 학생들에게 익숙한 값인지 물어봅니다.
6. 장치 근처에 조도 센서를 배치합니다. 앞서 형광등으로 설명하지 않았다면 이 센서가 무엇을 측정하는지 안내합니다. 학생들에게 개별적으로 조도 측정 결과를 예상하는 그래프를 그려 보게 합니다.
7. 밝기와 교류 전압을 동시에 측정합니다. 교류 전압과 밝기의 진동수를 각각 구해 봅니다. 두 진동수가 같은가요? 왜 같거나(또는 다를까요)?
8. 학생들에게 교류(AC) 대신 직류(DC)를 사용하면 그래프가 어떻게 달라질지 질문한 뒤, 직접 시연해 보입니다.
9. LED 조명에 대한 측정으로 실험을 확장해 봅니다. 여러 작업 현장에서 특수 조명을 사용하는 것이 왜 중요한지 토의할 수 있으며, [표본 추출(샘플링) 시범 실험](../demo44/demo44.md)도 함께 참고할 수 있습니다.

```{figure} demo48_figure4.jpg
---
width: 70%
align: center
name: demo48_fig4
alt: 실제 측정 결과가 표시된 오실로스코프 화면
---
측정된 진동수가 100 Hz인 이유는 무엇일까요?
```

## 물리학적 배경
전력망에서 공급되는 교류 전압은 50 Hz(미국에서는 60 Hz)로 변하며 교류 전류도 마찬가지입니다. 한 주기 동안 전압과 전류는 두 번씩 커졌다가 작아집니다. 백열전구가 빛을 내는 데에는 전류의 방향이 영향을 미치지 않으므로, 전구의 밝기는 정확히 두 배의 진동수로 요동칩니다. 학생들은 이 설명을 들으면 금방 이해하지만, 스스로 생각해 내기는 쉽지 않습니다. 학생들은 광원의 세기 변화를 눈으로 인지하지 못하기 때문에 밝기가 변하지 않고 일정하다고 생각하는 경향이 있습니다 {cite}`Bacalla2013`.

## 참고문헌
```{bibliography}
:filter: docname in docnames
```

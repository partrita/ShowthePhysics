# 블록을 쌓아 기울어진 탑 만들기

<table style="width: 100%; border-collapse: collapse; border: none;">
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">저자:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">Maarten van Woerkom</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">소요 시간:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">20분</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">대상 연령:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">12세 이상</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">관련 개념:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">질량 중심, 안정 평형</td>
    </tr>
</table>

```{figure} demo04_figure6.jpg
---
width: 50%
align: center
alt: 쌓아 올린 블록들
---
도전 과제: 맨 위 블록이 맨 아래 블록 위에 겹쳐 있지 않은 기울어진 탑 쌓기.
```

## 소개
두 개의 블록을 서로 위에 쌓을 때, 위쪽 블록의 질량 중심이 아래쪽 블록 위에 놓여 있어야 위쪽 블록이 안정적으로 유지됩니다. 따라서 위쪽 블록은 블록 길이의 1/2보다 더 많이 튀어나올 수 없습니다.

*그렇다면 맨 위 블록이 더 멀리 튀어나오도록 여러 개의 블록을 쌓는 것이 가능할까요?*

## 준비물
* 크기가 같은 블록 여러 개.
```{figure} demo04_figure1.jpg
---
width: 50%
align: center
name: demo04_fig1
alt: 일정한 간격으로 쌓인 블록들.
---
이 시범 실험에는 블록 몇 개만 있으면 됩니다.
```

## 실험 과정
학생들에게 다음과 같은 지시와 함께 블록을 서로 위에 쌓아 보게 합니다. *맨 위 블록의 끝부분이 최대한 많이 튀어나오게 하려면 어떻게 쌓아야 할까요?* 다시 말해, *맨 위 블록의 앞쪽 끝과 맨 아래 블록의 앞쪽 끝 사이의 거리를 최대로 만들려면 어떻게 해야 할까요?* 블록은 원하는 만큼 많이 사용할 수 있습니다.
맨 위 블록의 뒤쪽 끝이 맨 아래 블록의 앞쪽 끝을 지나쳐서 바깥으로 나가게 하는 것도 가능할까요?

```{figure} demo04_figure2.jpg
---
width: 50%
align: center
name: demo04_fig2
alt: 맨 위 블록이 맨 아래 블록의 왼쪽으로 벗어난 모습을 보여 주는 블록 쌓기 모식도
---
처음에 떠오르는 방법을 시도해 볼 수 있지만… 아마 성공하지 못할 것입니다.
```

보통은 아래에서부터 블록을 하나씩 쌓아 올립니다. {numref}`그림 {number} <demo04_fig2>`에 있는 4개의 블록을 보세요. 먼저 초록색 블록(1)을 놓고, 그 위에 블록 길이의 1/3만큼 튀어나오게 주황색 블록(2)을 올린 뒤, 또다시 블록 길이의 1/3만큼 튀어나오게 주황색 블록(3)을 올립니다.

그러면 두 주황색 블록을 합친 질량 중심이 정확히 맨 아래 초록색 블록의 왼쪽 끝 바로 위에 놓이게 됩니다. 따라서 그 위에 빨간색 블록 하나를 더 튀어나오게 올리면 탑이 무너지고 맙니다…

하지만 반대의 순서, 즉 위에서부터 아래로 쌓아 나가는 것도 가능합니다({numref}`그림 {number} <demo04_fig5>`). 맨 위에서부터 세었을 때 1번 블록을 2번 블록 위에 올리고, 그다음 1번과 2번 블록을 함께 들어 3번 블록 위에 올리는 식으로 진행합니다.

```{figure} demo04_figure5.jpg
---
width: 50%
align: center
name: demo04_fig5
alt: 손가락을 이용해 두 블록의 균형을 잡는 모습
---
거꾸로 쌓아 내려가려면 매 단계마다 질량 중심을 찾아야 합니다.
```

## 물리학적 배경
맨 위에서부터 시작하는 거꾸로 쌓기 방법을 사용하면, 돌출된 길이가 블록 하나의 길이보다 커지는 지점에 매우 빠르게 도달합니다.
* 1번 블록의 질량 중심은 2번 블록의 앞쪽 끝 바로 위에 위치합니다;
* 1번과 2번 블록을 합친 질량 중심은 3번 블록의 앞쪽 끝 바로 위에 위치합니다;
* 1~3번 블록을 합친 질량 중심은 4번 블록의 앞쪽 끝 바로 위에 위치합니다.
이 모든 블록을 5번 블록 위에 올리면 돌출된 거리는 이미 블록 하나 길이를 넘어섭니다.

```{figure} demo04_figure3.jpg
---
width: 50%
align: center
name: demo04_fig3
alt: 올바른 블록 쌓기 방법을 나타낸 모식도
---
블록 쌓기 뒤에 숨은 물리학(과 수학)
```

````{tip}
* 나무 블록 대신 CD 케이스나 큰 레고 블록을 사용할 수도 있습니다.
* 인터넷에서 “markthal Rotterdam”(로테르담 마르크트할)을 검색해 보면, 사진 속에서 228개의 아파트가 바로 여러분이 지금 이해한 방식으로 층층이 쌓여 있는 모습을 볼 수 있습니다. 실제로 교사 엘린 베이커(Eline Bijker)는 로테르담 마르크트할 사진({numref}`그림 {number} <demo04_fig3>`)으로 블록 쌓기 시범 수업을 시작하며 학생들에게 어떤 건축 원리가 사용되었는지 질문했습니다. <a href="https://en.wikipedia.org/wiki/Market_Hall_(Rotterdam)" target="_blank">로테르담 “마르크트할(Markthal)”</a>은 머리 위로 아치 모양을 이루도록 아파트를 쌓아 올린 실내 시장 건물로, 2014년에 개장했습니다.

```{figure} demo04_figure4.jpg
---
width: 50%
align: center
name: demo04_fig4
alt: 블록 쌓기의 실제 활용 사례를 보여 주는 로테르담 마르크트할 사진
---
로테르담의 마르크트할은 위의 원리에 따라 쌓아 올려진 건물입니다. 사진 출처: <a href="https://commons.wikimedia.org/wiki/File:Markthal-Rotterdam.jpg" target="_blank">https://commons.wikimedia.org/wiki/File:Markthal-Rotterdam.jpg</a> (CC BY-SA)
```
````
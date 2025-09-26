# 블록 쌓아 기울어진 탑 만들기

<table style="width: 100%; border-collapse: collapse; border: none;">
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">저자:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">마르턴 반 부르콤</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">시간:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">20분</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">연령 그룹:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">12세 이상</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">개념:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">질량 중심, 안정 평형</td>
    </tr>
</table>

```{figure} demo04_figure6.jpg
---
width: 50%
align: center
alt: 쌓인 블록
---
도전 과제: 맨 위 블록이 맨 아래 블록 위에 있지 않은 기울어진 탑 쌓기.
```

## 소개
두 개의 블록을 서로 위에 놓으면, 위쪽 블록의 질량 중심이 아래쪽 블록 위에 있을 때 안정적으로 유지됩니다. 따라서 위쪽 블록은 블록 길이의 ½ 이상 튀어나올 수 없습니다.

*블록을 쌓아서 위쪽 블록이 더 멀리 튀어나오게 할 수 있을까요?*

## 장비
* 같은 블록 여러 개.
```{figure} demo04_figure1.jpg
---
width: 50%
align: center
name: demo04_fig1
alt: 균일한 간격으로 쌓인 블록.
---
이 데모에는 몇 개의 블록만 필요합니다.
```

## 절차
*맨 위 블록의 끝이 최대한 많이 튀어나오게 하려면 어떻게 해야 할까요?* 라는 지침과 함께 블록을 몇 개 쌓아보십시오. 즉, *맨 위 블록의 앞면과 맨 아래 블록의 앞면 사이의 거리를 최대로 하려면 어떻게 해야 할까요?* 원하는 만큼 블록을 사용할 수 있습니다.
맨 위 블록의 뒷면이 맨 아래 블록의 앞면을 지나는 것이 가능할까요?

```{figure} demo04_figure2.jpg
---
width: 50%
align: center
name: demo04_fig2
alt: 쌓인 블록의 개략도로, 맨 위 블록이 맨 아래 블록의 왼쪽에 있음을 보여줍니다.
---
우리는 먼저 떠오르는 접근 방식을 시도해 볼 수 있지만... 아마 성공하지 못할 것입니다.
```

보통 블록은 하나씩 쌓습니다. {numref}`그림 {number} <demo04_fig2>`의 4개 블록을 참조하십시오. 먼저 녹색 블록(1), 그 다음 블록 길이의 1/3만큼 튀어나온 주황색 블록(2), 그 다음 블록 길이의 1/3만큼 튀어나온 또 다른 주황색 블록(3) 순입니다.

주황색 블록들의 질량 중심은 이제 맨 아래 녹색 블록의 왼쪽 바로 위에 있습니다. 따라서 빨간색 블록처럼 또 다른 블록을 튀어나오게 놓으면 더미가 넘어질 것입니다...

더미를 역순으로 배열하는 것도 가능합니다: 위에서 아래로({numref}`그림 {number} <demo04_fig5>`). 블록 1을 블록 2 위에 놓고(위에서부터 세어서), 그 다음 블록 1과 2를 블록 3 위에 놓는 식입니다.

```{figure} demo04_figure5.jpg
---
width: 50%
align: center
name: demo04_fig5
alt: 두 블록의 균형을 맞추는 데 사용되는 손가락
---
더미를 역순으로 쌓으려면 매번 질량 중심을 찾아야 합니다.
```

## 물리 배경
위에서부터 시작하여 역순으로 쌓는 방법을 사용하면, 매우 빠르게 돌출부가 블록 길이보다 커지는 지점에 도달합니다.
* 블록 1의 질량 중심은 블록 2의 앞면 위에 있습니다.
* 블록 1과 블록 2의 질량 중심은 블록 3의 앞면 위에 있습니다.
* 블록 1-3의 질량 중심은 블록 4의 앞면 위에 있습니다.
이 모든 것이 블록 5 위에 있으며 돌출부는 이미 블록 길이 하나 이상입니다.

```{figure} demo04_figure3.jpg
---
width: 50%
align: center
name: demo04_fig3
alt: 블록을 올바르게 쌓는 방법의 개략도
---
블록 쌓기의 물리(및 수학)
```

````{tip}
* 나무 블록 대신 CD 케이스나 큰 레고 블록을 사용할 수도 있습니다.
* "markthal Rotterdam"이라는 용어로 구글링하면, 사진에서 228개의 아파트가 이제 이해할 수 있는 방식으로 쌓여 있음을 볼 수 있습니다. 교사 엘리네 바이커는 실제로 로테르담의 시장 홀 사진({numref}`그림 {number} <demo04_fig3>`)으로 블록 쌓기 시연을 시작하고 학생들에게 어떤 건축 원리가 사용되었는지 물었습니다. <a href="https://en.wikipedia.org/wiki/Market_Hall_(Rotterdam)" target="_blank">로테르담 "마르크탈"</a>은 아파트가 아치 모양으로 쌓인 실내 시장입니다. 2014년에 문을 열었습니다.

```{figure} demo04_figure4.jpg
---
width: 50%
align: center
name: demo04_fig4
alt: 로테르담 시장 홀 사진으로, 쌓인 블록의 실제 사용을 보여줍니다.
---
로테르담의 시장 홀은 위의 원리에 따라 쌓여 있습니다. 그림 출처: <a href="https://commons.wikimedia.org/wiki/File:Markthal-Rotterdam.jpg" target="_blank">https://commons.wikimedia.org/wiki/File:Markthal-Rotterdam.jpg</a> (CC BY-SA)
```
````
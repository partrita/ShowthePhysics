# 회전하는 큐브

<table style="width: 100%; border-collapse: collapse; border: none;">
    <tr style="background-color: var(--background-color);">  
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">저자:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">Karel Langendonck</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">소요 시간:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">10~30분</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">대상 연령:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">10학년(고등학교 1학년) 이상</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">관련 개념:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">각속도, 선속도(공전 속도), 구심력</td>
    </tr>
</table>

<div style="display: flex; justify-content: center;">
    <div style="position: relative; width: 70%; height: 0; padding-bottom: 56.25%;">
        <iframe
            src="https://www.youtube.com/embed/_pOtj7NNjmU?si=rXjZopnOuhgbQmi3"
            style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
        ></iframe>
    </div>
</div>

## 소개
학생들은 원운동과 관련된 개념을 어려워하는 경우가 많습니다. 예를 들어, 선속도(원운동 속도)와 각속도의 차이나 구심력을 이해하는 것이 그렇습니다. 이 시범 실험에서는 이러한 개념들을 마찰력과 결합하여, 오직 하나의 힘만이 구심력을 제공하는 상황을 만들어 봅니다.


## 준비물
- 턴테이블
- 질량이 너무 크지 않은 큐브 형태의 물체(예: 레고 브릭 또는 듀플로 인형)
- 저울
- 자

```{figure} demo58_figure1.JPG
---
width: 70%
align: center
name: fig:turntable
---
레고 브릭을 올린 턴테이블
```

## 사전 준비
{numref}`그림 {number} <fig:turntable>`과 같이 레코드플레이어의 턴테이블 위에 큐브를 올려놓습니다. 이 실험 장치에서는 질량체로 레고 브릭을 사용했습니다. 턴테이블을 켰을 때 큐브가 미끄러지기 직전의 중심으로부터의 거리를 미리 파악해 둡니다.

## 실험 과정
1.	큐브를 턴테이블 중심에서 너무 멀지 않은 곳에 놓고 그 거리 $r$을 측정합니다.
2.	턴테이블을 켭니다. 별문제가 없다면 큐브는 턴테이블 위에 그대로 놓여 회전합니다.
3.	학생들에게 큐브의 선속도(원운동 속도)와 각속도를 계산하게 합니다. 턴테이블의 회전수가 33 rpm일 때와 45 rpm일 때 모두 계산하도록 합니다.
4.	학생들에게 큐브에 작용하는 마찰력을 계산하게 합니다.
5.	다시 턴테이블을 멈추고, 큐브를 중심에서 조금 더 멀리 옮긴 다음, 원궤도의 반지름을 다시 측정하고 턴테이블을 다시 켭니다.
6.	학생들에게 선속도, 각속도, 그리고 작용하는 마찰력을 다시 계산하게 합니다.
7.	큐브가 턴테이블 밖으로 튕겨 나가는 지점에 도달할 때까지 위 단계를 필요한 만큼 반복합니다. 이 순간이 바로 큐브에 작용하는 최대 정지 마찰력에 도달한 지점입니다. 이제 최대 정지 마찰 계수(그리고 이어서 운동 마찰 계수)를 계산하거나 학생들이 계산하도록 할 수 있습니다.
8.	학생들의 이해를 확인하기 위한 질문: *마찰 계수가 1보다 큰 값을 가질 수 있을까요?*

```{figure} demo58_figure3.jpg
---
width: 50%
align: center
name: demo58_fig3
---
속도 조절이 가능한 턴테이블을 사용한 시범 실험의 변형.
```

## 물리학적 배경
큐브에는 세 가지 힘이 작용합니다({numref}`그림 {number}<fig:force_balance>` 참조): 중력 $F_G$, 수직항력 $F_N$, 그리고 마찰력 $F_F$입니다. 큐브가 레코드플레이어의 턴테이블 위에 놓여 함께 회전하는 순간, 구심력을 제공하는 것은 바로 마찰력입니다. 따라서 다음 식이 성립합니다:

$$F_F=F_{c}=\frac{mv^2}{r}$$

이 식에서 $F_F$는 마찰력(단위: N), $F_c$는 구심력(단위: N), $m$은 블록의 질량(단위: kg), $v$는 블록의 접선 속도(단위: m/s), $r$은 원궤도의 반지름(단위: m)을 나타냅니다.

```{figure} demo58_figure2.jpg
---
width: 50%
align: center
name: fig:force_balance
---
큐브에 작용하는 세 가지 힘
```

마찰력은 블록에 작용하는 수직항력에 정지 마찰 계수를 곱해서도 구할 수 있습니다. 물론 수직항력은 중력과 크기가 같습니다. 이를 식으로 나타내면 다음과 같습니다:

$F_F = \mu _s \cdot F_N = \mu _s \cdot m  g$ 

이 식에서 $F_F$는 다시 마찰력(단위: N), μₛ는 정지 마찰 계수, $F_N$은 수직항력(단위: N), $m$은 블록의 질량(단위: kg), *g*는 중력 가속도(9.81 m/s$^2$)를 나타냅니다.

마찰력에 대한 두 식을 결합하면, 이 상황에서 정지 마찰 계수에 대한 공식을 유도할 수 있습니다:

$$ \mu _s \cdot m g = \frac{mv^2}{r} \quad \rightarrow \quad \mu _s = \frac{v^2}{rg} $$

위 식에 접선 속도의 공식($v = \frac{2 \pi r}{T}$, 여기서 $T$는 주기(단위: s))을 대입하면 다음과 같습니다:

$$ \mu_ s = \frac{\left( \frac{2 \pi r}{T} \right)^2}{r g} = \frac{4 \pi^2 r}{T^2 \cdot g} $$ 

이 식으로부터 정지 마찰 계수와 원궤도의 반지름 사이에 정비례 관계가 성립함을 알 수 있습니다. 블록이 턴테이블 밖으로 튕겨 나가는 지점에서 정지 마찰 계수는 최댓값에 도달한 것입니다.


```{tip}
- 몇몇 시험 수행자들은 턴테이블 표면이 충분히 매끄럽지 않다고 보고했습니다. 고무 매트를 제거하거나, 매트 위에 비닐 커버를 씌우거나, 기름을 살짝 바르면 실험이 잘 진행되었습니다.
- 이 실험은 진행 과정 자체가 아주 역동적이지는 않으므로, 학생들이 실험 수행과 측정값 수집 과정에 적극적으로 참여하도록 하는 것이 중요합니다. 중간중간 학생들이 직접 계산을 해 보도록 할 수 있습니다.
- 큐브의 회전 주기(그리고 그에 따른 선속도와 각속도)를 계산하는 것이 모든 학생에게 쉽고 당연하게 느껴지지는 않을 것입니다. 이 부분에 각별히 신경 써서 지도하세요.
```
## 심화 탐구
이 실험에서는 회전 주기(일부 턴테이블에서는 78 rpm의 회전수도 가능함), 큐브의 질량, 큐브와 턴테이블 표면의 재질을 변화시켜 볼 수 있습니다. 이를 통해 다양한 변인을 다루며 실험할 수 있으므로 학생 탐구 실험(수행 과제)으로도 적합합니다.
한 시험 수행자는 다음과 같이 보고했습니다: 같은 반지름 위치에 서로 다른 질량을 올려놓고 질량이 차이를 만드는지 비교해 볼 수 있습니다. 질량이 더 큰 물체가 턴테이블에서 더 쉽게 튕겨 나갈까요?
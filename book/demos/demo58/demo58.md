# 회전하는 입방체

<table style="width: 100%; border-collapse: collapse; border: none;">
    <tr style="background-color: var(--background-color);">  
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">저자:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">카렐 랑겐동크</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">시간:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">10-30분</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">연령 그룹:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">10학년 이상</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">개념:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">각속도, 궤도 속도, 구심력</td>
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
학생들은 종종 원운동과 관련된 개념들을 어려워합니다. 예를 들어 궤도 속도와 각속도의 차이, 그리고 구심력에 대한 이해 등이 있습니다. 이 시연에서는 이러한 개념들을 마찰력과 결합하여, 단 하나의 힘만이 구심력을 제공하는 상황을 만들어 봅니다.


## 장비
- 턴테이블 (레코드 플레이어)
- 질량이 너무 크지 않은 입방체 (예: 레고 블록이나 듀플로 인형)
- 저울
- 자

```{figure} demo58_figure1.JPG
---
width: 70%
align: center
name: fig:turntable
---
레고 블록이 놓인 턴테이블
```

## 준비
{numref}`그림 {number} <fig:turntable>`에 표시된 대로 레코드 플레이어의 턴테이블 위에 입방체를 놓습니다. 이 설정에서는 레고 블록을 질량체로 사용했습니다. 턴테이블을 켰을 때 입방체가 막 미끄러지기 시작하는 중심으로부터의 거리를 결정합니다.

## 절차
1. 턴테이블 중심에서 너무 멀지 않은 거리에 입방체를 놓고 이 거리 $r$을 측정합니다.
2. 턴테이블을 켭니다. 별다른 일이 없다면 입방체는 턴테이블 위에 그대로 머물 것입니다.
3. 학생들이 입방체의 궤도 속도와 각속도를 계산하게 합니다. 턴테이블 주파수가 33 rpm일 때와 45 rpm일 때 모두에 대해 계산하게 하십시오.
4. 학생들이 입방체에 작용하는 마찰력을 계산하게 합니다.
5. 턴테이블을 다시 멈추고 입방체를 중심에서 약간 더 먼 곳에 놓은 뒤, 회전 반경을 다시 측정하고 턴테이블을 다시 켭니다.
6. 학생들이 다시 한번 궤도 속도, 각속도 및 작용하는 마찰력을 계산하게 합니다.
7. 입방체가 턴테이블 밖으로 튕겨 나가는 지점에 도달할 때까지 위의 단계를 필요한 만큼 반복합니다. 그 지점이 바로 입방체에 작용하는 최대 정지 마찰력이 한계에 도달한 지점입니다. 이제 정지 마찰 계수의 최대값(그리고 이를 통해 동마찰 계수)을 계산할 수 있습니다.
8. 학생들의 이해도를 확인하기 위한 질문: *마찰 계수가 1보다 클 수 있을까요?*

```{figure} demo58_figure3.jpg
---
width: 50%
align: center
name: demo58_fig3
---
조절 가능한 턴테이블을 사용한 시연의 변형.
```

## 물리 배경
입방체에는 세 가지 힘이 작용합니다 ({numref}`그림 {number}<fig:force_balance>` 참조): 중력 $F_G$, 수직항력 $F_N$ 그리고 마찰력 $F_F$. 입방체가 레코드 플레이어의 턴테이블 위에 있는 동안, 구심력을 제공하는 것은 바로 마찰력입니다. 따라서 다음이 적용됩니다.

$$F_F=F_{c}=\frac{mv^2}{r}$$

이 식에서 $F_F$는 마찰력(N), $F_c$는 구심력(N), $m$은 블록의 질량(kg), $v$는 블록의 접선 속도(m/s), 그리고 $r$은 원운동의 반지름(m)을 나타냅니다.

```{figure} demo58_figure2.jpg
---
width: 50%
align: center
name: fig:force_balance
---
입방체에 작용하는 세 가지 힘
```

마찰력은 또한 블록에 작용하는 수직항력에 정지 마찰 계수를 곱하여 계산할 수 있습니다. 수직항력은 물론 중력과 크기가 같습니다. 공식으로는 다음과 같습니다.

$F_F = \mu _s \cdot F_N = \mu _s \cdot m  g$ 

이 공식에서 $F_F$는 다시 마찰력(N)을, $\mu_s$는 정지 마찰 계수를, $F_N$은 수직항력(N)을, $m$은 블록의 질량(kg)을, 그리고 $g$는 중력 가속도(9.81 m/s$^2$)를 나타냅니다.

마찰력에 대한 두 식을 결합하면, 이 상황에 대한 정지 마찰 계수 공식을 유도할 수 있습니다.

$$ \mu _s \cdot m g = \frac{mv^2}{r} \quad \rightarrow \quad \mu _s = \frac{v^2}{rg} $$

위 식에서 접선 속도 공식($v = \frac{2 \pi r}{T}$, $T$는 주기(s))을 대입할 수도 있습니다. 그러면 다음과 같습니다.

$$ \mu_ s = \frac{\left( \frac{2 \pi r}{T} \right)^2}{r g} = \frac{4 \pi^2 r}{T^2 \cdot g} $$ 

이 식을 통해 정지 마찰 계수와 원운동 반지름 사이의 정비례 관계를 알 수 있습니다. 블록이 턴테이블에서 튕겨 나가는 지점에서 정지 마찰 계수의 최대값에 도달한 것입니다.


```{tip}
- 몇몇 테스터들은 턴테이블이 충분히 매끄럽지 않다고 보고했습니다. 고무 매트를 제거하거나 매트 주위에 플라스틱 커버를 씌우거나 오일을 바르면 잘 되었습니다.
- 이 실험은 실행 과정 자체가 아주 흥미진진하지는 않으므로, 학생들이 실행과 측정 결과 수집에 잘 참여하도록 유도하는 것이 중요합니다. 중간중간 학생들에게 몇 가지 계산을 시켜볼 수 있습니다.
- 입방체의 회전 주기(그리고 이를 통한 궤도 속도 및 각속도)를 계산하는 것이 모든 학생에게 간단하고 논리적이지는 않을 것입니다. 이 부분에 명시적으로 주의를 기울이십시오.
```
## 추가 연구
실험에서 회전 시간(특정 유형의 턴테이블에서는 78 rpm 주파수도 가능), 입방체의 질량, 그리고 입방체 및/또는 턴테이블의 표면 유형을 변화시킬 수 있습니다. 이를 통해 다양한 변수로 실험할 수 있으며, 학생들을 위한 실습 과제로도 적합합니다.
테스터 중 한 명의 보고: 같은 반지름에서 서로 다른 질량을 적용하여 질량이 차이를 만드는지 비교해 볼 수 있습니다. 질량이 더 크면 턴테이블에서 더 쉽게 튕겨 나갈까요?

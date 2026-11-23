# 거꾸로 올라가는 물방울

<span style="font-size: 25px; color: gray;">표본 추출(샘플링)</span>

<table style="width: 100%; border-collapse: collapse; border: none;">
    <tr style="background-color: var(--background-color);">  
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">저자:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">Freek Pols</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">소요 시간:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">15분</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">대상 연령:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">11학년(고2)</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">관련 개념:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">진동수, 표본 추출(샘플링), 나이퀴스트(Nyquist) 정리</td>
    </tr>
</table>

<div style="display: flex; justify-content: center;">
    <div style="position: relative; width: 70%; height: 0; padding-bottom: 56.25%;">
        <iframe
            src="https://www.youtube.com/embed/C9cByXAXkRw?si=nm_BLzKo5BOkISQT"
            style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
        ></iframe>
    </div>
</div>

## 소개
영화나 광고를 보면 자동차는 앞으로 달리고 있는데 바퀴는 뒤로 도는 것처럼 보일 때가 있습니다. 왜 이런 현상이 나타날까요? 그리고 (아날로그) 신호를 다시 복원할 수 있도록 (디지털로) 표본 추출(샘플링)하려면 최소 몇 번의 측정이 필요할까요?

## 준비물
* 점적기(스포이트, 위쪽에 큰 저장통이 달린 것이 가장 좋음)
* 스트로보스코프(또는 LED 스트립과 듀티 사이클 조절이 가능한 함수 발생기)
* 물받이 쟁반
* 물
* 어둡게 할 수 있는 교실(암실)
* 진자

```{warning}
깜빡이는 빛에 민감한 사람이 있을 수 있으므로... 사전에 반드시 확인하세요!
```

## 사전 준비
피펫과 비슷한 형태의 점적기를 실험대 위에 설치합니다. 떨어지는 물방울을 받을 수 있도록 아래에 물받이 쟁반을 놓습니다. 실험 장치 옆에 스트로보스코프를 배치합니다. 물방울이 떨어지는 속도와 스트로보스코프의 적정 진동수를 미리 시험해 봅니다. 또한 진자 실험 장치도 준비하되, 진자의 길이가 너무 길지 않게 합니다(진자의 주기를 미리 측정해 두세요!).

```{figure} demo44_figure1.JPG
---
width: 70%
align: center
name: demo44_fig1
alt: 함수 발생기에 연결된 LED 스트립과 앞쪽에 놓인 물 점적기로 구성된 실험 장치.
---
실험 장치.
```

```{tip}
물방울이 연속해서 떨어지는 진동수를 구한 뒤, 함수 발생기를 그 진동수에 맞추어 설정하세요.
```

## 실험 과정
학생들에게 실험 장치를 보여 줍니다. 스트로보스코프를 켜고 수도꼭지를 살짝 열어 물방울이 빠르게 연속해서 떨어지게 합니다. 섬광 진동수를 조절하면 물방울이 공중에 '멈춰' 있게 하거나, 천천히 떨어지게 하거나, 심지어 위로 올라가는 것처럼 보이게 만들 수 있습니다.

점적기를 치우고 진자로 바꿉니다. 진자가 양 끝점이나 평형 위치에서만 보이도록 섬광 진동수를 맞춥니다. 학생들에게 진자가 앞뒤로 왕복 운동을 하는지 아니면 정지해 있는지 구별할 수 있겠느냐고 질문합니다. 그런 다음 섬광 진동수를 조금 높이면 어떻게 보일지 예상해 보게 합니다. 실제로 섬광 진동수를 높여 학생들의 예상을 확인합니다.

## 물리학적 배경
스트로보스코프의 진동수가 물방울이 떨어지는 진동수와 같으면, 뒤따라 떨어지는 물방울들이 이전 물방울과 같은 위치에서 보이게 됩니다. 따라서 물방울들이 공중에 '멈춘' 것처럼 보입니다. 진동수를 약간 높이면 다음 물방울이 이전 물방울보다 조금 위쪽에서 보이게 되므로, 물방울들이 천천히 위로 올라가는 것처럼 보입니다.

```{tip}
Phyphox 앱을 사용하면 물방울의 진동수를 측정할 수 있으며, 이때 음향 스톱워치(acoustic chronometer) 기능을 활용하면 됩니다.

이 주제에 관한 훌륭한 [참고 영상](https://www.youtube.com/watch?v=LdEbyvUOlsg)도 있습니다.
```

스트로보스코프의 각 섬광은 영상의 한 프레임에 해당합니다. 즉, 운동을 표본 추출(샘플링)하고 있는 것입니다.

(디지털 방식으로) 표본을 추출하여 아날로그 신호를 온전히 복원하려면 한 주기당 최소 2번 이상 측정해야 합니다. 이를 나이퀴스트(Nyquist) 기준이라고 합니다. 표본 추출 진동수(샘플링 주파수)가 이 기준보다 낮으면 에일리어싱(aliasing) 현상이 발생하며, 영화에서 자동차 바퀴가 뒤로 도는 것처럼 보이는 현상이 바로 이 때문입니다.

```{note}
검토자 중 한 분은 다음과 같이 평가했습니다. "'거꾸로 올라가는 물방울'은 학생들의 놀라움을 자아내는 아주 흥미로운 시범 실험입니다. 많은 학생이 물방울의 움직임을 보면서 섬광 진동수와 물방울 낙하 진동수 사이의 관계를 금방 깨달았습니다."
```

## 후속 활동
학생들에게 작은 장난감 자동차를 이용해 등속 운동과 등가속도 운동을 하는 스톱모션 영상을 만들어 보게 합니다. 그리고 스톱모션 영상이 이 시범 실험과 어떤 관련이 있는지 질문해 봅니다.

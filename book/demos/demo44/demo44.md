# 거꾸로 맺히는 물방울

<span style="font-size: 25px; color: gray;">샘플링</span>

<table style="width: 100%; border-collapse: collapse; border: none;">
    <tr style="background-color: var(--background-color);">  
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">저자:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">프릭 폴스</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">시간:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">15분</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">연령 그룹:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">11학년</td>
    </tr>
    <tr style="background-color: var(--background-color);"> 
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">개념:</td>
        <td style="text-align: left; padding: 3px; border: none; color: var(--text-color)">주파수, 샘플링, 나이퀴스트</td>
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
영화나 광고에서 자동차가 앞으로 가는데 바퀴는 뒤로 회전하는 것을 본 적이 있을 것입니다. 그것은 어떻게 작동할까요? 그리고 신호를 재구성할 수 있도록 (아날로그) 신호를 (디지털로) 샘플링하려면 얼마나 많은 측정값이 필요할까요?

## 장비
* 스포이트 (상단에 큰 저장소가 있는 것이 가장 좋음)
* 스트로보스코프 (또는 LED 스트립과 듀티 사이클 조절이 가능한 주파수 발생기)
* 물받이
* 물
* 어두운 방
* 진자

```{warning}
깜박이는 빛에 민감한 사람이 있을 수 있습니다... 미리 확인하십시오!
```

## 준비
피펫팅에 사용되는 것과 유사한 스포이트를 테이블 위에 놓습니다. 그 아래에 물방울을 받을 물받이를 놓습니다. 설정 옆에 스트로보스코프를 배치합니다. 물방울이 떨어지는 속도와 스트로보스코프의 적절한 주파수를 미리 테스트해 보십시오. 또한 진자 설정을 준비하고, 진자의 길이가 너무 길지 않도록 하십시오(주기를 미리 측정해 두십시오!).

```{figure} demo44_figure1.JPG
---
width: 70%
align: center
name: demo44_fig1
alt: 설정, LED 스트립에 연결된 함수 발생기, 앞쪽에 물 스포이트.
---
설정.
```

```{tip}
물방울이 연속해서 떨어지는 주파수를 결정하십시오. 주파수 발생기를 이 주파수로 설정하십시오.
```

## 절차
학생들에게 실험 설정을 보여줍니다. 스트로보스코프를 켜고 물방울이 빠르게 연속해서 떨어지도록 수도꼭지를 살짝 엽니다. 플래시 주파수를 조절하여 물방울을 '얼리거나', 천천히 떨어지게 하거나, 심지어 위로 솟아오르게 할 수 있습니다.

스포이트를 진자로 교체합니다. 진자가 양쪽 끝 지점이나 평형 위치에서만 보이도록 플래시 주파수를 설정합니다. 학생들에게 진자가 앞뒤로 움직이고 있는지 아니면 가만히 있는지 알 수 있는지 물어봅니다. 그런 다음 플래시 주파수를 약간 높이면 무엇이 보일지 묻습니다. 플래시 주파수를 높여 그들의 답변을 확인합니다.

## 물리 배경
스트로보스코프의 주파수가 물방울이 떨어지는 주파수와 같으면, 연속되는 물방울들이 같은 위치에서 보입니다. 따라서 물방울들이 공중에 '얼어 있는' 것처럼 보입니다. 주파수를 약간 높이면, 다음 물방울이 이전 물방울보다 약간 높은 위치에서 보입니다. 그러면 물방울들이 천천히 위로 움직이는 것처럼 보입니다.

```{tip}
Phyphox를 사용하여 물방울의 주파수를 결정할 수 있으며, 이를 위해 음향 크로노미터를 사용할 수 있습니다.

이 주제에 관한 아주 멋진 [동영상들](https://www.youtube.com/watch?v=LdEbyvUOlsg)이 있습니다.
```

스트로보스코프의 각 플래시는 영화의 한 프레임에 해당합니다. 여러분은 운동을 샘플링하고 있는 것입니다.

(디지털로) 샘플을 채취하여 아날로그 신호를 구성하려면 주기당 최소 2회의 측정값이 필요합니다. 이를 나이퀴스트(NyQuist) 기준이라고 합니다. 샘플링 주파수가 이 주파수보다 낮으면 앨리어싱(aliasing)이 발생하며, 영화에서 자동차 바퀴가 뒤로 회전하는 것처럼 보이는 효과가 바로 이것입니다.

```{note}
테스터 중 한 명은 다음과 같이 말했습니다: "'거꾸로 맺히는 물방울'은 학생들의 놀라움을 자아내는 정말 재미있는 시연입니다. 많은 학생이 물방울이 움직이는 방식을 보고 플래시 주파수와 물방울 주파수 사이의 관계를 빠르게 깨달았습니다."
```

## 후속 활동
학생들에게 작은 장난감 자동차가 등속 운동과 등가속 운동을 하는 스톱모션 영화를 만들게 하십시오. 스톱모션 영화가 이 시연과 어떤 관련이 있는지 물어보십시오.

# 물리학을 보여주세요 (Show the Physics)

NVON과 델프트 공과대학교(TU Delft)가 공동 제작한 물리 실험 시연 및 교육 자료 모음집입니다. 이 프로젝트는 Jupyter Book을 사용하여 물리 교육을 위한 다양한 실험 시연(Demos)과 교육학적(Pedagogy) 배경 지식을 제공합니다.

---

## 📚 주요 구성

이 책은 다음과 같은 주요 파트로 구성되어 있습니다:

- **Introduction (소개)**: 프로젝트 배경, 저자 및 서문
- **Pedagogy (교육학)**: 과학의 본성(NoS), 논증(Argumentation), PoE(Predict-Observe-Explain) 등 물리 교육의 이론적 토대
- **Physics Demos (물리 실험 시연)**:
  - **Nature of Science (과학의 본성)** 관련 실험
  - **Scientific Inquiry (과학적 탐구)** 관련 실험
  - **Conceptual Development (개념 발달)**: 파동, 광학, 양자, 전자기학, 역학, 열역학 등 주제별 실험
  - **Special Occasions (특별한 날)**을 위한 실험
- **Pocket Demos (포켓 데모)**: 간편하게 수행할 수 있는 짧은 실험 모음

## 📄 기타 자료

- **PDF 버전**: [book/200demos.pdf](book/200demos.pdf)에서 200가지 물리 데모가 정리된 PDF 파일을 확인할 수 있습니다.
- **이미지 리사이저**: `jpg_file_resizer.ipynb` 노트북을 사용하여 실험 사진의 크기를 일괄 조정할 수 있습니다.

## 🛠️ 로컬 개발 환경 설정

이 프로젝트는 [uv](https://docs.astral.sh/uv/)를 사용하여 의존성을 관리합니다.

### 1. 의존성 설치
```bash
uv sync
```

### 2. 책 빌드 (HTML)
```bash
uv run jupyter-book build book/
```
빌드된 결과물은 `book/_build/html/index.html` 에서 확인할 수 있습니다.

---

## 📜 라이선스 및 제작

- **라이선스**: CC-BY-NC (크리에이티브 커먼즈 저작자표시-비영리)
- **제작**: [NVON](https://www.nvon.nl/), [델프트 공과대학교 (TU Delft)](https://www.tudelft.nl/)


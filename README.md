# Show the Physics (한국어판)

네덜란드 과학교육협회([NVON](https://nvon.nl))와 델프트 공과대학교(TU Delft)가 출판한 물리 시범 실험서 **Show the Physics**(원제: *Show de Fysica*)의 한국어 번역 프로젝트입니다.

이 책은 중·고등학교 물리 수업에서 활용할 수 있는 99가지 물리 시범 실험과 교수법(과학의 본성, 과학적 탐구, 개념 발달, 특별한 날을 위한 시범 등), 그리고 브라우저에서 바로 실행할 수 있는 Python 시뮬레이션 및 포켓 시범 실험(Pocket demos)을 다룹니다.

## 환경 설정 및 로컬 빌드

이 프로젝트는 [uv](https://docs.astral.sh/uv/)를 사용하여 Python 의존성을 관리합니다.

```bash
# 의존성 설치 및 가상환경 동기화
uv sync

# TeachBooks(Jupyter Book) 빌드
uv run teachbooks build book
```

빌드가 완료되면 `book/_build/html/index.html`에서 결과물을 확인할 수 있습니다.

## 배포

`main` 브랜치에 변경 사항이 푸시되면 GitHub Actions 워크플로우를 통해 자동으로 빌드되어 GitHub Pages에 배포됩니다.

## 라이선스 및 저작권

- 원본 저작자: NVON, TU Delft (편집: Freek Pols & Peter Dekkers)
- 라이선스: **CC BY-NC 4.0** (비상업적 목적에 한해 출처를 명시하고 자유롭게 이용 및 수정 가능)
- 원서 저장소: [TeachBooks/Showing-Physics](https://github.com/TeachBooks/Showing-Physics) / [FreekPols/ShowthePhysics](https://github.com/FreekPols/ShowthePhysics)

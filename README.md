# tobal-study

Git과 GitHub를 익히고, 학습한 내용을 기록하며 개인 포트폴리오를 만들어 가는 저장소입니다.

## 🎯 저장소 목적

- Git의 기본 명령어와 버전 관리 흐름 익히기
- GitHub를 활용한 원격 저장소 관리 및 배포 경험 쌓기
- 학습 과정에서 배운 내용과 시행착오를 기록하기
- 데이터 분석가를 목표로 한 개인 포트폴리오 제작 및 개선

## 📅 오늘의 작업 기록

### 2026-11-13 | Git 기초 실습 & 포트폴리오 제작

#### 1. Git 기본 명령어 실습

로컬 저장소를 만들고 파일을 추적해 커밋하는 기본 흐름을 연습했습니다.

| 명령어 | 역할 |
| --- | --- |
| `git status` | 작업 디렉터리와 스테이징 상태 확인 |
| `git config` | 사용자 이름 및 이메일 등 Git 설정 |
| `git remote -v` | 연결된 원격 저장소 확인 |
| `git add` | 변경 파일을 스테이징 영역에 추가 |
| `git commit -m "메시지"` | 스테이징된 변경 사항을 커밋 |
| `git log` | 커밋 기록 확인 |
| `git log --oneline` | 커밋 기록을 한 줄씩 간단히 확인 |
| `git restore --staged 파일명` | 스테이징한 파일을 스테이징 영역에서 내리기 |

**기본 작업 흐름**

```bash
git status
git add 파일명
git commit -m "커밋 메시지"
git log --oneline
```

**실습하며 배운 점**

- Git은 작업 디렉터리, 스테이징 영역, 저장소의 세 단계로 변경 사항을 관리합니다.
- `git add`는 변경 사항을 커밋할 대상으로 선택하는 과정입니다.
- `git commit`은 스테이징 영역에 올라온 변경 사항을 기록합니다.
- 이미 커밋한 파일은 `git restore --staged`로 취소하는 대상이 아닙니다. 이 명령은 아직 커밋하지 않은 스테이징 상태를 되돌릴 때 사용합니다.
- 명령어의 철자와 옵션 앞의 하이픈(`-`)을 정확히 입력해야 합니다.

#### 2. 개인 포트폴리오 제작

데이터 분석가를 목표로 하는 개인 소개 페이지를 HTML과 CSS 중심으로 제작하고 개선했습니다.

- **About:** 컴퓨터공학 학습 및 데이터 분석가를 향한 목표 소개
- **Tech Stack:** Python, SQL, PostgreSQL, Pandas, NumPy, Tableau, Git 등 학습 기술 정리
- **Projects:** 주식 분석, 시계열 분석, 데이터 시각화 주제 구성
- **Contact:** 연락을 위한 영역 구성

초기 포트폴리오를 개선하면서 다음 요소를 추가했습니다.

- 화면 크기에 따라 배치가 바뀌는 반응형 레이아웃
- 모바일 화면에서 사용할 수 있는 햄버거 메뉴
- SVG를 활용한 시계열 그래프 형태의 시각 요소
- About, Skills, Projects, Focus, Contact 섹션 구성
- 스크롤 진입 애니메이션과 접근성 고려
- 따뜻한 배경색과 차콜, 라임, 오렌지 중심의 디자인

#### 3. GitHub Pages 배포 준비

- 기존 포트폴리오를 개선하고 저장소의 `index.html`에 반영했습니다.
- GitHub Pages에서 사용할 수 있도록 `docs/index.html`을 생성했습니다.
- Pages 배포 경로를 `main` 브랜치의 `/docs` 폴더로 사용하는 방식으로 구성했습니다.

🔗 **[포트폴리오 페이지 열기](https://im-gitttt.github.io/tobal-study/docs/index.html)**

## 🧰 사용 기술

- HTML
- CSS
- JavaScript
- Git & GitHub
- GitHub Pages

## 📂 주요 파일

| 경로 | 설명 |
| --- | --- |
| `index.html` | 저장소 루트의 포트폴리오 페이지 |
| `docs/index.html` | GitHub Pages 배포용 포트폴리오 페이지 |
| `test/index.html` | Git 기초 실습 및 초기 포트폴리오 작업 파일 |
| `README.md` | 저장소 소개와 학습 기록 |

## 📝 학습 기록

학습한 내용은 GitHub Issues를 활용해 TIL, 회고, 부검 형태로 정리합니다.

- [학습 기록 및 TIL 이슈](https://github.com/im-gitttt/tobal-study/issues)

## 🚀 앞으로의 계획

- [ ] Git의 branch, merge, pull, push 흐름 익히기
- [ ] 포트폴리오의 프로젝트 내용을 실제 분석 결과로 교체하기
- [ ] 주식 및 시계열 데이터 분석 프로젝트 추가하기
- [ ] GitHub Issues에 학습 내용과 문제 해결 과정 꾸준히 기록하기

---

꾸준히 기록하고 개선하면서 개발 및 데이터 분석 역량을 쌓아가는 저장소입니다.


# b;eat Landing Page

로봇카페 프랜차이즈 **b;eat**의 영업/프랜차이즈 소개용 랜딩 페이지입니다. 브랜드 소개, 도입 상권, 기술력, 인건비 절감 효과, 투자 유형 등 전 섹션을 스크롤 인터랙션과 함께 담은 싱글 페이지 사이트입니다.

## 데모

- Live: https://jandela00.github.io/beat-landing/

## 기술 스택

- **HTML5 / CSS3 / Vanilla JavaScript** — 별도 프레임워크나 번들러 없이 순수 웹 표준만으로 작성된 단일 파일(`index.html`) 프로젝트입니다.
- 빌드 도구, 패키지 매니저, 외부 JS 라이브러리 의존성 없음 (웹폰트만 CDN에서 로드).
- 로컬 개발/미리보기는 정적 파일 서버(예: `npx serve`)만 있으면 됩니다.

## 폴더 구조

```
.
├── index.html          # 전체 페이지 (마크업 + 스타일 + 스크립트가 모두 이 한 파일에 포함)
├── assets/              # 이미지, 영상, 아이콘 등 정적 리소스
├── .claude/
│   └── launch.json      # Claude Code 브라우저 미리보기 도구용 로컬 서버 실행 설정
├── .gitignore
└── README.md
```

## 설치 방법

별도 설치가 필요 없습니다. 이 저장소를 clone하기만 하면 바로 실행할 수 있습니다.

```bash
git clone https://github.com/jandela00/beat-landing.git
cd beat-landing
```

## 로컬 실행 방법

정적 파일이므로 아무 정적 서버로 열어도 됩니다. 예시:

```bash
npx serve .
```

이후 안내되는 로컬 주소(기본값 `http://localhost:3000`, 이 프로젝트는 보통 `5173` 포트로 실행)로 브라우저에서 접속하면 됩니다.

> `index.html`을 브라우저에서 바로 더블클릭해서 열어도 대부분 정상 표시되지만, 일부 브라우저는 `file://` 경로에서 리소스 로드를 제한할 수 있어 로컬 서버 사용을 권장합니다.

## 빌드 방법

빌드 과정이 없습니다. `index.html`이 곧 배포 산출물입니다. GitHub Pages 배포 시 저장소 루트(`main` 브랜치)를 그대로 소스로 사용합니다.

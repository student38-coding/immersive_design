# AURA: The Immersive Light & Sound Journey

몰입형 라이트 & 사운드 전시회 "AURA"의 UI 디자인입니다.

## 프로젝트 설명

Google Stitch로 제작된 AURA 전시회의 웹 UI입니다. 빛과 소리가 어우러진 몰입형 아트 경험을 위한 반응형 웹 디자인을 제공합니다.

### 주요 기능

- 🎨 몰입형 히어로 섹션
- 🌟 3가지 핵심 체험 소개 (AURORA, ECHO, VOID)
- 🖼️ 갤러리 섹션
- 📍 위치 및 일정 정보
- 🎫 티켓 예매 CTA 버튼
- 📱 완전 반응형 디자인

### 기술 스택

- HTML5
- Tailwind CSS (CDN)
- Google Fonts (Manrope)
- Material Symbols Icons
- Node.js + Express (서버)

## 로컬 개발

### 설치

```bash
npm install
```

### 개발 서버 실행

```bash
npm start
```

브라우저에서 `http://localhost:3000` 접속

## Railway 배포

### Railway CLI 사용

1. Railway CLI 설치:
```bash
npm install -g @railway/cli
```

2. Railway 로그인:
```bash
railway login
```

3. 프로젝트 초기화:
```bash
railway init
```

4. 배포:
```bash
railway up
```

### Railway 웹 인터페이스 사용

1. [Railway](https://railway.app/)에 로그인
2. "New Project" 클릭
3. "Deploy from GitHub repo" 선택
4. 이 리포지토리 선택
5. Railway가 자동으로 감지하고 배포합니다

### 환경 변수

기본 포트는 `3000`이지만 Railway는 자동으로 `PORT` 환경 변수를 설정합니다.

필요시 Railway 대시보드에서 추가 환경 변수를 설정할 수 있습니다.

## 프로젝트 구조

```
immersive_design/
├── index.html          # 메인 HTML 파일
├── screen.png          # 디자인 스크린샷
├── server.js           # Express 서버
├── package.json        # Node.js 의존성
├── .gitignore         # Git 제외 파일
└── README.md          # 프로젝트 문서
```

## 배포 체크리스트

- [x] index.html 파일 준비
- [x] Express 서버 설정
- [x] package.json 구성
- [x] .gitignore 추가
- [x] Railway 호환성 확인

## 라이선스

ISC

## 지원

문제가 발생하면 이슈를 생성해주세요.

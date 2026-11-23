<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4F46E5,100:06B6D4&height=180&section=header&text=Kim%20Mugyeom&fontSize=44&fontColor=ffffff&fontAlignY=36&desc=Frontend%20Developer&descSize=18&descAlignY=56" width="100%" />

**기획부터 출시까지, 사용자 입장에서 화면을 만드는 프론트엔드 개발자입니다.**

</div>

<br/>

## About

컴퓨터공학과를 전공한 개발자입니다.<br>
Flutter 앱 **칼캘**을 혼자 기획하고 개발해서 App Store에 출시했고, 지금은 캡스톤 프로젝트 **EV-flow**에서 프론트엔드를 맡고 있습니다.

기능을 만들기 전에 "사용자가 이 화면에서 뭘 하려는지"부터 정리하는 편입니다.
학원에서 정보 과목을 가르치면서 어려운 개념을 쉽게 설명하고 문서로 남기는 데 익숙해졌습니다.

<br/>

## Projects

### EV-flow — 전기차 충전소 혼잡 예측·추천 서비스

실시간 충전기 상태로 15 / 30 / 60분 뒤 혼잡도를 예측하고, 지금 가기 가장 좋은 충전소를 추천

| | |
|---|---|
| **형태** | 캡스톤 팀 프로젝트 (FE / BE / AI) · 2026.09 ~ 진행 중 |
| **역할** | 프론트엔드 |
| **Stack** | React 18, TypeScript, Vite, Tailwind CSS, TanStack Query, MSW, Recharts |
| **Links** | [Service](https://evflowkr.app) · [Repository](https://github.com/2026-Capstone4/ev-flow) |

**서비스**
- 광진구 급속 충전소 46곳(충전기 116기)의 상태를 5분 간격으로 수집
- XGBoost로 예측 시점별 혼잡도 예측, 이동거리 + 대기시간 + 미래 혼잡도를 합쳐 추천 점수 계산

**내가 한 일**
- TanStack Query로 60초 폴링, 화면이 비활성일 때 폴링 중단, 갱신에 실패하면 마지막 정상값을 유지하고 경고 표시
- MSW로 API를 mock해서 백엔드와 병렬로 개발
- 네이버 지도 API로 충전소 지도와 경로 표시, 혼잡도 3단계(여유 / 보통 / 혼잡) 색상 UI
- Recharts로 관리자 대시보드(충전소별 시간대·요일별 이용률) 구현

<br/>

### 칼캘 — 칼로리 캘린더

먹은 음식과 칼로리를 캘린더에 기록하고 AI로 분석·추천받는 앱

| | |
|---|---|
| **형태** | 1인 개발 · App Store 출시 (2026.08) |
| **역할** | 기획, 개발, 배포, 심사 대응 |
| **Stack** | Flutter, Dart |
| **Links** | [App Store](https://apps.apple.com/kr/app/id6802026331) · [Repository](https://github.com/kkyom/cal_cal_app) |

- Apple / Google 소셜 로그인, 회원탈퇴(계정 삭제)
- 음식·영양 데이터 외부 API 연동
- 식단 기록 기반 AI 분석 및 추천
- App Store 심사 피드백(Guideline 2.1)을 받고 대응해서 출시


<br/>

## Tech Stack

| | |
|---|---|
| **Frontend** | <img src="https://skillicons.dev/icons?i=react,ts,vite,tailwind" height="40"/> &nbsp; + TanStack Query |
| **Mobile** | <img src="https://skillicons.dev/icons?i=flutter,dart" height="40"/> |
| **써본 적 있음** | <img src="https://skillicons.dev/icons?i=spring,fastapi,docker,githubactions" height="40"/> |
| **Collaboration** | <img src="https://skillicons.dev/icons?i=git,notion,discord" height="40"/> |

<br/>

## Now

- EV-flow 프론트엔드 개발 및 AI 예측 결과 연동
- React → React Native 전환 공부

<br/>

## Contact

<a href="mailto:mu04299@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://apps.apple.com/kr/app/id6802026331"><img src="https://img.shields.io/badge/칼캘_App_Store-0D96F6?style=for-the-badge&logo=appstore&logoColor=white"/></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4F46E5,100:06B6D4&height=100&section=footer" width="100%" />

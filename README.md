
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:f8d5dc,100:fffbf0&height=180&text=Hello,%20Seohyun's%20World!&animation=fadeIn&fontColor=815f5f&fontSize=40" />
</div>

# Hello! I'm Seohyun 🌟
**portfolio site: https://hyuni.site**
* 📧 **Email:** [hyuniii0920@gmail.com](mailto:hyuniii0920@gmail.com)
* 📑 **Resume:** [Notion Portfolio](https://www.notion.so/SEOHYUN-CHO-658f109a9b758248804301d9b82ebddd)

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:F7D9DC,100:FFF7E8&height=180&section=header&text=SEO%20HYUN%20CHO&fontSize=42&fontColor=76565B&animation=fadeIn&fontAlignY=38&desc=Frontend%20Developer%20%C2%B7%20AI%20Product%20Builder&descAlignY=59&descSize=16" />

  <a href="https://hyuni.site"><img src="https://img.shields.io/badge/Portfolio-hyuni.site-76565B?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="mailto:hyuniii0920@gmail.com"><img src="https://img.shields.io/badge/Email-Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.notion.so/SEOHYUN-CHO-658f109a9b758248804301d9b82ebddd"><img src="https://img.shields.io/badge/Resume-Notion-000000?style=flat-square&logo=notion&logoColor=white" alt="Resume" /></a>
</div>

## 안녕하세요, 조서현입니다.

사용자 경험을 설계하고, 이를 **동작하는 제품**으로 구현하는 개발자입니다.  
프론트엔드에서 시작해 AI 파이프라인·백엔드·데이터 설계까지 확장하며, 사용자가 신뢰하고 실제로 쓸 수 있는 서비스를 만듭니다.

<br />

## Experience

**메가존클라우드 · ATU Data & Design Whole 팀**  
`2025.11 — 2026.01` · Frontend & UX/UI Intern

- B2B/B2C 멀티테넌트 SaaS LMS의 프론트엔드 개발
- 6개 직급 통합 라우팅, 테넌트별 브랜딩·기능 플래그, JWT Refresh Queue 패턴 설계

**제로웹(IT) · Frontend 개발 & UX/UI 디자인 팀**  
`2024.07 — 2024.08` · Frontend & UX/UI Design Intern

- Care Bell 위치 기반 노약자 케어 서비스의 기획·Figma 디자인·퍼블리싱 전 과정 단독 수행
- 운영 서비스 UI 오류·브라우저 호환성 개선 및 Design-to-Code 협업

<br />

## Projects

### CLAIR — AI 계약서 분석 서비스

`2026.03 — 2026.06` · **AI 파이프라인 · Backend · PM**  
OCR, LLM, RAG를 연결해 계약서의 위험 조항·Safety Score·근거 조항을 제공하는 한국어 계약서 분석 플랫폼입니다.

- FastAPI 인증·계약서·채팅 REST API, SQLAlchemy 2.x·MySQL 8 모델 설계
- LLM의 비일관적인 점수 산출을 백엔드 알고리즘으로 분리해 재현 가능한 Safety Score 구현
- 조항 단위 스키마와 `evidence_clause_ids`로 RAG 답변의 근거를 화면에서 확인하는 UX 구현
- 스캔 PDF OCR 처리 분기로 분석 시간을 최대 8배 개선, Gemini 장애 시 키워드 기반 폴백 적용

`React 18` `TypeScript` `Vite` `Tailwind CSS 4` `Radix UI` `FastAPI` `SQLAlchemy 2.x` `MySQL 8` `EasyOCR` `Google Gemini` `ChromaDB` `Gemini Embedding`

### Growbase — B2B/B2C 멀티테넌트 LMS

`2025.11 — 2026.01` · **Frontend**  
하나의 코드베이스로 복수 기업의 독립 학습 환경과 B2B/B2C 학습 경험을 지원하는 SaaS LMS입니다.

- hostname 기반 서브도메인과 `X-Subdomain` 헤더, CSS 변수 기반 테넌트 브랜딩 구조 설계
- B2B/B2C 흐름과 SA·TA·CO·DESIGNER·INSTRUCTOR·USER 6개 직급의 독립 라우팅 구성
- 토큰 만료 시 동시 refresh 요청을 하나로 처리하는 JWT Refresh Queue 패턴 적용
- React Query Key Factory로 캐시 키와 invalidate 범위 일관성 확보

`React 19` `TypeScript 5.6` `Vite 6` `Tailwind CSS + CVA` `Radix UI` `Zustand` `React Query` `react-router-dom v7` `Spring Boot` `JWT` `MySQL / PostgreSQL`

### 동백웨이 — 부산 통합 관광 플랫폼

`2026.07` · **PM · 기획 총괄 · UX/UI · Data/Backend**  
지역화폐 동백전을 여행자의 탐색·예약·일정·현장 소통·결제·리뷰 경험에 연결한 DIVE 2026 프로젝트입니다.

- 문제 정의부터 기능 우선순위, 팀 업무 분배, 전체 UX/UI, 피치덱·발표까지 프로젝트 전 과정 총괄
- 119,260건 가맹 원천 데이터를 수집·정제·검증해 재현 가능한 장소 데이터 파이프라인 설계
- Firebase Data Connect 중심의 관계형 데이터 구조를 재설계하고, FastAPI 기반 사용자·사장님 MCP 구현

`Figma` `Python` `Kakao Local API` `Firebase Data Connect` `Cloud SQL for PostgreSQL` `FastAPI` `FastMCP` `Firebase Admin SDK` `GraphQL` `Pydantic` `Railway` `Docker`

### ArtBusan — QR·AR 기반 전시 안내 Android 앱

`2026.04 — 현재` · **기획 · Android**  
불안정한 전시장 네트워크에서도 QR·AR 작품 정보와 4개국어 안내를 제공하는 Offline-First 전시 플랫폼입니다.

- 앱 초기 구조·다크 디자인 시스템·QR/AR 안내 사용자 흐름 기획 및 구현
- Room DB에 번들 데이터를 시드하고, API 실패 시 로컬 데이터를 조회하는 Offline-First 구조 구현
- 앱 재설치 없이 한·영·일·중 4개국어를 즉시 전환하는 런타임 전환 파이프라인 구현

`Kotlin + Coroutines` `KSP` `Jetpack Navigation` `Room 2.7` `Retrofit 2.11 + Gson` `CameraX 1.4` `ML Kit Barcode Scanning` `Android TTS API`

<details>
<summary><b>More projects</b></summary>
<br />

**PIYAK(dansynkpop)** · AI  
K-pop 안무 영상에서 멤버별 마스크 영상을 생성하는 반자동화 파이프라인을 구현했습니다. 첫 프레임의 멤버 지정 후 SAM2가 이후 프레임을 추적하도록 설계했고, Django REST·Cloudflare R2·PeerTube로 영상 저장과 스트리밍을 분리했습니다.  
`SAM2` `Python` `Django REST Framework` `Cloudflare R2` `PeerTube` `Oracle Cloud (Ubuntu)`  
🏆 2026 경성대학교 글로컬 Innovation Challenge Day 대상(총장상)

**SAI (Smishing Prevention AI)** · 기획 · Frontend · Backend  
의심스러운 문자·메신저 화면을 OCR·LLM으로 분석하고, 위험도·대응 가이드를 보여주는 Android·Web 통합 스미싱 예방 서비스입니다. Firebase 기반 인증·데이터 흐름과 React·Spring Boot 배포 자동화를 구성했습니다.  
`Kotlin` `React` `Vite` `Spring Boot` `Java 21` `Firebase Auth` `Firestore` `Firebase Storage` `Firebase Admin SDK` `GitHub Actions`  
🏆 피싱스캠 예방 서비스 개발 경진대회 전체 644팀 중 상위 15%

</details>

<br />

## Tech

프로젝트에서 실제로 사용한 기술입니다.

| Area | Technologies |
| :-- | :-- |
| **Frontend** | React 18/19 · TypeScript · JavaScript · Vite · Tailwind CSS · Radix UI · Zustand · React Query |
| **Backend** | FastAPI · SQLAlchemy · Spring Boot · Django REST Framework · MySQL · PostgreSQL · REST API · GraphQL |
| **AI & Data** | Google Gemini · LangChain · ChromaDB · Gemini Embedding · EasyOCR · SAM2 · Kakao Local API |
| **Android** | Kotlin · Coroutines · Room · CameraX · ML Kit · Retrofit · Jetpack Navigation |
| **Infra** | Firebase · Cloud SQL · Docker · Railway · Cloudflare R2 · PeerTube · GitHub Actions |
| **Product & Design** | Figma · User Journey · Wireframe · Service Planning · Feature Prioritization |

<br />

## Education & activities

- 🎓 **경성대학교 컴퓨터공학과** · 2022 — 2026.08 졸업예정
- 🧪 **경성대학교 Infonet Lab** · 연구원 및 랩장 · 2022.03 — 2026.08
- 🧠 **LG Aimers 7기** · 산업 데이터 기반 AI 전문가 과정 수료 · 2025.07 — 2025.08
- 🤝 **IT 연합동아리 PROJECT** · 운영진 · 2024 — 현재
- 📝 **정보처리기사** · 필기 합격, 실기 준비 중

<div align="center">
  <br />
  <a href="https://hyuni.site">Portfolio</a> ·
  <a href="mailto:hyuniii0920@gmail.com">Email</a> ·
  <a href="https://www.notion.so/SEOHYUN-CHO-658f109a9b758248804301d9b82ebddd">Resume</a>
  <br /><br />
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:F7D9DC,100:FFF7E8&height=100&section=footer" />
</div>

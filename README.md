# 유종안 포트폴리오

웹 구현, 데이터 기반 서비스, 지도 API, AI 도구, IoT/임베디드 프로젝트와 디자인/영상/3D 작업을 한 페이지에서 볼 수 있도록 정리한 개인 포트폴리오입니다.

정적인 소개 페이지가 아니라 프로젝트 카드, 상세 모달, 이미지 프리뷰, 영상 섹션, 배포 링크까지 포함한 반응형 웹사이트로 구성했습니다.

![포트폴리오 메인 화면](images/preview-desktop-home.png)

## 구성

- About: 자기소개, 작업 방향, 경험 요약
- Experience: LMS 개발 및 유지보수, 서버 관리, 데이터 관리 경험
- Skills: 웹 구현 기술과 디자인, 영상, 3D 작업 역량
- Projects: 웹 서비스, AI 도구, 지도 서비스, 전적검색, 데이터 대시보드, IoT 프로젝트
- Design: 배너, 쿠폰, 포스터, 상품 홍보 그래픽
- 3D / Video: Blender 렌더링, 2D+3D 모션, 영상 편집 작업
- Contact: GitHub, 이메일, 이력서 연결

## 주요 프로젝트

### Rift Record

Riot Games API를 사용해 League of Legends와 Teamfight Tactics 전적을 분리 조회하고 분석하는 서비스입니다.
검색 직후 프로필, 티어, 최근 15게임 요약, 최근 게임 목록을 먼저 볼 수 있도록 정보 구조를 정리했고, 분석 영역은 접힘 구조로 분리했습니다.
TFT 탭에서는 랭크, 최근 10게임 요약, 유닛/특성/증강체 중심의 카드형 UI를 제공합니다.

- 배포: https://rift-record.vercel.app/
- GitHub: https://github.com/ajttk369/rift-record
- 사용 기술: HTML, CSS, Vanilla JavaScript, Node.js, Riot API, TFT API, Data Dragon, Supabase, Vercel
- 구현 범위: Riot ID 검색, LoL/TFT 탭 분리, 게임 유형 필터, 상세보기 참여자 재검색, 라이트/다크 테마, TFT 한글 데이터 매핑, Supabase 매치 저장

### CareerLens AI 포트폴리오 분석

지원 직무와 포트폴리오 내용을 입력하면 강점, 보완점, 개선 우선순위, 예상 면접 질문을 정리해주는 AI 포트폴리오 리뷰 도구입니다.
분석 결과 저장, 공유 리포트, 삭제까지 이어지는 흐름을 구현했습니다.

- 배포: https://careerlens-ai-kohl.vercel.app/
- GitHub: https://github.com/ajttk369/CareerLens-AI
- 사용 기술: Next.js, TypeScript, OpenAI, Supabase, Tailwind CSS, Vercel

### InsightBoard

CSV 매출 데이터를 업로드해 KPI, 차트, 인사이트, 원본 테이블을 확인하는 데이터 대시보드입니다.
브라우저에서 CSV를 파싱하고 필터 조건에 맞춰 지표와 차트가 함께 갱신되도록 구성했습니다.

- 배포: https://insightboard-xi.vercel.app/
- GitHub: https://github.com/ajttk369/InsightBoard
- 사용 기술: Next.js, TypeScript, Tailwind CSS, Recharts
- 구현 범위: CSV 업로드, KPI 계산, 차트 시각화, 필터링, 테이블, CSV 다운로드, 리포트 저장

### 지도로 지도 서비스

장소명과 주소를 검색하고 지도 위에서 결과, 상세 정보, 즐겨찾기, 길찾기를 확인할 수 있는 지도 기반 웹 서비스입니다.
Naver 지도/검색/좌표/길찾기 API와 TAGO 교통 API를 연결해 지도 중심의 검색 흐름을 구현했습니다.
거리뷰와 일부 고급 기능은 현재 업데이트 중 상태로 표시했습니다.

- 배포: https://jidoro-map.vercel.app/
- GitHub: https://github.com/ajttk369/jidoro-map
- 사용 기술: Next.js 14, React 18, TypeScript, Tailwind CSS, LocalStorage, Vercel
- 사용 API: Naver Maps JavaScript API, Naver Local Search API, Naver Cloud Geocoding API, Naver Cloud Reverse Geocoding API, Naver Cloud Directions API, TAGO 교통 정보 API
- 구현 범위: 장소/주소 검색, 지도 마커, 결과 목록, 상세 패널, 즐겨찾기, 자동차/대중교통/도보/자전거 길찾기, 모바일 하단 시트 UI

### 학생 관리 시스템

Python Flask와 SQLite를 사용해 학생 데이터를 등록, 조회, 수정, 삭제할 수 있는 관리자 페이지입니다.
검색, 필터, 통계 카드, 수정 dialog 등 실제 관리 화면에서 필요한 흐름을 중심으로 구현했습니다.

- 배포: https://student-lms-manager.onrender.com/
- GitHub: https://github.com/ajttk369/student-lms-manager
- 사용 기술: Python, Flask, SQLite, HTML/CSS/JavaScript

### 웹사이트 리뉴얼

온라인몰 화면을 참고해 홈 화면 정보 구조와 픽업 주문 흐름을 개선한 UX/UI 리뉴얼 프로토타입입니다.
상품 탐색, 매장 재고 확인, 픽업 가능 매장 추천, 로그인 모달 흐름을 한 페이지 안에서 자연스럽게 이어지도록 구성했습니다.

- 배포: https://website-renewal-navy.vercel.app/
- GitHub: https://github.com/ajttk369/InsightBoard
- 사용 기술: HTML5, CSS3, JavaScript, Vercel
- 구현 범위: 홈 화면 정보 구조 재배치, 상품/매장 카드, 픽업 가능 정보, 로그인 모달, 반응형 UI

### Shopping Mall Page

쇼핑몰 서비스를 가정해 제작한 웹 페이지입니다.
상품 목록, 브랜드, 이벤트, 검색, 마이페이지 흐름을 중심으로 화면을 구성했습니다.

- 배포: https://shopping-mall-rosy.vercel.app/
- GitHub: https://github.com/ajttk369/Shopping-mall
- 사용 기술: HTML, CSS, JavaScript, Python

### AI Future Expo

AI 전시 홍보를 위한 반응형 웹사이트입니다.
전시 정보, 프로그램, 홍보 콘텐츠를 한 화면에서 볼 수 있도록 구성하고 Vercel에 배포했습니다.

- 배포: https://ai-expo-sooty.vercel.app/
- GitHub: https://github.com/ajttk369/AI-Expo
- 사용 기술: HTML, CSS, JavaScript, Premiere Pro, After Effects

### Automatic Cup Collector

Raspberry Pi와 Python을 사용해 컵을 인식하고 분류하는 자동 수거기 프로젝트입니다.
카메라 인식, 분류 흐름, 시연 영상과 기획 자료를 포트폴리오에 함께 정리했습니다.

- 사용 기술: Raspberry Pi, Python, Machine Learning, OpenCV

### Smart Parking System

Arduino, NFC, Bluetooth를 사용한 무선 주차 시스템 프로젝트입니다.
주차 상태 확인과 사용자 인증 흐름을 중심으로 구현했습니다.

- 사용 기술: Arduino, C++, NFC, Bluetooth, IoT

## 기술 스택

- HTML / CSS / JavaScript
- TypeScript / React / Next.js
- Python / Flask / SQLite / SQL
- Node.js / REST API / Supabase / Vercel
- Riot API / TFT API / Data Dragon
- Naver Maps API / Naver Local Search API / Naver Directions API / TAGO API
- Arduino / Raspberry Pi

## 디자인 · 영상 · 3D 도구

- Photoshop
- Illustrator
- Premiere Pro
- After Effects
- Blender
- Figma

## 로컬 실행

별도 빌드 과정 없이 `index.html`을 브라우저에서 열어 확인할 수 있습니다.

```bash
start index.html
```

## 폴더 구조

```text
.
├─ index.html
├─ README.md
├─ resume.pdf
├─ cup-collector-plan.pdf
├─ images/
└─ videos/
```

# 유종안 포트폴리오

웹 구현, 데이터 기반 서비스, 디자인/영상/3D 작업을 한 페이지에서 볼 수 있도록 정리한 개인 포트폴리오입니다.
정적인 소개 페이지가 아니라 프로젝트 카드, 상세 모달, 이미지 갤러리, 영상 섹션까지 포함한 반응형 웹사이트로 구성했습니다.

![포트폴리오 메인 화면](images/preview-desktop-home.png)

## 구성

- About: 자기소개, 작업 방향, 경험 요약
- Experience: LMS 개발 및 유지보수, 서버 관리, 데이터 관리 경험
- Skills / Tools: 웹 구현 기술과 디자인/영상/3D 도구
- Projects: 웹 서비스, 데이터 대시보드, IoT/임베디드 프로젝트
- Design: 배너, 쿠폰, 포스터, 상품 홍보 그래픽
- 3D / Video: Blender 렌더링, 2D+3D 모션, 영상 편집 작업
- Contact: GitHub, 이메일, 이력서 연결

## 주요 프로젝트

### InsightBoard

CSV 매출 데이터를 업로드해 KPI, 차트, 인사이트, 원본 테이블을 확인하는 데이터 대시보드입니다.
브라우저에서 CSV를 파싱하고, 필터 조건에 맞춰 지표와 차트가 함께 갱신되도록 구성했습니다.

- GitHub: https://github.com/ajttk369/InsightBoard
- 사용 기술: Next.js, TypeScript, Tailwind CSS, Recharts
- 구현 범위: CSV 업로드, KPI 계산, 차트 시각화, 필터링 테이블, CSV 다운로드, 리포트 저장

### CareerLens AI 포트폴리오 분석

지원 직무와 포트폴리오 내용을 입력하면 강점, 보완점, 개선 방향을 정리해주는 리뷰 도구입니다.
분석 결과 저장, 공유 리포트, 삭제 흐름까지 포함해 하나의 서비스처럼 사용할 수 있도록 구현했습니다.

- 배포: https://careerlens-ai-kohl.vercel.app/
- GitHub: https://github.com/ajttk369/CareerLens-AI
- 사용 기술: Next.js, TypeScript, OpenAI, Supabase, Tailwind CSS, Vercel

### Rift Record

Riot Games API를 활용해 League of Legends와 Teamfight Tactics 전적을 조회하고 분석하는 서비스입니다.
최근 경기 요약, 상세 참여자 분석, 챔피언 데이터, TFT 데이터 등을 분리해 보여주도록 구성했습니다.

- 배포: https://rift-record.vercel.app/
- GitHub: https://github.com/ajttk369/rift-record
- 사용 기술: JavaScript, Node.js, Riot API, Supabase, Vercel

### 학생 관리 시스템

Python Flask와 SQLite를 사용해 학생 데이터를 등록, 조회, 수정, 삭제할 수 있는 관리자 페이지입니다.
검색, 필터, 통계 카드, 수정 dialog 등 실제 관리 화면에서 필요한 흐름을 중심으로 구현했습니다.

- 배포: https://student-lms-manager.onrender.com/
- 사용 기술: Python, Flask, SQLite, HTML/CSS/JavaScript

### AI Future Expo

AI 전시 홍보를 위한 반응형 웹사이트입니다.
전시 정보, 프로그램, 홍보 콘텐츠를 한 화면에서 볼 수 있도록 구성하고 Vercel에 배포했습니다.

- 배포: https://ai-expo-sooty.vercel.app/
- 사용 기술: HTML, CSS, JavaScript, Premiere Pro, After Effects

### Shopping Mall Page

쇼핑몰 서비스를 가정해 제작한 웹 페이지입니다.
상품 목록, 브랜드, 이벤트, 검색, 마이페이지 흐름을 중심으로 화면을 구성했습니다.

- 배포: https://shopping-mall-rosy.vercel.app/
- 사용 기술: HTML, CSS, JavaScript, Python

### Automatic Cup Collector

Raspberry Pi와 Python을 활용해 컵을 인식하고 분류하는 자동 수거기 프로젝트입니다.
카메라 인식, 분류 흐름, 시연 영상과 기획 자료를 포트폴리오에 함께 정리했습니다.

### Smart Parking System

Arduino, NFC, Bluetooth를 활용한 무선 주차 시스템 프로젝트입니다.
주차 상태 확인과 사용자 인증 흐름을 중심으로 구현했습니다.

## 기술 스택

- HTML / CSS / JavaScript
- TypeScript / React / Next.js
- Python / Flask / SQLite / SQL
- Supabase / REST API / Vercel
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

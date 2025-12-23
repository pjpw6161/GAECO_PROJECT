# 🎮 GAECO : Gamified AI Eco-system
> **"게이미피케이션 기반 자기계발 플랫폼"**

![Java](https://img.shields.io/badge/Java-17-007396?style=flat&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.0-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-3.0-4FC08D?style=flat&logo=vue.js&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-Latest-DC382D?style=flat&logo=redis&logoColor=white)

## 📅 프로젝트 소개
**GAECO**는 건강 관리(식단, 운동)에 RPG 게임 요소와 실시간 메타버스를 결합하여 지속 가능한 동기를 부여하는 웹 서비스입니다.
사용자는 AI 비서의 도움을 받아 간편하게 식단을 기록하고, 길드원들과 실시간 아지트에서 소통하며 함께 성장할 수 있습니다.

* **개발 기간:** 2024.XX.XX ~ 2024.XX.XX (약 X주)
* **개발 인원:** 0명 (Back-end, Front-end, Infra)

---

## 📸 프로젝트 메인 이미지
![Main Screenshot](./assets/main_banner.png)

---

## 👨‍💻 팀원 소개

| Role | Name | Position & Responsibility | Github |
|:---:|:---:|:---|:---:|
| **Leader** | **OOO** | Backend, CI/CD | [@username](https://github.com/) |
| **Member** | **OOO** | Frontend (Vue, Phaser) | [@username](https://github.com/) |
| **Member** | **OOO** | Backend, AI Modeling | [@username](https://github.com/) |
| **Member** | **OOO** | Frontend, UI/UX | [@username](https://github.com/) |

---

## ✨ 핵심 기능 (Key Features)

### 1. 🥗 AI 기반 식단 분석 및 성장 시스템
![Diet Analysis](./assets/diet.gif)
* **AI Vision Analysis:** Java `ProcessBuilder`와 Python 스크립트를 연동하여 OpenAI Vision API 호출.
* **RAG Reward System:** 벡터 DB 데이터를 기반으로 영양 성분에 따른 경험치/골드 차등 지급.
* **Quest Automation:** `Spring Scheduler(Cron)`를 활용한 매일 자정 일일 퀘스트 초기화.

### 2. 🏠 WebSocket 기반 실시간 길드 아지트
![Guild Room](./assets/guild_room.gif)
* **Real-time Interaction:** `WebSocket(STOMP)`을 활용한 캐릭터 이동 및 채팅 동기화.
* **Phaser 3 Engine:** 웹 기반 2.5D 그래픽 렌더링 및 파티클 시스템(날씨) 구현.
* **AI Secretary:** "비서야" 호출 시 OpenAI API와 연동된 페르소나 챗봇 응답.

### 3. 🎵 인터랙티브 도구 (주크박스 & 화이트보드)
![Jukebox & Board](./assets/interactive.gif)
* **Jukebox Sync:** YouTube API 활용 및 입장 시점(Timestamp) 계산을 통한 재생 구간 동기화 (`seekTo`).
* **Live Whiteboard:** HTML5 Canvas 좌표 데이터 공유 및 마우스 이벤트 쓰로틀링(Throttling) 최적화.

### 4. 🛠️ 아지트 커스터마이징 (하우징)
![Housing](./assets/housing.gif)
* **Grid Snapping:** 32px 단위 그리드 시스템을 적용한 정교한 가구 배치.
* **Serialization:** 배치된 수백 개의 타일 객체를 JSON 직렬화하여 DB 저장 및 로드.

---

## 🏗️ 시스템 아키텍처 (System Architecture)

![Architecture](./assets/architecture_diagram.png)

* **Backend:** Spring Boot 기반의 REST API 서버 및 WebSocket 메시지 브로커 구축.
* **Frontend:** Vue 3 Composition API와 Pinia 상태 관리, Phaser 3 게임 엔진 활용.
* **AI/Data:** Python 프로세스 연동을 통한 이기종 언어 간 통신 구현.
* **Infra:** AWS EC2, Docker, Jenkins를 활용한 CI/CD 파이프라인 구축.

---

## 🛠️ 기술 스택 (Tech Stack)

### Backend
![Java](https://img.shields.io/badge/Java-17-007396?style=flat&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.2-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![JPA](https://img.shields.io/badge/Spring%20Data%20JPA-gray?style=flat&logo=spring&logoColor=white)
![Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat&logo=spring-security&logoColor=white)

### Frontend
![Vue.js](https://img.shields.io/badge/Vue.js-3.0-4FC08D?style=flat&logo=vue.js&logoColor=white)
![Phaser](https://img.shields.io/badge/Phaser-3-black?style=flat&logo=phaser&logoColor=white)
![Pinia](https://img.shields.io/badge/Pinia-F1C40F?style=flat&logo=vue.js&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat&logo=axios&logoColor=white)

### AI & Data
![Python](https://img.shields.io/badge/Python-3.9-3776AB?style=flat&logo=python&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-API-412991?style=flat&logo=openai&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-Latest-DC382D?style=flat&logo=redis&logoColor=white)

### Infrastructure & Tools
![AWS](https://img.shields.io/badge/AWS-EC2-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## 📚 프로젝트 산출물
* 📑 [요구사항 정의서](./docs/requirements.pdf)
* 🎨 [Figma 디자인](https://www.figma.com/)
* 🗄️ [ERD 설계도](./docs/erd.png)
* 📡 [API 명세서 (Notion)](https://notion.so/)

---

## 🚀 시작하기 (Getting Started)

### Backend
```bash
$git clone [https://github.com/username/project-backend.git$](https://github.com/username/project-backend.git$) cd project-backend
$./gradlew clean build$ java -jar build/libs/app.jar

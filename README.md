# 🌏 AI 기반 서울 맞춤형 여행 플랫폼

> 외국인 관광객을 위한 개인화된 AI 스마트 여행 서비스  
> 실시간 통번역, 도슨트, 메뉴 분석, K-POP 플레이리스트까지 한 번에!

---

## ✨ 프로젝트 소개
서울을 방문하는 외국인 관광객에게 개인의 **취향과 관심사에 최적화된 맞춤형 여행 경험**을 제공합니다.  
복잡한 여행 정보를 개인화하고, **AI 통번역 및 도슨트 기능**으로 언어 장벽 없는 편리한 여행을 지원합니다.

---

## 🧠 기술 스택

- **Frontend / Backend:** JavaScript, Python, Flask  
- **AI & Data:** Azure OpenAI, Azure AI Search, Azure Computer Vision, Azure Custom Vision, Azure AI Translator, YOLOv8 (Ultralytics / Torch / OpenCV)  
- **Cloud & Infra:** Azure Function, Azure Blob Storage, Azure Database for MySQL  
- **Authentication / API:** JWT Token, Spotify API  
- **Platform:** Azure AI Services  

---

## 🚀 주요 기능

### 🎯 맞춤형 여행 일정 추천
- 사용자 설문 및 데이터 기반으로 여행자별 **페르소나(여행 스타일)** 도출  
- 군집화 분석을 통해 ‘K-Food 미식가’, ‘K-Beauty 쇼퍼’, ‘역사 탐방가’ 등으로 분류  
- Azure AI Search 활용, 페르소나별 **최적의 여행 일정 추천 (Day-by-Day 일정 제안)**  

### 🗣️ AI 기반 실시간 안내 및 통번역
- **AI 도슨트:** 관광지별 심층적인 문화·역사 정보 안내  
- **실시간 챗봇:** Azure AI Search + Azure Function(HttpTrigger)을 이용한  
  24시간 **실시간 질의응답(Q&A)** 기능 (운영 시간, 교통, 위치 등)  
- **실시간 통역:** Azure AI Translator로 외국인과의 대화 및 표지판 번역 지원  

### 🍽️ 스마트 메뉴 분석 및 문화 체험
- **메뉴판 이미지 분석:**  
  Azure Computer Vision / Custom Vision + YOLOv8 모델로  
  메뉴판 인식 → 음식 설명 + 알러지 유발 성분 자동 감지  
- **K-POP 플레이리스트:**  
  Spotify API를 통해 사용자 취향 기반의 **‘나만의 K-POP Playlist’** 자동 생성  

### 🔒 보안 및 마이페이지
- **JWT 기반 로그인:** Google, Microsoft 소셜 로그인  
- **마이페이지 & 커뮤니티:**  
  Azure Database for MySQL + Azure Blob Storage 기반  
  개인화된 여행 기록 저장 및 사용자 간 정보 공유  

---

## 💡 프로젝트 기획 의도

서울은 다양한 매력을 가진 도시이지만  
**언어 장벽, 정보 과다, 개인화 부족**으로 인해 외국인 여행자에게는 여전히 어려움이 존재합니다.  

본 서비스는 **Microsoft AI School**에서 학습한 **최신 Azure AI 기술**을 활용하여  
외국인 관광객이 더 쉽게, 더 깊게, 그리고 **K-컬처를 찐하게 체험할 수 있도록** 기획되었습니다.  

---

## 🧭 서비스 흐름 요약

1. **사용자 입력 & 설문 → 페르소나 도출 (AI 분석)**  
2. **Azure AI Search 기반 추천 일정 자동 생성**  
3. **여행 중 AI 챗봇 / 도슨트 / 통역 기능으로 실시간 가이드**  
4. **식사 중 메뉴판 이미지 분석 및 알러지 정보 제공**  
5. **여행 스타일에 맞는 Spotify K-POP Playlist 제공**  

---

## 🖥️ 최종 결과물

### 📊 페르소나 기반 일정 추천 대시보드
- 개인화된 3~5일 맞춤 일정 및 추천 지도 표시  

### 💬 AI 통역 및 분석 인터페이스
- 실시간 음성/텍스트 번역
- 음식 상세 정보 및 알러지 시각화 결과 표시  

### 🧩 커뮤니티 및 사용자 관리
- JWT 인증 기반 로그인
- 안전한 커뮤니티 활동과 마이페이지 관리  

---

## 🏫 개발 계기

이 프로젝트는 **Microsoft AI School** 과정의 일환으로,  
최신 **Azure AI 인프라와 OpenAI 모델**을 실무형으로 통합한 프로젝트 입니다.



## 🛠️ 활용 기술 아키텍처 다이어그램 (예시)


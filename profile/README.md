# ☁️ 미세한차이

> AI 기반 미세먼지 예측 및 최적 활동 시간 추천 서비스

기상·환경 데이터를 활용해 미세먼지 농도를 예측하고,  
사용자의 일정과 활동 목적에 맞춰 **야외활동 및 환기에 적합한 시간대**를 추천함.

---

## ✨ Key Features

- 시계열 AI 기반 미세먼지 농도 예측
- 야외활동 및 환기 최적 시간대 추천
- 사용자 일정 기반 차선 시간대 재추천
- 기상 변수 기반 추천 사유 제공
- 사용자 조건을 고려한 호흡기 부담 지수 제공

---

## 🛠 Team & Tech Stack

| Part | Role | Tech Stack | Member |
|---|---|---|---|
| Main Server | 서비스 메인 API 서버 | Java, Spring Boot | 차예림 |
| AI Server | AI 모델 연동 API 서버 | Python, FastAPI | 안수현 |
| AI Model | 미세먼지 예측 모델 | Python | 박영혜 |
| Frontend | 모바일 애플리케이션 | Flutter | 홍순기 |

---

## 📦 Repository

- `main-server` — Spring Boot 기반 메인 서버
- `ai-server` — Python / FastAPI 기반 AI 서버
- `ai-model` — 미세먼지 예측 모델 학습 및 실험
- `frontend` — Flutter 모바일 애플리케이션

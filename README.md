<img width="600" height="830" alt="Shape" src="https://github.com/user-attachments/assets/f28ba17f-cd9c-48b7-b845-8b22d29a4f46" />
목소리의 형상 (성악, 플루트,기술이 금강이 되는 음악)
라이브 웹 프레젠테이션 (Presentation Link)
##음악과 미디어 아트 공연 제안서 바로가기([https://github.io/Shape.of.Sound](https://github.io/Shape.of.Sound)/)**

---

## Overview
* **공연명:** 목소리의 형상 (Shape of Voice)
* **장르:** 인터랙티브 미디어아트
* **핵심 컨셉:** 연주자의 소리(성악, 국악, 클래식)를 실시간 파이썬 오디오 분석 파이프라인으로 추출하여 '비·물·바람'의 시각적 요소로 형상화

---

##  주요 예술 및 기술 포인트

### 1. 서사 및 예술적 연출 (Storyline)
* **1장 (소리의 탄생):** 세 연주자의 소리가 각기 다른 온도의 빗줄기가 되어 무대에 쌓임
* **2장 (두 흐름의 대화):** 가야금 속주와 성악의 고저에 따라 빗줄기 밀도와 파동이 변화함
* **3장 (공존 - 금강):** 빗줄기가 모여 만들어진 강물이 버드나무 사이를 지나 바다로 향하는 웅장한 완성

### 2. 오디오 반응형 매핑 (Audio Feature Mapping)
| 연주 악기 | 추출 데이터 | 시각적 반응 요소 (Visual Target) |
| :--- | :--- | :--- |
| **성악 (Voice)** | Pitch (높낮이) / RMS (음량) | 빗방울 높이, 입자 크기, 물결 떨림 |
| **가야금 (Gayageum)** | Onset (타점) / RMS | 빗방울 생성 빈도, 강우량 (폭우/가랑비) |
| **플루트 (Flute)** | Breath (숨소리) / Pitch | 안개 밀도, 바람 방향, 물결 지속시간 |

---

## 💻 시스템 아키텍처 (System Architecture)
* **Audio Engine:** PyAudio / SoundDevice / Librosa / Aubio
* **Backend:** Python 3.11 / FastAPI / Uvicorn (OSC & WebSocket Protocol)
* **Visualization:** TouchDesigner / Blender (Physics Simulation)
* **Control UI:** Web Operator Panel (iPad / Tablet Interface)
* **Infra:** Ubuntu 22.04 LTS

---

## 📬 Contact
* **개발 / 파이프라인 엔지니어:** leun95@naver.com
* **연락처:** 010-2405-6340

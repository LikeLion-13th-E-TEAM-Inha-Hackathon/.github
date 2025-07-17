<p align="center">
  <img src="https://github.com/user-attachments/assets/59de1b78-172f-453f-bd62-25d8dcda18d1" width="90%"/>
</p>

# 👨‍👩‍👧‍👦 Familog - 침묵을 깨는 하루의 대화

> **가족 간 단절을 ‘질문’과 ‘화분’으로 잇는 감성형 커뮤니케이션 웹 서비스**  
> 하루 1분, 사소한 질문 하나로 **가장 가까운 사람들과 다시 연결**되는 경험을 제공합니다.

---

## ✨ 서비스 소개

우리는 매일 인터넷에서 수많은 사람과 연결되어 있지만,  
정작 가족에게는 가장 사소한 질문조차 놓치고 살아갑니다.

**“형이 가장 좋아하는 음식이 뭐더라?”**  
**“엄마는 요즘 어떤 하루를 보내고 있을까?”**

‘Familog’는 이런 작고 소중한 질문을 통해, 가족 간 단절을 메우고  
관계를 다시 이어주는 **가족 전용 질문·기록 플랫폼**입니다.

---

## 🪴 주요 기능

| 기능 | 설명 |
|------|------|
| 👨‍👩‍👧 가족 생성 및 참여 | 가족 코드를 통해 하나의 그룹 생성 및 참여 |
| 📬 오늘의 질문 | 매일 자동 생성되는 질문에 가족이 각자 답변 |
| 📦 질문 서랍 | 과거의 질문/답변을 한눈에 열람 |
| 🌿 물 주기 시스템 | 답변 시 포인트 적립 → 가족 화분 성장 |
| 👤 가족 프로필 | 가족 구성원 간 프로필 확인 및 감정 표현 |

---

## 🛠️ 기술 스택

<p align="center">
  <img src="https://github.com/user-attachments/assets/9fd8b177-804c-4820-b18b-c45398294eb5" width="90%"/>
</p>

- **Frontend**: React, Vite, TailwindCSS, Axios  
- **Backend**: Django REST Framework, JWT 인증, SQLITE
- **Deploy**: Render, Vercel
- **협업**: GitHub, Notion, Figma  

---

## 🖼️ 서비스 화면

<p align="center">
  <img src="https://github.com/user-attachments/assets/58ed2b4a-2360-4a89-a6a7-a347f7a5429d" width="90%"/>
  <img src="https://github.com/user-attachments/assets/f0b8f311-5f17-40ca-88fc-974f41901b85" width="90%"/>
  <img width="90%" alt="스크린샷 2025-07-11 오전 4 16 36" src="https://github.com/user-attachments/assets/d0ddcaa7-3279-4682-beb5-bdd593e8dab3" />
</p>

---

## 🛤️ 개발 과정 및 시행착오

| 시점 | 시행착오 / 문제 | 해결 방법 |
|------|------------------|------------|
| 오전 3:20 | 첫 로그인 시 로컬 스토리지에 사용자 정보 미저장 → API 호출 불가 | 사용자 입력 값을 state로 저장하고, 바로 로컬스토리지에 반영 |
| 오전 3:21 | UserID와 MemberID가 같으면 답변 여부 오작동 | MemberID가 아닌 Nickname으로 고유성 확인 로직 변경 |
| 오전 3:26 | 프론트에서 생성한 Family Code가 백엔드로 전달되지 않음 | 백엔드에서 생성된 코드를 응답으로 반환하고, 프론트는 이를 로컬스토리지에 저장 |
| 개발 초반 | 프론트/백 간 소통 부족 (URL/JSON 불일치 등) | Notion에 API 예시 기록, 짧은 회의 지속, 명세 일치화 |

## 💬 마무리 한마디

> “질문 하나로, 대화 둘로, 가족 셋이 다시 연결됩니다.”  
> 사소한 질문이 일상이 되고,  
> 그 대화가 가족의 연결을 회복하는 시작이 되기를 바랍니다.

<br/>
👉 서비스 링크: https://fe-gamma-bice.vercel.app/

---


<!-- 헤더 영역 -->
<div align="center">

# 👋 Hi there, I'm **Jin-Woo Jang (장진우)** 

💡 AIoT · Computer Vision · Smart Healthcare · Sign Language AI  

</div>

---

## 👨‍💻 About Me

- 🎓 서원대학교 **컴퓨터공학과** 재학 중
- 🧠 **AI + IoT(하드웨어) + 모바일 앱**을 한 시스템에 엮는 걸 좋아함
- 🍼 대표 프로젝트: **영유아 낙상 방지 스마트 침대 (AIoT Smart Infant Bed)**
- 🧏‍♂️ 사회적 약자(영유아, 독거노인, 장애인, 수어 사용자)를 돕는 **AI 서비스/시스템**에 관심 많음
- 🛠️ “아이디어 → 논문/보고서 → 프로토타입 → 실제 서비스”까지 만들어보는 걸 목표로 개발 중
- ✍️ 캡스톤, 공모전, 학회용 **논문/보고서 작성**도 함께 병행하는 타입

---

## 🛠 Tech Stack

### 🔤 Languages
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=C&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=OpenJDK&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

### ⚙️ Backend & Server
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### 📱 Mobile / Frontend
![Android Studio](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)

### 🤖 AI / CV
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)
![AlphaPose](https://img.shields.io/badge/AlphaPose-FF6F00?style=for-the-badge)
![StableDiffusion](https://img.shields.io/badge/Stable_Diffusion-000000?style=for-the-badge)

### 🧰 Tools & Others
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Anaconda](https://img.shields.io/badge/Anaconda-44A833?style=for-the-badge&logo=anaconda&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

---

## 🚀 What I’m Working On

- 🍼 **AIoT Smart Infant Bed**
  - YOLOv3 + AlphaPose 기반 **아기 자세 인식 & 낙상 위험 감지**
  - Raspberry Pi + 리니어 액추에이터로 **안전가드 자동 제어**
  - Flask / WebSocket / Android 앱 / Firebase 푸시 알림 연동
  - 실시간 영상 스트리밍 + 행동 분석 + 보호자 알림까지 한 번에

- 🧏‍♀️ **수어(수화) 인식 & 번역 시스템**
  - 스마트폰 카메라 기반 **실시간 수어 인식**
  - 2D Pose + 3D Pose + LSTM 조합으로 문장 단위 수어 해석
  - 향후 장애인 접근성 개선 서비스로 확장 예정

- 🏢 **Next-Gen ERP 재개발**
  - 노후 Java/ActiveX ERP를 **Python + FastAPI + React** 기반으로 재설계
  - 마이크로서비스, JWT 기반 인증/권한, Docker, CI/CD 설계에 관심

---

## 📂 Featured Projects

### 🍼 1. AIoT Smart Infant Bed
> 영유아 낙상을 사전에 감지하고, 자동으로 침대 가드를 올려주는 스마트 침대 시스템

- **Tech Stack**
  - Backend: Flask, FastAPI, Socket.IO, Redis  
  - AI: YOLOv3, AlphaPose, PyTorch, OpenCV  
  - Device: Raspberry Pi, WebCam, Linear Actuator, Sensors  
  - App: Android(Java/Kotlin), Firebase Cloud Messaging
- **Key Features**
  - 아기 자세(누움, 기어감, 일어남, 넘어가려는 동작 등) 실시간 분석
  - 위험 행동 감지 시, **0.8초 이내** 가드 자동 상승을 목표로 설계
  - 보호자 앱으로 실시간 알림 & 이벤트 로그 제공

---

### 🧏‍♂️ 2. Sign Language Recognition System
> 수어 사용자와 비수어 사용자를 연결하는 **수어 인식 및 자막/음성 변환 시스템**

- **Tech Stack**
  - Pose Estimation: MediaPipe / AlphaPose  
  - Model: CNN + LSTM 기반 행동 분류 모델  
  - Data: 직접 촬영한 수어 영상 + 프레임 단위 라벨링 CSV
- **Highlights**
  - 문장 단위 수어(“안녕하세요”, “감사합니다” 등)를 **시계열로 인식**
  - 오른손/왼손 핸드 크롭 데이터 자동 생성 파이프라인 구성
  - 학회 논문/프로젝트로 확장 준비 중

---

### 🏫 3. 대학 커뮤니티 & 시간표 시스템 (Java / MySQL)
> 학과 학생들을 위한 커뮤니티 + 시간표 관리 프로그램

- **Tech Stack:** Java, Swing(or Web), MySQL  
- **Features**
  - 게시판, 댓글, 공지, 강의/시간표 관리
  - 로그인, 권한(관리자/학생) 분리
  - 학과 생활에 필요한 주요 기능들을 한 곳에 통합

---

### 📚 4. C 기반 도서 대여 시스템
> 콘솔 환경에서 돌아가는 **도서 대여 관리 프로그램**

- **Tech Stack:** C  
- **Highlights**
  - 로그인 / 회원 정보 관리
  - 도서 CRUD(등록, 수정, 삭제, 검색)
  - 연체 및 페널티 관리 로직 구현
  - 방향키 조작 기반 **간편 콘솔 UI**

---

## 📊 GitHub Stats

<div align="center">

![Jin-Woo’s GitHub stats](https://github-readme-stats.vercel.app/api?username=TODO_GITHUB_ID&show_icons=true&theme=radical)  
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=TODO_GITHUB_ID&layout=compact&theme=radical)

</div>

---

## 📫 Contact

- ✉️ **Email**: `TODO_YOUR_EMAIL`  
- 🔗 **LinkedIn**: [TODO_LinkedIn_Name](https://www.linkedin.com/in/TODO_LINK/)  
- 📝 **Blog**: [TODO_Blog_URL](https://TODO_Blog_URL)  
- 🐱 **GitHub**: [https://github.com/TODO_GITHUB_ID](https://github.com/TODO_GITHUB_ID)


---

> “사회적 약자를 돕는 AI 시스템을 직접 만들고, 논문과 서비스로 연결하는 개발자”를 목표로 성장 중입니다.  
> 새로운 협업이나 프로젝트 제안은 언제든지 연락 주세요! 🙌

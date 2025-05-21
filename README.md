![배너](./assets/img-banner.png)

# 👋 Hi, I'm Lin-Bee

스마트팜 IoT 통합 시스템부터 웹 앱 대시보드까지  
**풀스택 실무형 백엔드/프론트엔드 개발자**를 지향합니다.

---


## 🧰 Tech Stack

![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/SpringBoot-6DB33F?style=flat&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat&logo=mysql&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)

---

## 🚀 주요 프로젝트

| 프로젝트 | 설명 | 링크 |
|----------|------|------|
| **스마트팜 IoT 통합 시스템** | 실시간 센서 데이터 수집 및 관리자 제어 기능 | [🔗 자세히 보기](https://github.com/Lin-Bee/2025-smartfarm-project) |
| **React Native 앱 대시보드** | 농장 구역별 센서 시각화, 토글뷰 UI | [🔗 미리보기](https://github.com/Lin-Bee/...) |

---

## 🔗 포트폴리오 링크

[![포트폴리오 바로가기](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=github&logoColor=white)](https://lin-bee.github.io)

---


## 🧩 주요 기능

### 사용자 기능 (USER)
- 🌡️ 구역별 센서 데이터 수집 (온도, 습도, 조도 등)
- 📊 센서 상태값 시각화 (이상 여부 강조 표시)
- 📂 구역별 센서 목록 토글 및 구분
- ⚙️ 제어기 설정 페이지 이동 (설정값 수정은 별도 페이지)
- 🧑‍💼 마이페이지 내 정보 수정 및 비밀번호 변경
- 📝 스마트팜 서비스 신청 기능
  - 신청자 유형, 지역, 연락처, 상담 내용 등 입력
  - 신청 후 상태는 '신청대기'로 고정 저장

### 관리자 기능 (ADMIN)
- 📥 서비스 신청 내역 목록 및 상세 보기
  - 신청자 정보, 상태, 메모 확인
  - 상태 변경(상담대기, 상담중, 상담완료 등)
- 🗂 신청 상세 수정 (상태 + 메모)
- 📈 구역별 센서 목록 및 최근 데이터 조회
- 🧭 관리자 페이지는 일반 사용자와 완전 분리

### 인증 및 보안
- 🔐 JWT 기반 로그인/인증 처리
- 🔄 로그인 상태 유지 및 토큰 만료 처리
- 🧾 권한별 메뉴 및 접근 제어
  - `fammer`만 마이팜 접근 가능
  - `admin`만 관리자페이지 접근 가능
- ☑️ 이메일 중복 확인 / 아이디 중복 확인

### UI/UX 및 기타
- 🧭 React + Redux 상태관리 구조 구성
- 🧩 routesLink 기반 자동 라우팅 및 메뉴 구성
- 📆 Dayjs 활용한 날짜 표시
- 🖼️ 스마트 대시보드형 UI 적용

---

## 🛠 기술 스택

| 구분 | 기술 |
|------|------|
| Frontend | React, React Native, Redux, TailwindCSS |
| Backend | Java 17, Spring Boot, MyBatis |
| 인증 | JWT, Redis (이메일 인증, 토큰 관리) |
| Database | PostgreSQL |
| 형상 관리 | Git, GitHub |

---

## 🧱 아키텍처 구성 특징

- `DTO → Entity → Mapper → Service` 구조 사용
  - DTO는 컨트롤러와 Mapper만 사용
  - Service는 Entity만 사용하며 Mapper를 통해 연결
- Spring Security 기반 JWT 필터 인증 구현
  - `@RequestAttribute` 방식으로 사용자 정보 주입
- 로그인 후 사용자 정보 및 권한에 따라 마이페이지 분기
- 관리자와 일반 사용자 페이지를 완전히 분리

---

### 🛍️ lazysoul  
![coming soon](https://your-image-url.com/coming-soon.png)

**기간:** 2024년 8월 8일 ~ 2025년 3월 1일  
**상태:** `WIP` `eComm`
### 🛍️ lazysoul  
![coming soon](https://your-image-url.com/coming-soon.png)

**기간:** 2024년 8월 8일 ~ 2025년 3월 1일  
**상태:** `WIP` `eComm`
![coming soon](https://your-image-url.com/coming-soon.png)

**기간:** 2024년 8월 8일 ~ 2025년 3월 1일  
**상태:** `WIP` `eComm`
![coming soon](https://your-image-url.com/coming-soon.png)

**기간:** 2024년 8월 8일 ~ 2025년 3월 1일  
**상태:** `WIP` `eComm`


---

## 📬 마무리

📧 lin_bee@naver.com  
향후에는 WebSocket을 연동한 실시간 상태 알림 기능도 구현해보고 싶습니다.


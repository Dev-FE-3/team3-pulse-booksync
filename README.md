# TEAM3 - 펄스(PULSE)💗

## 📖 스마트 독서 기록 웹앱 (24.12.23~24.12.31) 🔗 [배포 주소](https://github.com/Dev-FE-3/team3-pulse-smartreader)

- 이 서비스는 사용자가 독서 기록을 체계적으로 관리하고, 독서 습관을 분석하여 지속적으로 독서를 이어갈 수 있도록 지원하는 기능을 제공합니다. 사용자는 읽은 책을 기록하고, 독서 통계를 시각화된 차트로 확인하며, 맞춤형 책 추천을 받을 수 있습니다. 또한 친구 추가와 채팅 기능을 통해 독서 경험을 공유하고, 책에 대해 소통할 수 있는 커뮤니티를 제공합니다. 특히 독서 데이터와 책 간의 관계를 시각적으로 표현하기 위해 네트워크 그래프를 활용하여 사용자에게 심층적인 통찰을 제공합니다.

<div align="center">
<img src="https://github.com/user-attachments/assets/615329eb-9d19-417d-b81d-8343f78a4799" alt="image" width="75%" height="700">
</div>

&nbsp;

## 🔦 기능

### 회원 관리

- **회원가입 및 로그인**: 소셜 로그인 및 일반 로그인 기능을 제공합니다.
- **개인 정보 관리**: 사용자의 개인정보를 수정할 수 있는 기능을 제공합니다.

### 독서 기록 관리

- **마이 페이지**: 사용자가 기록한 책 목록, 통계 정보, 추천 도서를 확인할 수 있는 개인 페이지를 제공합니다.
- **독서 기록 입력 및 관리**: 책 제목, 저자, 장르, 읽은 날짜, 읽은 페이지 수, 독서 시간 등을 입력&관리할 수 있습니다.
- **감상평 기능**: 감상평을 남길 수 있습니다.

### 독서 통계 시각화

- **독서 시간 통계 시각화**: 사용자의 입력 독서 시간 기록을 바탕으로 일별/주별/월별 독서 습관을 확인 가능한 시각화된 그래프를 제공합니다.
- **장르별 통계**: 입력된 책의 장르 비율을 파이 차트 그래프를 제공합니다.
- **독서 성취도 그래프**:누적 독서 페이지 및 시간 데이터를 기반으로 선 그래프를 제공합니다.
- **독서 네트워크 그래프:** 입력 책 데이터를 기반으로 생성된 네트워크 그래프를 제공합니다.

### 맞춤 도서 추천

- **맞춤형 도서 추천:** 사용자의 독서 이력과 선호 장르, 자주 읽은 저자를 기반으로 도서를 추천합니다.
- **시각화 그래프 제공**: 네트워크 그래프를 통해 추천 책의 연관성을 시각적으로 제공합니다.

### 알림

- **독서 알림 설정**: 독서 목표 알림을 설정할 수 있습니다.
- **채팅 알림**: 채팅에 대한 알림을 설정할 수 있습니다.

### 공유

- **도서 공유**: 기록한 책 목록이나 추천 도서를 공유할 수 있습니다.
- **독서 기록 공유**: 독서 기록을 공유할 수 있습니다.

### 친구 추가 및 관리

- **친구 추가**: 사용자의 이메일 또는 사용자명으로 친구 추가를 할 수 있습니다.
- **친구 관리**: 친구 목록의 친구를 삭제하거나 차단할 수 있습니다.
- **친구 상태 확인**: 친구의 독서 현황(최근 읽은 책, 독서 목표 달성률)을 확인할 수 있습니다.

### 채팅

- **1:1 채팅**: 친구와 독서 관련 대화를 나눌 수 있는 채팅을 생성&관리할 수 있습니다.
- **그룹 채팅**: 다수의 사용자들과 함께 독서 주제별 토론 및 의견 교환을 할 수 있는 그룹채팅을 생성&관리할 수 있습니다.
- **채팅을 통한 공유**: 채팅을 통해 도서, 독서 기록을 공유할 수 있습니다.

&nbsp;

## 📂 프로젝트 구조

```bash
team3-pulse-smartreader
 ┣ design
 ┃ ┣ 기능정의서.md
 ┃ ┣ 요구사항정의서.md
 ┃ ┗ 프로젝트정의서.md
 ┣ .gitignore
 ┗ README.md
```

&nbsp;

## 🔧 기술스택

<div align="center">

|      Type       |                                                                                                                     Tool                                                                                                                      |
| :-------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|     Library     |                ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black) ![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=Chart.js&logoColor=white)                 |
|    Language     |                                                             ![TyoeScript](https://img.shields.io/badge/TypeScript-3178C6.svg?style=for-the-badge&logo=TypeScript&logoColor=black)                                                             |
| Package Manager |                                                                         ![Npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)                                                                          |
| Version Control |               ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)                |
|   Deployment    | ![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=Firebase&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=GitHub%20Actions&logoColor=white) |
|  Collaboration  |                     ![Zoom](https://img.shields.io/badge/Zoom-0B5CFF?style=for-the-badge&logo=zoom&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)                     |

</div>

&nbsp;

## 🔩 프로젝트 설정 및 실행 방법

### 1. 프로젝트 클론하기

먼저, Git 저장소에서 프로젝트를 로컬로 클론해야 합니다. 터미널(또는 명령 프롬프트)을 열고 아래 명령어를 입력합니다.

```bash
git clone https://github.com/Dev-FE-3/team3-pulse-smartreader.git
```

해당 명령어는 지정된 Git 저장소에서 프로젝트를 로컬 컴퓨터로 복사해옵니다.

### 2. 의존성 설치

프로젝트가 로컬에 클론된 후, 프로젝트 폴더로 이동한 다음, 필요한 패키지들을 설치해야 합니다.
Node.js 기반 프로젝트인 경우, `npm` 명령어를 사용하여 의존성을 설치할 수 있습니다.

```bash
npm install
```

이 명령어는 `package.json` 파일에 정의된 모든 의존성(dependencies)을 자동으로 설치해 줍니다.

### 3. 개발 서버 실행

모든 의존성이 설치되면, 개발 서버를 실행하여 프로젝트를 로컬에서 테스트할 수 있습니다.

```bash
npm run dev
```

이 명령어를 통해 개발 모드에서 서버를 시작하며, 변경 사항이 있을 때 자동으로 갱신됩니다.
이후, 브라우저에서 `http://localhost:5173` 주소로 접속하여 애플리케이션을 확인할 수 있습니다.

&nbsp;

## ⭐️ About Team

> 패스트캠퍼스 데브캠프 : 김민태의 프론트엔드 개발 3기 3팀

- 팀명: 펄스(PULSE)
- 팀소개: "Pulse"는 창조적인 에너지를 의미합니다. 새로운 아이디어와 영감이 끊임없이 솟아오르는 저희는 마치 맥박이 활발히 뛰고 있는 것과 같습니다. 💥
- 팀목표: 모두 취뽀까지 화이팅! 😀
<div align=center>

| [<img src="https://avatars.githubusercontent.com/u/150745130?v=4" width="150" height="200"/>](https://github.com/JaewonYooTime) | [<img src="https://avatars.githubusercontent.com/u/67031524?v=4" width="150" height="200"/>](https://github.com/gkfla668) | [<img src="https://avatars.githubusercontent.com/u/173143133?v=4" width="150" height="200"/>](https://github.com/Jang-eunhye) | [<img src="https://avatars.githubusercontent.com/u/118454010?v=4" width="150" height="200"/>](https://github.com/ijisun) |
| :-----------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------: |
|                                        **🐔 [유재원](https://github.com/JaewonYooTime)**                                        |                                      **🐤 [양정규](https://github.com/jungkyuYang)**                                      |                                        **🐤 [장은혜](https://github.com/Jang-eunhye)**                                        |                                        **🐤 [이지선](https://github.com/ijisun)**                                        |

</div>

&nbsp;

## ✉️ Conventions

### 커밋 컨벤션

- `feat`: 새로운 기능 추가
- `style`: css 수정 및 코드의 의미에 영향을 미치지 않는 변경사항
- `fix`: 버그 수정
- `refactor`: 리팩토링, 기능 변화 없이 코드 구조 개선
- `chore`: 코드 수정 외 잡다한 작업 (빌드 과정이나 설정 변경 등)
- `docs`: 문서 변경
- `perf`: 성능을 향상시키는 코드 변경
- `test`: 테스트 코드 추가 또는 수정
- `build`: 빌드 시스템 또는 외부 종속성 관련 변경
- `ci`: CI 구성 파일 및 스크립트 변경

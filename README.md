# AI 기반 식단 추천 웹서비스
<br><br>
## 📌서비스 개요
건강 목표, 알레르기, 예산 등의 정보를 기반으로 AI가 맞춤형 식단을 추천하고, 구성해주는 웹 기반 식단 설계 서비스
<br><br>
## 📌목적 및 필요성
건강한 식단은 개인의 건강 목표 달성과 질병 예방에 필수적이지만, 일반 사용자가 자신의 상황에 맞는 식단을 구성하기엔 어렵습니다.
<br>
본 서비스는 AI를 통해 사용자 맞춤형 식단을 자동 추천함으로써, 누구나 쉽고 효율적으로 건강한 식생활을 실천할 수 있도록 지원합니다.
<br><br>
## 🧠 핵심 기능
- 성별, 키, 몸무게, 건강 목표, 예산, 알레르기 등 사용자 정보 입력
- Rule – based AI알고리즘 기반의 음식 추천 기능 제공
- 추천된 음식을 아침, 점심, 저녁으로 구분하여 맞춤 식단 설계
- 영양소 시각화 및 총 칼로리, 예산 비교 요약 제공
- 예외 상황(fallback) 시에도 기본 추천 데이터를 기반으로 서비스 가능

<br><br>

## 👥 팀원 역할 분담

<table>
  <thead>
    <tr>
      <th>이름</th>
      <th>역할</th>
      <th>세부 담당 업무</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>김세일</strong></td>
      <td>팀장 / 총괄 기획·백엔드</td>
      <td>일정·문서 기획<br>API 설계<br>서버 운영</td>
    </tr>
    <tr>
      <td><strong>이동환</strong></td>
      <td>프론트엔드 개발자</td>
      <td>컴포넌트 개발<br>추천 결과 렌더링<br>차트 구현<br>React<br>상태관리<br>바인딩 처리</td>
    </tr>
    <tr>
      <td><strong>박상헌</strong></td>
      <td>테스트 / 품질·UX 개선</td>
      <td>QA 시나리오 작성<br>Postman 테스트<br>발표용 UI 개선</td>
    </tr>
  </tbody>
</table>

<br><br>


## 기술 스택
<div style="margin: 20px 0;">
  <div style="margin-bottom: 0;">
    <h3>🛠 Frontend</h3>
    <table>
      <thead>
        <tr>
          <th>역할</th>
          <th>기술 스택</th>
          <th>세부 설명</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>UI Library</td>
          <td>
            <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
          </td>
          <td>UI 구성 및 관리 라이브러리, 컴포넌트 기반 웹 애플리케이션 개발</td>
        </tr>
        <tr>
          <td>Chart Library</td>
          <td>
            <img src="https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chart.js&logoColor=white">
          </td>
          <td>데이터 시각화 및 차트 라이브러리</td>
        </tr>
        <tr>
          <td>State Management</td>
          <td>
            <img src="https://img.shields.io/badge/Zustand-FFBB00?style=for-the-badge&logo=zustand&logoColor=black">
          </td>
          <td>경량화된 상태 관리 라이브러리, React와 함께 사용</td>
        </tr>
        <tr>
          <td>HTTP Client</td>
          <td>
            <img src="https://img.shields.io/badge/axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">
          </td>
          <td>HTTP 요청을 보내는 클라이언트 라이브러리, API 호출에 사용</td>
        </tr>
        <tr>
          <td>UI Notification</td>
          <td>
            <img src="https://img.shields.io/badge/Sonner-00B9F1?style=for-the-badge&logo=sonner&logoColor=white">
          </td>
          <td>알림 UI 라이브러리, 사용자가 상호작용할 때 알림을 표시</td>
        </tr>
        <tr>
          <td>Markup Language</td>
          <td>
            <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
            <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
          </td>
          <td>웹 페이지의 구조 및 스타일링을 담당하는 언어</td>
        </tr>
        <tr>
          <td>Programming Language</td>
          <td>
            <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
            <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
          </td>
          <td>웹 애플리케이션의 기능 구현 및 데이터 흐름 처리</td>
        </tr>
        <tr>
          <td>Build Tool</td>
          <td>
            <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white">
          </td>
          <td>빠른 빌드 및 개발 서버, ES 모듈 지원, React 개발에 최적화된 빌드 도구</td>
        </tr>
      </tbody>
    </table>    
  </div>

  <br/>

  <div style="margin-bottom: 0;">
    <h3>🛠 Backend</h3>
    <table>
      <thead>
        <tr>
          <th>역할</th>
          <th>기술 스택</th>
          <th>세부 설명</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Database</td>
          <td>
            <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=PostgreSQL&logoColor=white">
            <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=SQLite&logoColor=white">
          </td>
          <td>관계형 데이터베이스 시스템, PostgreSQL은 대규모, SQLite는 경량 DB</td>
        </tr>
        <tr>
          <td>ORM Library</td>
          <td>
            <img src="https://img.shields.io/badge/SQLAlchemy-8B0000?style=for-the-badge&logo=SQLAlchemy&logoColor=white">
          </td>
          <td>Python 기반 ORM 라이브러리, 데이터베이스와의 상호작용 담당</td>
        </tr>
        <tr>
          <td>Web Framework</td>
          <td>
            <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white">
            <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white">
          </td>
          <td>Express.js는 Node.js 기반 웹 서버, Flask는 Python 기반 경량 웹 프레임워크</td>
        </tr>
        <tr>
          <td>Programming Language</td>
          <td>
            <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
            <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
          </td>
          <td>서버 사이드 로직을 작성하는 프로그래밍 언어</td>
        </tr>
        <tr>
          <td>Runtime Environment</td>
          <td>
            <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white">
          </td>
          <td>JavaScript 런타임 환경, 서버 사이드에서 JavaScript 실행</td>
        </tr>
      </tbody>
    </table>
  </div>

  <br/>
  
  <div style="margin-bottom: 0;">
    <h3>🛠 AI Server</h3>
    <table>
      <thead>
        <tr>
          <th>역할</th>
          <th>기술 스택</th>
          <th>세부 설명</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Programming Language</td>
          <td>
            <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
          </td>
          <td>AI 모델 및 서버 로직 구현을 위한 언어</td>
        </tr>
        <tr>
          <td>ORM Library</td>
          <td>
            <img src="https://img.shields.io/badge/SQLAlchemy-8B0000?style=for-the-badge&logo=SQLAlchemy&logoColor=white">
          </td>
          <td>Python 기반 ORM 라이브러리, 데이터베이스와의 상호작용 담당</td>
        </tr>
      </tbody>
    </table>    
  </div>

  <br/>

  <div style="margin-bottom: 0;">
    <h3>🛠 Tools</h3>
    <table>
      <thead>
        <tr>
          <th>역할</th>
          <th>기술 스택</th>
          <th>세부 설명</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>IDE</td>
          <td>
            <img src="https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=PyCharm&logoColor=white" alt="PyCharm">
            <img src="https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=Visual%20Studio%20Code&logoColor=white" alt="Visual Studio Code">
          </td>
          <td>Python 개발 환경(PyCharm), 다양한 언어 지원(Visual Studio Code)</td>
        </tr>
        <tr>
          <td>Version Control</td>
          <td>
            <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
            <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
          </td>
          <td>소스 코드 버전 관리 및 협업 도구</td>
        </tr>
        <tr>
          <td>Cooperation</td>
          <td>
            <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white" alt="Notion">
            <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=Discord&logoColor=white" alt="Discord">
          </td>
          <td>팀 협업 및 문서화 도구(Notion), 실시간 소통 도구(Discord)</td>
        </tr>
        <tr>
          <td>Test</td>
          <td>
            <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white" alt="Postman">
            <img src="https://img.shields.io/badge/curl-FF8C00?style=for-the-badge&logo=curl&logoColor=white">
          </td>
          <td>API 테스트 및 요청 도구</td>
        </tr>
        <tr>
          <td>UI Design</td>
          <td>
            <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white" alt="Figma">
          </td>
          <td>UI/UX 디자인 및 프로토타입 도구</td>
        </tr>
      </tbody>
    </table>    
  </div>
</div>



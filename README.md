# AI 기반 식단 추천 웹서비스

## 📌서비스 개요
건강 목표, 알레르기, 예산 등의 정보를 기반으로 AI가 맞춤형 식단을 추천하고, 구성해주는 웹 기반 식단 설계 서비스
## 📌목적 및 필요성
건강한 식단은 개인의 건강 목표 달성과 질병 예방에 필수적이지만, 일반 사용자가 자신의 상황에 맞는 식단을 구성하기엔 어렵습니다.
<br>
본 서비스는 AI를 통해 사용자 맞춤형 식단을 자동 추천함으로써, 누구나 쉽고 효율적으로 건강한 식생활을 실천할 수 있도록 지원합니다.
## 🧠 핵심 기능
- 성별, 키, 몸무게, 건강 목표, 예산, 알레르기 등 사용자 정보 입력
- Rule – based AI알고리즘 기반의 음식 추천 기능 제공
- 추천된 음식을 아침, 점심, 저녁으로 구분하여 맞춤 식단 설계
- 영양소 시각화 및 총 칼로리, 예산 비교 요약 제공
- 예외 상황(fallback) 시에도 기본 추천 데이터를 기반으로 서비스 가능
<br>
<h2>👥 팀원 역할 분담</h2>

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

<br>
<div style="margin: 20px 0;">
  <h1>기술스택</h1>
  <div style="margin-bottom: 0;">
    <h3>🛠 Frontend</h3>
    <table>
      <thead>
        <tr>
          <th>역할</th>
          <th>종류</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>library</td>
          <td>
            <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
            <img src="https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chart.js&logoColor=white">
            <img src="https://img.shields.io/badge/Recoil-0088CC?style=for-the-badge&logo=recoil&logoColor=white">
          </td>
        </tr>
        <tr>
          <td>Markup Language</td>
          <td>
            <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
            <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">
          </td>
        </tr>
        <tr>
          <td>Programming Language</td>
          <td>
            <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
          </td>
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
          <th>종류</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Database</td>
            <td>
              <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=PostgreSQL&logoColor=white">
              <img src="https://img.shields.io/badge/SQLite-87CEEB?style=for-the-badge&logo=SQLite&logoColor=white">
            </td>
        </tr>
        <tr>
          <td>ORM Library</td>
            <td>
              <img src="https://img.shields.io/badge/SQLAlchemy-8B0000?style=for-the-badge&logo=SQLAlchemy&logoColor=white">
            </td>
        </tr>
        <tr>
          <td>Framwork</td>
          <td>
            <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white">
            <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white">
          </td>
        </tr>
        <tr>
          <td>Programming Language</td>
          <td>
            <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
            <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
          </td>
        </tr>
        <tr>
          <td>Runtime Language</td>
          <td>
            <img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white">
          </td>
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
          <th>종류</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Programming Language</td>
          <td>
            <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
          </td>
        </tr>
        <tr>
          <td>ORM Library</td>
            <td>
              <img src="https://img.shields.io/badge/SQLAlchemy-8B0000?style=for-the-badge&logo=SQLAlchemy&logoColor=white">
            </td>
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
          <th>종류</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>IDE</td>
          <td>
            <img src="https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=PyCharm&logoColor=white" alt="PyCharm">
            <img src="https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=Visual%20Studio%20Code&logoColor=white" alt="Visual Studio Code">
          </td>
        </tr>
        <tr>
          <td>Version Control</td>
          <td>
            <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
            <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
          </td>
        </tr>
        <tr>
          <td>Cooperation</td>
          <td>
            <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white" alt="Notion">
            <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=Discord&logoColor=white" alt="Discord">
          </td>
        </tr>
        <tr>
          <td>Test</td>
          <td>
            <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white" alt="Postman">
          </td>
        </tr>
        <tr>
          <td>UI Design</td>
          <td>
            <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white" alt="Figma">
          </td>
        </tr>
      </tbody>
    </table>    
  </div>

# Awesome WIZ Project

<p align="center">
  <img src="src/assets/ProjectLogo.png" alt="ProjectLogo" style="width: 400px "/>
</p>
<br/>

## 프로젝트 설명
- **프로야구팀과 선수들**에 대한 **소개, 최근 소식, 경기 일정과 기록** 등을 제공하는 **웹 서비스**입니다.

<br/>

## 배포 링크
- https://wiz-front-fe.vercel.app/
- API 지원 중단으로 인해 배포중단 상태

<br/>

## 개발 기간
-  2024.09.02 ~ 2024.09.26 ( 4주 )

<br/>

## 개발 인원
-  5명 ( FE )

<br/>

## 역할 분담
- 김다은 ( 팀장 )
  - 메인페이지 하단 카드 컴포넌트 구현
  - 포수 / 내야수 / 외야수 / 코칭스텝 / 응원단 상세페이지 구현
  - 선수 상세페이지 차트 구현
  - 선수 상세페이지 선수리스트 캐러셀 구현

- 김채현
  - 메인페이지 상단 카드 컴포넌트 구현
  - WIZ 소식 / 보도자료 페이지 구현
  - 페이지 내 검색기능 기능 구현
  - 페이지 내 페이지네이션 기능 구현

- 신성우
  - 메인페이지 이미지 슬라이더 구현
  - 포수 / 내야수 / 외야수 / 코칭스텝 / 응원단 리스트페이지 구현
  - 페이지 내부 탭 메뉴바 / 페이지 내부 탭 메뉴 Navbar 구현
  - 백그라운드 이미지 컴포넌트 구현 및 모든페이지 적용

- 임희원
  - 메인페이지 최근경기일정 컴포넌트 구현
  - 정규리그 최근경기일정 컴포넌트 구현
  - 정규리그 순위기록 팀 / 투수 / 타자 / 관중현황 페이지 차트, 테이블 구현
  - 정규리그 순위기록 팀 / 투수 / 타자 / 관중현황 페이지 스켈레톤 UI 적용
  - 투수 / 타자 순위 페이지 내 검색 및 필터링 기능 구현
  - 페이지 로케이터 컴포넌트 구현 및 모든 페이지 적용

- 황유빈
  - 메인페이지 하이라이트 비디오 컴포넌트 구현
  - 정규리그 경기일정 캘린더 구현
  - 정규리그 박스스코어 페이지 테이블 구현
  - 정규리그 박스스코어 페이지 스켈레톤 UI적용
  - wiz 소개 / 연혁 페이지 구현
  - 상단 Navbar 구현 구현 및 모든 페이지 적용

<br/>

## 설치 방법

- 프로젝트를 실행을 위한 설치 방법에 대해 설명합니다.
- 아래 명령어들을 순서대로 입력하여 설치 및 실행할 수 있습니다.

<br/>

  ```
  git clone https://github.com/Awesome-Wiz/wiz-front
  ```
  ```
  npm install
  ```
  ```
  npm run dev
  ```

<br/>

## 디렉터리 구조
```
awesome-wiz
 ┣ 📂api
 ┣ 📂assets
 ┣ 📂components
 ┃ ┣ 📂game
 ┃ ┣ 📂main
 ┃ ┣ 📂media
 ┃ ┣ 📂player
 ┃ ┣ 📂rank
 ┃ ┣ 📂skeleton
 ┣ 📂layouts
 ┣ 📂pages
 ┃ ┣ 📂game
 ┃ ┣ 📂info
 ┃ ┣ 📂main
 ┃ ┣ 📂media
 ┃ ┗ 📂players
 ┃ ┣ 📜App.tsx
 ┃ ┣ 📜index.css
 ┃ ┣ 📜main.tsx
 ┃ ┗ 📜vite-end.d.ts
 ┣ 📂router
 ┣ 📂styles
 ┣ 📂types
 ┣ 📂utils
 ┣ 📜.env
 ┣ 📜.gitignore
 ┣ 📜.gitmessage.txt
 ┣ 📜eslint.config.js
 ┣ 📜index.html
 ┣ 📜package-lock.json
 ┣ 📜package.json
 ┣ 📜postcss.config.js
 ┣ 📜README.md
 ┣ 📜tailwind.config.js
 ┣ 📜tsconfig.app.json
 ┣ 📜tsconfig.json
 ┣ 📜tsconfig.node.json
 ┣ 📜vercel.json
 ┣ 📜build.sh
 ┗ 📜vite.config.ts
```
<br />

## 라이브러리

이 프로젝트에서 사용된 주요 라이브러리는 다음과 같습니다:

- ***recharts***: 차트 라이브러리
- ***react-calendar***: 캘린더 라이브러리
- ***tanstack-table***: 테이블 라이브러리
- ***tanstack-query***: 상태 관리 라이브러리
- ***swiper***: 슬라이더/캐러셀 라이브러리

<br />

## 사용 기술

- ***React***
- ***Vite***
- ***TypeScript***
- ***Tailwind CSS***
- ***TanStack Query***

<br />

## 프로젝트 팀원

<table border="1" cellspacing="0" cellpadding="10">
  <tr>
    <td align="center" style="padding: 20px;">
      <a href="https://github.com/rhrh9999">
        <img src="https://avatars.githubusercontent.com/u/112358232?v=4" height="150" width="150">
      </a>
      <br/>
      <b>김다은</b> <br/>
      <a href="https://github.com/rhrh9999">danni</a>
    </td>
    <td align="center" style="padding: 20px;">
      <a href="https://github.com/chaehyun422">
        <img src="https://avatars.githubusercontent.com/u/179909553?v=4" height="150" width="150">
      </a>
      <br/>
      <b>김채현</b> <br/>
      <a href="https://github.com/chaehyun422">chaehyun422</a>
    </td>
    <td align="center" style="padding: 20px;">
      <a href="https://github.com/Shinsungwoo21">
        <img src="https://avatars.githubusercontent.com/u/114410351?v=4" height="150" width="150">
      </a>
      <br/>
      <b>신성우</b> <br/>
      <a href="https://github.com/Shinsungwoo21">Shinsungwoo21</a>
    </td>
  </tr>
  <!-- 여백 -->
  <tr>
    <td align="center" style="padding: 20px;">
      <a href="https://github.com/gmldnjs212">
        <img src="https://avatars.githubusercontent.com/u/75336939?v=4" height="150" width="150">
      </a>
      <br/>
      <b>임희원</b> <br/>
      <a href="https://github.com/gmldnjs212">gmldnjs212</a>
    </td>
    <td align="center" style="padding: 20px;">
      <a href="https://github.com/ppinppini">
        <img src="https://avatars.githubusercontent.com/u/97329194?v=4" height="150" width="150">
      </a>
      <br/>
      <b>황유빈</b> <br/>
      <a href="https://github.com/ppinppini">ppinppini</a>
    </td>
    <td align="center" style="padding: 20px;">
      <a href="https://wiz-front-fe.vercel.app/">
        <img src="src/assets/ProjectLogo.png" alt="ProjectLogo" height="100" width="100" style="border-radius: 50px;"/>
      </a>
    </td>
  </tr>
</table>

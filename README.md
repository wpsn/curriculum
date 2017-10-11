[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

# Node.js 웹 프로그래밍 스쿨 교육과정

패스트캠퍼스 Node.js 웹 프로그래밍 스쿨 1기의 강의 자료를 공개합니다. **전체 교육과정은 아니고, 앞의 HTML, CSS, JavaScript 과정 이후의 강의를 위한 자료입니다.** 1주차, 2주차 강의는 프론트엔드 스쿨 + Node.js 웹 프로그래밍 스쿨을 대상으로, 3주차부터는 Node.js 웹 프로그래밍 스쿨만을 대상으로 강의가 진행되었습니다.

## 1주차, 2주차

1주차, 2주차 강의는 웹 브라우저와 서버 사이에서 일어나는 일들에 대한 내용을 중점적으로 다루었습니다. [프레젠테이션](https://wpsn.github.io/wpsn-handout/)의 내용을 바탕으로, 주로 [Glitch](https://glitch.com/)를 활용해서 예제 코드를 실행해본 뒤 함께 코딩을 해보는 형식으로 진행되었습니다. 다룬 내용의 얼개를 아래에 시간 순으로 나열합니다.

- 1주차
    - Node.js 소개
    - JavaScript 동시성과 비동기 프로그래밍
    - HTTP 기초
    - Glitch 사용법
    - Express
    - EJS 템플릿 엔진
    - URL Shortener 개발 실습
- 2주차
    - Express Middleware
    - HTTP Cookie
    - Session
    - Ajax, Axios
    - CORS
    - 토큰 기반 인증과 JWT
    - Fetch API
    - HTTP Cache
    - GraphQL
    - Single-page Application의 구조

아래는 프레젠테이션에 링크되어있는 모든 Glitch 프로젝트의 목록 및 거기서 다룬 내용입니다.

- <https://glitch.com/edit/#!/wpsn-glitch-tutorial>
    - Glitch 사용법
- <https://glitch.com/edit/#!/wpsn-express-prac>
    - Express 실습
- <https://glitch.com/edit/#!/wpsn-ejs-example>
    - EJS 예제
    - HTML Escape
- <https://glitch.com/edit/#!/wpsn-ejs-prac>
    - EJS 실습
- <https://glitch.com/edit/#!/wpsn-form-example>
    - UUID
    - Form Validation
    - HTTP Redirection
- <https://glitch.com/edit/#!/wpsn-middleware-example>
    - Express 미들웨어
    - `app.locals`, `res.locals`
- <https://glitch.com/edit/#!/wpsn-cookie-example>
    - 쿠키의 동작 방식
- <https://glitch.com/edit/#!/wpsn-cookie-session-example>
    - cookie-session 미들웨어
    - 서명을 통한 보안
- <https://glitch.com/edit/#!/wpsn-auth-prac>
    - 인증과 인가
    - cookie-session을 사용한 인증
- <https://glitch.com/edit/#!/wpsn-axios-example>
    - Axios 예제
    - json-server
- <https://glitch.com/edit/#!/wpsn-axios-auth-example>
    - 쿠키를 통한 Ajax 인증 예제
- <https://glitch.com/edit/#!/wpsn-cross-origin-example>
    - Cross-origin 요청에 대한 브라우저의 보안 정책
- <https://glitch.com/edit/#!/wpsn-jwt-example>
    - JWT
    - Axios instance

## 3주차

3주차에는 SQL, MySQL, Knex.js 쿼리 빌더를 다루었습니다. MySQL Workbench를 활용해서 초보자도 쉽게 SQL을 작성하고 바로 실행해볼 수 있도록 했습니다. 도서관 서비스를 위한 데이터베이스를 모델링해본 뒤 Workbench 위에서 ERD를 그려보는 실습도 진행했습니다.

- [MySQL 강의 자료](https://github.com/wpsn/wpsn-database)
- [Knex.js 강의 자료](https://github.com/wpsn/wpsn-knex)

그 밖에 다룬 주제들입니다.

- Visual Studio Code를 이용한 Node.js 디버깅
- [bcrypt](https://www.npmjs.com/package/bcrypt)를 이용한 패스워드 보안
- [validator](https://www.npmjs.com/package/validator)를 통한 사용자 입력 데이터의 검증
- [connect-flash](https://www.npmjs.com/package/connect-flash)를 이용한 피드백 메시징
- [csurf](https://www.npmjs.com/package/csurf)를 이용한 CSRF 방어 ([실습 예제](https://glitch.com/edit/#!/project/wpsn-csrf-example))

## 4주차, 5주차

4주차부터는 주로 Github에 올라가있는 예제 프로젝트를 클론받은 뒤, 같이 코딩해보는 방식으로 강의를 진행했습니다. 4주차에는 여러 Node.js 라이브러리를 활용해 간단한 서비스들을 만들어보는 실습을, 5주차에는 프론트엔드 스쿨과의 팀 프로젝트 진행을 위한 내용을 주로 다루었습니다. 각 프로젝트의 링크 및 거기서 다룬 내용입니다.

- 4주차
    - <https://glitch.com/edit/#!/wpsn-socketio-example>
        - Socket.io 예제
    - <https://github.com/wpsn/wpsn-socketio>
        - Socket.io 실습
    - <https://github.com/wpsn/wpsn-passport>
        - Passport
    - <https://github.com/wpsn/wpsn-oauth>
        - OAuth
    - <https://github.com/wpsn/wpsn-kue>
        - Redis와 Kue를 이용한 작업 큐 구현
        - aws-sdk를 이용해 AWS S3에 파일 업로드하기
        - Sharp를 이용한 이미지 처리
- 5주차
    - <https://github.com/wpsn/wpsn-rest>
        - REST 개념
        - REST API의 설계
    - <https://github.com/wpsn/wpsn-spa>
        - Single-page Application 보안과 인증
        - [예제 React 앱](https://github.com/wpsn/wpsn-todo-front)을 위한 [REST API 작성 실습](https://github.com/wpsn/wpsn-todo-back)과 [결과물](https://github.com/wpsn/wpsn-todo-back-impl)
    - <https://github.com/wpsn/wpsn-linux>
        - 리눅스 기초 명령어
        - AWS EC2, RDS, Route 53
        - PM2, Caddy
    - <https://github.com/wpsn/wpsn-testability>
        - Mocha, assert 내장 모듈, SuperTest를 활용한 REST API 테스트
        - Testability를 높이기 위한 의존성 주입과 Sinon의 활용
        - Travis CI
        - apiDoc을 이용한 REST API 문서화
    - <https://github.com/wpsn/wpsn-docker>
        - Docker
        - Docker Compose

위 강의자료에는 포함되어 있지 않지만 추가로 다룬 내용들입니다.

- PM2와 [Keymetrics](https://keymetrics.io/) 연동하기
- [AWS Cloudwatch](https://aws.amazon.com/ko/cloudwatch/)를 활용한 모니터링
- [Bugsnag과 Express 연동하기](https://docs.bugsnag.com/platforms/nodejs/express/)


프로젝트 개요
======================
이것은 뷰 스터디를 위한 도움 프로젝트입니다.

최종 프로젝트는 SFC(Single File Component) 기반의 프론트 프로젝트를 구축하게 되며, 
스터디 기간은 다음과 같이 구상하고 있습니다.

## 1. 스터디 기간 총 4주차
#### (단, 커리큘럼 진행 속도에 따라 1~2주 추가 여부 고려 필요)
	[최종 어플리케이션의 방향성]
	1. vue 파일을 컴파일해서 프론트 프로젝트가 빌드되도록 처리(SFC)
	2. 모바일과 웹에서 동작 가능한 페이지(컴포넌트 재사용이 용이한 Vue의 특징 이해)
	3. JWT를 통한 로그인 세션 처리 가능(단, Back-end 파트는 이 스터디에서 다루지 않습니다)
	4. 기본적인 CRUD가 가능한 어플리케이션
 
 
## 2. 커리큘럼(초안)
  * 1주차(09.08 일요일 / 09:00 ~ 13:00)
     - 09:00 ~ 09:50
        - 환경설정(실습)
            * Node.js / NPM 설치
            * ~Vue CLI 3 설치~ (SFC 구현 시점에 설치함)
            * Atom 설치
            * Atom 테마 및 플러그인 설치
            * Source Tree 설치
        - Vue의 이해
            * Vue의 특징 및 Vue의 장단점 설명
            * Vue와 JQuery를 사용할 때 주의할 점
     - 10:00 ~ 10:50
        - 최초의 Vue 컴포넌트 작성하기
            * Hello World 작성(실습)
        - Vue의 기본 문법 익히기
            * v-for
            * v-on
            * v-bind
            * v-if
            * v-show
     - 11:00 ~ 11:50
        - Vue의 라이프 사이클 이해하기
            * Vue 컴포넌트의 라이프 사이클 간단 설명
            * create, mounted, update, destroyed 등(실습)
            * Vue 전역 컴포넌트와 지역 컴포넌트의 이해(실습)
            * Vue 컴포넌트간의 데이터 전달 방식 이해(실습 / event 및 prop 전달 방식)
            * 이벤트 버스를 통한 데이터 전달 방식 이해(실습 / +vuex 간단 소개)
     - 12:00 ~ 12:50
        - Vue를 사용하는 세 가지 방법 설명
            * js 임포트 / CDN 방식 (사실상 동일)
            * SFC 방식 및 .vue 파일의 구조 설명(Single File Component)
            * SFC가 가지는 장점 및 차이점 소개
        - 향후 커리큘럼 진행 방향 안내
            * 왜 SFC를 써야하는가?
            * Webpack, Babel 등에 대한 간단 설명
  * 2주차(09.15 일요일 / 09:00 ~ 13:00)
     - 09:00 ~ 09:50
        - Vue 컴포넌트 레이아웃 구성하기
        - Vue 라우터 구성하기
            * Vue Router와 Nested Router (실습)
	    * 화면 레이아웃 구성해보기 (실습)
     - 10:00 ~ 10:50
        - Vuex 사용하기
            * Vuex의 특징 및 사용하는 이유
	    * Vuex를 통한 다른 컴포넌트로의 데이터 전달 (실습)
     - 11:00 ~ 11:50
        - Axios
	    * Axios 설명 및 사용법 안내
            * Axios를 통한 HTTP 통신 구현하기 (실습)
	    * Vuex 상태 변경시 Axios로 서버로부터 데이터 가져오기 (실습)
        - 토큰을 통한 인증 방식의 이해
	    * 무상태 서버와 상태 서버
	    * JWT(JSON Web Token) 설명
     - 12:00 ~ 12:50
        - JWT 토큰 심화 과정
            * JWT 토큰 방식을 통한 로그인 세션 처리 (실습)
            * JWT 토큰 사용시 주의할 점(백엔드 파트)
            * SessionStorage 및 LocalStorage 사용법
	    * API 서버 통신 및 에러 코드 처리
  * 3주차(09.22 일요일 / 09:00 ~ 13:00)
     - 09:00 ~ 09:50
        - SFC 방식으로 프로젝트 구현하기(Single File Component / Progressive Web Application)
            * Vue CLI 3로 SFC 프로젝트 초기 세팅하기 (실습)
        - Webpack, Babel 설정
            * VWebpack, Babel 개략적으로 설명
	    * Vue CLI 3를 통한 Webpack, Babel 설정
        - 추가 설정 
            * Vue Router, Axios, Vuex 등 설정하기 (실습)
            * 모듈 형태의 Vuex 설정하기 (실습)
     - 10:00 ~ 10:50
        - [간단 프로젝트] SFC 방식으로 Vue 컴포넌트 작성방법 (실습)
     - 11:00 ~ 11:50
        - [간단 프로젝트] SFC 방식으로 Vue 컴포넌트 작성방법 (실습)
     - 12:00 ~ 12:50
        - Vue 프로젝트 개발 / 프로덕션 모드 및 빌드하기 이해
	- Tomcat에 빌드한 Vue 프로젝트 배포하기
  * 4주차(09.28 일요일 / 09:00 ~ 13:00)
     - 09:00 ~ 09:50
        - [간단 프로젝트] SFC 방식으로 Vue 컴포넌트 작성방법 (실습)
     - 10:00 ~ 10:50
        - [간단 프로젝트] SFC 방식으로 Vue 컴포넌트 작성방법 (실습)
     - 11:00 ~ 11:50
        - 상용 그리드와의 연동 방법 설명(실습 / 참고용)
        - JQuery와 같이 사용할 경우 주의사항 등 안내
     - 12:00 ~ 12:50
        - 최종 샘플을 빌드 및 Tomcat에 배포하기
        - Jenkins, Gitlab 등 도움이 될만한 도구 안내
        - 모바일 및 PC에서 최종 샘플 결과화면 확인하기
        - 기타 실무적인 질의사항 받기

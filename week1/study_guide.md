1주차 스터디 가이드 문서
======================

## 1. 환경설정 및 Vue의 이해 (09:00 ~ 09:50)
### 1.1 Node.js 및 NPM 설치
```이번 스터디에서 Node.js를 직접적으로 사용하지는 않지만 NPM(Node Package Manager)의 사용을 위해 설치합니다.```
#### 1.1.1 Node 설치 여부 확인(cmd)
```C:\Users\oxide>node --version```
     
#### 1.1.2 Node 설치 파일 다운로드 
https://nodejs.org/ko/

#### 1.1.3 Node 설치 여부 재확인(cmd)
```C:\Users\oxide>node --version```

```C:\Users\oxide>npm --version```


### 1.2 Vue Cli 3 글로벌 설치

#### 1.2.1 cmd에서 글로벌 설치 명령어 수행
```npm install -g @vue/cli```
###### -g는 글로벌 설치를 의미합니다. (글로벌 설치일 때는 커맨드를 실행하는 위치 상관없음)
(참고) 글로벌 설치시 `C:\Users\%username%\AppData\Roaming\npm\node_modules` 하위로 설치됩니다. 

#### 1.2.2 글로벌 설치 여부 확인

###### cmd를 열고 아무 위치에서나 `vue ui` 명령어 입력


### 1.3 Atom 및 플러그인 설치

#### 1.3.1 Atom 설치
https://atom.io/

###### Atom은 Github에서 제공하는 오픈소스 텍스트 에디터로, 프론트 개발시 Sublime Text, VS Code 등과 함께 종종 사용되고 있습니다.

## 2. 커리큘럼(초안)
  * 1주차(09.08 일요일 / 09:00 ~ 13:00)
     - 09:00 ~ 09:50
        - 환경설정(실습)
            * Node.js / NPM 설치
            * Vue CLI 3 글로벌 설치
            * Atom 설치
            * Atom 테마 및 플러그인 설치
            * Source Tree 설치
        - Vue의 이해
            * Vue의 특징 및 Vue의 장단점 설명
            * Vue와 JQuery를 사용할 때 주의할 점
     - 10:00 ~ 10:50
        - Vue를 사용하는 세 가지 방법 설명
            * js 임포트 / CDN 방식 (사실상 동일)
            * SFC 방식 및 .vue 파일의 구조 설명(Single File Component)
            * SFC가 가지는 장점 및 차이점 소개
        - 최초의 Vue 컴포넌트 작성하기
            * Hello World 작성(실습)
        - Vue의 라이프 사이클 이해하기
            * Vue 컴포넌트의 라이프 사이클 간단 설명
            * create, mounted, update, destroyed 등(실습)
     - 11:00 ~ 11:50
        - Vue의 컴포넌트 개념 및 데이터 전달 방식 이해하기
            * Vue 전역 컴포넌트와 지역 컴포넌트의 이해(실습)
            * Vue 컴포넌트간의 데이터 전달 방식 이해(실습 / event 및 prop 전달 방식)
            * 이벤트 버스를 통한 데이터 전달 방식 이해(실습 / +vuex 간단 소개)
     - 12:00 ~ 12:50
        - Vue의 기본 문법 익히기(디렉티브)
            * v-for
            * v-on
            * v-bind
            * v-if / v-else / v-else-if
            * v-show
        - 향후 커리큘럼 진행 방향 안내
            * 왜 SFC를 써야하는가?
            * Webpack, Babel 등에 대한 간단 설명

# 뷰 템플릿 라이브러리(Vue Template Library) & 스터디

****

## 이곳은
VS Code를 이용해 Vue 공부 내용을 기록하고, 개인적으로 활용할 뷰 템플릿 라이브러리를 만들 생각입니다.

****

## Vue 개발 환경 설정
### 1. Node.js 설치
[Node.js >](https://nodejs.org/ko/)

### 2. npm 설치
```bash
$ npm install -g npm

```

### 3. Visual Studio Code 설치 및 설정
#### 3.1 Visual Studio Code 설치
[Visual Studio Code >](https://code.visualstudio.com/)

#### 3.2 확장 플러그인 설치
* open in browser : html을 브라우저로 볼 수 있도록 한다.

    ```
    ctrl + alt + B

    or

    1. 열어볼 페이지 우클릭
    2. Open In Default Browser 클릭
    3. 브라우저 선택
    ```

* HTML Snippets : 빠른 태그 작성을 돕는다.

* Vue 2 Snippets : Vue.js 2.0 문법 지원, 강조 기능 제공

* Vue-beautify : Vue.js 코드 정리

* ESLint : 자바스크립트 문법 체크. 터미널에서 설치를 추천. eslint 모드 해제는 ctrl + D

    ```bash
    $ npm install -g eslint
    $ eslint --init
    ```

* vetur : Vue.js 문법 강조, 코드 자동완성, 디버깅, Linting

### 4. 크롬 브라우저 Vue.js devtools 확장 프로그램 추가
[Vue.js devtools >](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd?hl=ko)

    1. 크롬 브라우저 > 설정 > 확장 프로그램
    2. Vue.js devtools > 세부정보
    3. 파일 URL에 대한 액세스 허용 ON

### 5. Vue-CLI 설치
기본 템플릿 설정해주는 스캐폴딩 도구

```bash
$ npm install -g vue-cli
$ vue list
```

#### 5.1 템플릿 종류(템플릿명) 
> * simple : Vue.js를 CDN 참조. 기본 테스트용
> * browserify-simple : browserify + vueify. 기본 템플릿
> * browserify : browserify + vueify. hot-reload, linting, 단위 테스트 지원. 대규모 애플리케이션에 적합
> * webpack-simple : Webpack + vue-loader. 기본 템플릿
> * webpack : Webpack + vue-loader. hot-reload, linting, 단위 테스트 지원. 대규모 애플리케이션에 적합
> * pwa : PWA(Progessive Web App) 개발 템플릿. webpack 유사. 몇 가지 라이브러리 추가 제공

#### 5.2 Vue-CLI로 프로젝트 만들기
```bash
$ vue init [템플릿명] [프로젝트명]
```
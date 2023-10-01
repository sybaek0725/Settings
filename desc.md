프론트엔드 개발환경의 이해와 실습 (2023.09.15)

# NPM

1. 프론트엔트 개발에 Node.js가 필요한 이유
   - 최신 스펙으로 개발
   - 빌드 자동화
   - 개발 환경 커스텀 마이징

2. Node.js 설치
   - [Nodejs.org](https://nodejs.org/ko)에서 운영체제 별로 설치 파일을 다운로드하면 된다.
     - Version LTS : 안정적, 신뢰도 -> Node.js로 서버 구성 시 사용 권장
     - Current Version : 최신 기능 -> 개발 환경 세팅 시 사용 권장

   - Node.js 확인
       - 터미널 창 실행하여 ```node``` 입력 시 node 터미널 도구(REPL)가 실행된다.
       - REPL(Real Eval Print Loop)는 자바스크립트 코드를 입력하고 즉시 결과를 확인할 수 있는 프로그램이다.
       - php, python 언어에서도 제공된다.
       - 종료할 경우 ```.exit``` 입력하면 다시 shell 로 빠져나올 수 있다.
       
   - 프로젝트 생성
      - 폴더 생성 및 진입
       ```shell
       $ mkdir sample
       $ cd sample
       ```
       - 프로젝트 생성
         - 프로젝트 메터 정보 입력할 수 있는 화면 제공된다.
         - 완료 시 package.json 파일 생성된 것을 확인할 수 있다.
           - package.json 파일 살펴보기
             - default ```name, version, description, main, scripts, author, license```
             - ```scripts``` 프로젝트를 자동화할 수 있게 shell 스크립트 명령어를 입력할 수 있는 곳이다. 
       ```shell
       $ npm init
       ```
     
   - 프로젝트 명령어
   

## 프로젝트 생성





## 외부 패키지를 관리하는 방법

# 웹팩(Webpack) - 기본편

# 바벨(Babel)

# 린트(Lint)

# 웹팩(Webpack) - 심화편

# 마무리


https://github.com/sybaek0725

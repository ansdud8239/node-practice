Node Practice

1. 패키지
    - 프로젝트 사용하는 Module(라이브러리)
    - 완전한 애플리케이션(babel,webpack,nodemon)

2. 의존성
    - 개발하는 프로젝트(애플리케이션,라이브러리)에서 설치하고 사용하는 패키지
    - 일반 의존성 : 개발하고 있는 프로젝트에서 사용하는 패키지로 꼭 빌드와 배포에 포함되어야 한다.
    - 개발 의존성 : 개발에 필요하거나 도움이 되는 패키지로 빌드와 배포에 포함하지 않는다.

3. 패키지 설치
    1) 전역 설치(global) : 여러 프로젝트에서 공통으로 사용하는 도구
    2) 지역 설치(local) : 특정 프로젝트 종속적인 도구나 라이브러리
    3) 패키지 설치 실습
        $ npm i ejs         [local, general dependency]
        $ npm i -D nodemon  [local, dev dependency]
        $ npm i -g gulp     [global, general dependency]
    4) 패키지 삭제
        $ npm unn ejs       [local install 삭제]
        $ npm un nodemon    [local install 삭제]
        $ npm un -g gulp    [global install 삭제]
        $ npm gulp --version
4.

5.
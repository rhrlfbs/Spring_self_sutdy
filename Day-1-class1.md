Spring IOC를 이용한 비즈니스 컴포넌트 만들기

환경
- jdk8
- tomcat 8.0.32
- h2 database 1.4.192
- spring tool suite 3.7.3

1. 개발환경 구축
- jdk 1.8 설정
- H2 데이터 베이스
- STS(Spring Tool Suite) 플러그인 설치

2. 실습 프로젝트 생성
- new > spring legacy project > project name 입력 > templates : spring MVC project > next > top-level package : "com.springbook.biz" > finish > 프로젝트 생성

- 프로젝트 설정 변경
project 우클릭 > properties > project facets > java : 1.8 
> runtimes : apache tomcat v8.0
> java build path > libraries > 톰캣 및 자바 버전 확인

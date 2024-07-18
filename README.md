# 🧑‍🎓 코멘토

### 1️⃣ 1주차 

**스프링 개발환경 구축**

- Github 계정생성
  - repository 생성
- JDK/Tomcat/mybatis/Intellij Community설치
  - DBeaver Community 24.1.2
    - mariaDB 연결
  - IntelliJ Community 2023.3.2
    - Maven - jetty 이용
      - pom.xml 파일의 properties 추가
      - pom.xml 파일의 dependency 삭제후 추가
      - pom.xml 파일에 jetty 구동을 위한 build 문 추가
      - Spring 설정을 위한 web.xml 수정
      - resources 아래 web 설정정보 작성
      - controller 아래 PingController ( healthCheck용 ping api ) 작성 후 jetty 실행
      - 실행 및 Ping Test (localhost:9080/ping 호출)
  - datasource & mybatis 연동
    - DB 연동을 위한 dependency 추가
    - DB 설정정보, mybatis 연동을 위한 mapper 경로 resources 아래 생성
    - DB 실행을 위한 DAO / Controller / Service 코드 작성
    - 설정후 구동
  


### 2️⃣ 2주차

**SW활용률 가이드 문서 작성**
  1. 업무를 위해 소통하는 문서 API 에 대해 알아보기
  2. 다양한 API 의 작성방법 조사
  3. 샘플 API 작성해 보기
     API 가이드 문서(초안) 작성.

     요청 URL, Request Parameters, Response Body 확인

     *요청 : pathVariable 방식
        
     *응답 : JSON 포맷

     *통신 : HTTP

     
- Rest API 에 대한 문서작성
  1. HTTP 통신에 관하여
  2. 브라우저에 URL을 입력후 요청하여 서버에서 응답하는 과정에 관하여
  3. Rest API 에 관하여

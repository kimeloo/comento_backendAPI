# comento_backendAPI

## 1차 과제

<ol>
<li>개발환경 셋팅
<ul>
<li>Github repository 생성
<ul><li>프로젝트 소스코드 관리 및 버전 관리를 위한 Github repository 생성 (완료)</li></ul></li>
<li>Java 개발환경 구성
<ul><li>Intellij Community, JDK11 설치 (완료)</li></ul></li>
<li>DB 클라이언트 구성
<ul><li>Dbeaver, mariaDB server 연결 (완료)</li></ul></li>
</ul>
<li>API 구성
<ul>
<li>Ping API 구성
<ul><li>Spring Framework 활용 API 구성</li></ul></li>
<li>DB 조회 API 구성
<ul><li>Java, Maven, Jetty, Mybatis를 이용하여 DB 조회 API 구성</li></ul></li></ul></ol>

---

## 3차 과제

1. 개발환경 세팅 및 DB 구성
   - Java 개발환경 구성
     - JDK : corretto-17.0.12 (aarch64)
   - Spring Boot 프로젝트 생성
     - Spring Boot 3.2.8
     - Maven Project
     - Dependencies : Lombok, Spring Web, Spring Boot DevTools
   - DB 구성
     - statistic11 Database 생성
       - requestInfo Table 생성
       - requestCode Table 생성
       - user Table 생성
     - requestInfo Table dummy data 입력
2. API 구성
   - Ping API
     - /ping
     - Spring Framework 활용
   - LoginCount API
     - /api/v1/logins/{year}/{month}
     - Mybatis, MariaDB 연동
     - statistic11 database 사용
3. API 테스트
   - Ping API
     - /ping 접속 및 출력 정상
   - LoginCount API
     - /api/v1/logins/20 접속 및 출력 정상
     - /api/v1/logins/20/04 접속 및 출력 정상
4. SQL 작성
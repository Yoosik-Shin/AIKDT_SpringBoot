# AIKDT_SpringBoot
AIKDT_SpringBoot



## MyBatis 의존성 추가
 - build.gradle에 아래 추가

implementation 'org.mybatis.spring.boot:mybatis-spring-boot-starter:3.0.3'
testImplementation 'org.mybatis.springboot:mybatis-spring-boot-starter-test:3.0.3'

```
implementation 'org.mybatis.spring.boot:mybatis-spring-boot-starter:3.0.3'
    testImplementation 'org.mybatis.spring.boot:mybatis-spring-boot-starter-test:3.0.3'
```

## 웹 개발 작업 순서 (SpringBoot ver.)
1. 기능 정의
2. ERD 설계
3. 화면 설계
4. DDL.sql & table 생성
--------------------------
5. table에 연결될 엔터티(도메인; DTO) 생성
6. Mapper.xml 파일 생성 및 SQL 작성
7. Mapper.java 인터페이스 생성 및 메소드 정의
8. Service 인터페이스 및 구현 클래스 작성
9. Controller 클래스 작성 및 요청 경로 매핑
10. View (html) 화면 작성
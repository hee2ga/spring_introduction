# Spring Introduction 🌱🚀💻

이 저장소는 제가 **스프링 입문 - 코드로 배우는 스프링 부트, 웹 MVC, DB 접근 기술** 강의를 기반으로  
Spring의 기본 개념과 동작 방식을 실습하며 정리한 코드 예제들을 담고 있습니다.  
직접 코드를 작성하고, 점진적으로 개선하며 학습한 모든 과정과 파이널 구조까지 포함되어 있습니다.

---

## 📚 사용한 자료
- 인프런 [김영한님의 스프링 입문 강의](https://www.inflearn.com/course/스프링-입문-스프링부트)
- Spring 공식 문서, 블로그, 개발자 커뮤니티 등 참고
- 단순한 메모리 DB부터 JDBC, JPA, 그리고 Spring Data JPA까지 다양한 방식으로 DB 접근 방법을 실습

---

## 📁 디렉토리 구조 예시

- `controller/` : 웹 요청을 처리하는 컨트롤러
- `domain/` : 비즈니스 도메인 객체 (예: Member)
- `repository/` : DB 접근 기술들 (Memory, JDBC, JDBC Templatem, JPA, Spring Data JPA 등)
- `service/` : 비즈니스 로직 처리
- `aop/` : 시간 측정 등 공통 관심사 처리 (AOP)
- `SpringConfig.java` : 직접 빈을 등록하여 DI를 설정하는 클래스

---

## 💡 학습 내용 요약

### 🔹 웹 계층
- 정적 콘텐츠, MVC 템플릿 엔진, API의 차이 이해
- `@Controller`, `@GetMapping`, `@ResponseBody`, `Model` 사용법

### 🔹 회원 관리 예제 구현
- 도메인 객체와 인터페이스 기반 저장소 설계
- Memory → JDBC → JdbcTemplate → JPA → Spring Data JPA 단계별 전환 실습
- `@Repository`, `@Service`, `@Transactional` 개념 학습

### 🔹 AOP
- `@Aspect`, `@Around`, `ProceedingJoinPoint`를 사용한 시간 측정 기능 구현
- 공통 관심사 분리의 중요성과 프록시 기반 AOP 이해

---

## ⚙️ 사용 기술 스택
- Java 17
- Spring Boot 3.x
- Gradle
- Thymeleaf
- H2 Database (in-memory)
- JPA / Spring Data JPA
- IntelliJ IDEA

---

## ✅ 목표
- 웹 계층부터 서비스, 리포지토리, DB까지의 흐름을 이해
- DI(의존성 주입), AOP, 트랜잭션 처리 등 스프링 핵심 개념을 몸에 익히기
- 스프링 부트를 이용해 빠르게 웹 애플리케이션을 개발할 수 있는 능력 기르기
- 이후 실전 스프링(Spring Core / JPA / MVC)으로 확장 예정

---

## 📝 진행 흐름
- [x] 프로젝트 생성 및 설정
- [x] 정적 페이지 / 템플릿 엔진 / API 작성
- [x] 회원 도메인 및 저장소 구현
- [x] JDBC / JdbcTemplate / JPA / SpringDataJPA
- [x] AOP 구현

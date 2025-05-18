# Part 03 리눅스 네트워크 관리
## Chapter 13 DB 서버와 웹 서버

### Summary
- **관계형 데이터베이스(Relational Database)** 는 데이터를 테이블 구조로 구성하며, 기본 단위는 테이블, 필드(열), 레코드(행), 키(각 레코드를 고유하게 식별할 수 있는 필드 값)로 이루어진다.
- **SQL (Structured Query Language)** 은 관계형 데이터베이스를 생성, 조회, 수정, 삭제 등의 작업에 사용하는 표준 데이터베이스 언어이다. 
- 데이터베이스를 생성·관리하는 소프트웨어를 **DBMS (Database Management System)** 라고 하며, 리눅스에서는 **MySQL** 과 이를 기반으로 한 **MariaDB** 를 주로 사용한다.
- 리눅스 환경에서는 대표적인 웹 서버인 **apache** 를 사용할 수 있다. **Apache와 PHP, MySQL(MariaDB)** 을 함께 사용하는 구성은 **APM** 스택이라고 부르며, 리눅스 기반 웹 서버 환경의 대표적인 조합이다.
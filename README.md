# 아랏동 주민센터 관리자 시스템 (ARAT ADMIN SYSTEM)

## 📌 프로젝트 개요
망우본동 주민센터 웹사이트를 기반으로,
회원 관리와 게시판 기능을 포함한 **관리자 전용 웹페이지**를 구현하여  
관리자의 업무 효율성과 **사용자 권한 제어**를 강화하는 것을 목표로 함.

## 🎯 주요 목표
- 회원 관리 기능으로 권한 구분 및 보안 강화
- 게시판 CRUD (댓글, 목록, 수정, 삭제 포함)
- DB 설계 및 연동 기반 MVC(Model2) 아키텍처 적용
- Bootstrap 기반 UI로 사용성과 유지보수성 향상

## 🛠 기술 스택
**백엔드**
- Java 11, Spring Framework 5.0.7
- Spring Security, Servlet API 3.1.0
- Oracle 11g, MyBatis 3.5.2, HikariCP

**프론트엔드**
- JSP, Bootstrap 3.x (sb-admin-2)
- jQuery, DataTables, Flot.js, Morris.js

## 📂 주요 기능
### 👤 주민(사용자)
- 회원가입 / 로그인
- 민원 게시판 글 작성, 수정, 삭제
- 공지사항 조회

### 🛡 관리자
- 회원 관리(주소, 연락처 조회)
- 공지사항 작성/수정/삭제
- 게시판 관리 및 검색/조회
- 댓글 작성

## 🖥 시스템 아키텍처
![SW 아키텍처](https://github.com/user-attachments/assets/e6d4509c-ae13-4def-96d2-c655120bf294)
![HW 아키텍처](https://github.com/user-attachments/assets/f32accca-68e5-476a-9c39-1c9a90de951d)
## 📌 ERD
![erd](https://github.com/user-attachments/assets/adb33bdc-16c9-4228-8336-ca8e99183e6d)

## 📸 화면 예시
### 로그인 화면


### 대시보드
![대시보드](docs/dashboard.png)

### 공지사항 게시판
![공지사항 게시판](docs/notice_board.png)

### 주민등록 게시판
![주민등록 게시판](docs/resident_board.png)

### 민원사항 게시판
![민원사항 게시판](docs/complaint_board.png)

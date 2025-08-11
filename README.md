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
<b>HW 아키텍처</b>
<img width="1222" height="450" alt="Image" src="https://github.com/user-attachments/assets/a76795b8-7fda-43db-bf60-b7119dffe031" />
<b>SW 아키텍처</b>
<img width="1244" height="505" alt="Image" src="https://github.com/user-attachments/assets/4b087b13-841f-4eaa-afb2-990f01547bae" />
## 📌 ERD
<img width="1290" height="577" alt="Image" src="https://github.com/user-attachments/assets/a8389c63-d573-4ca6-842f-203ce3a3ac68" />

## 📸 화면 시연 영상
### 로그인 화면
https://github.com/user-attachments/assets/4b167042-ff79-4cb5-aa22-d5d6f6ce972d

### 대시보드
https://github.com/user-attachments/assets/5c8ee4b6-9ae5-4e6b-958d-b30c6522cc61

### 공지사항 게시판
https://github.com/user-attachments/assets/d62d3b4d-d014-43ca-92de-9c2197f568a8

### 주민 게시판
https://github.com/user-attachments/assets/9ea59632-5cc7-4184-b031-4c81cbfd234e

### 민원사항 게시판
https://github.com/user-attachments/assets/54782970-6b31-44f1-9159-71cd48dc963e

### 민원댓글 
https://github.com/user-attachments/assets/23ecb0c5-3514-44f9-b8f0-baeaaf309421

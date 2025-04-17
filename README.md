# talkspace - 게시판

🛠 **기술 스택**  
- **Frontend**: React, Context API, Styled-Components,
- Backend: Spring Boot, MySQL

## 📌 주요 기능
- **회원가입**: 이메일 및 비밀번호를 통한 사용자 등록
- **글 목록/상세**: 글 목록 조회, 글 상세 페이지 보기
- **글 검색 기능**: 검색 기능과 페이징 기능 구현
- **글 등록**: 글 등록 시 이미지 파일 업로드 가능
- **좋아요 댓글 기능**: 좋아요와 댓글 등록 수정 삭제

## 🧪 실행 방법
### Backend (Spring Boot)
1. `git clone https://github.com/`
2. `cd back/hijtest`
3. `./gradlew build` (Windows는 `gradlew.bat build`)
4. `./gradlew bootRun` 으로 서버 실행 `http://localhost:8080`


### Frontend (React)
1. `cd front/talkspace`
2. `yarn install`
3. `yarn dev` 실행 후 (http://localhost:3000) 접속

## 📸 스크린샷

### 🛍️ 홈페이지
![홈페이지](./img/HomePage.png)

### 📦 게시판 목록
![게시판 목록](./img/BoardList.png)

### 🛒 게시글 상세
![게시글 상세](./img/Detail.png)

### 🔐 로그인
![로그인](./img/Login.png)

### 🧑‍💼 글 등록
![글 등록](./img/add-Board.png)


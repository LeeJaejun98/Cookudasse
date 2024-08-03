# ESTSOFT 2nd Project
---
#  Cookudasse Project 
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"> <img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white"> <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=AmazonAWS&logoColor=white"> <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">



> 다양한 음식과 그에 해당하는 조리법이 궁금한 사람들을 위한 커뮤니티 👉 [[링크]](http://ormi-donkey.com/)

![img.png](readme/mainImg.png)

## 📖Description

- 누구나 쉽게 접근할 수 있는 사이트
- 자유롭게 본인만의 레시피를 공유할 수 있는 사이트
  
최근 집밥을 해먹는 집밥러들이 많아지고, 한식의 세계화가 이루어지는 시대에 한 사이트에서 다양한 레시피를 찾아보기 힘듭니다.

각종 집밥 백선생님들이 모여 본인의 레시피를 올리고, 그 레시피에 대한 이야기를 나누며, 서로의 밥상에 다양성을 추가해 줄 수 있는 사이트가 되면 좋겠습니다. 



### 1. 💾**개발 환경**
![img.png](readme/DevelopmentEnvironment.png)

- Java JDK 21, JavaScript
- 프론트엔드 : React, HTML, tailwind
- 백엔드 : Spring Boot
- 데이터베이스 : MySQL
- ORM : JPA
- 배포환경 : AWS EC2, RDS
- 협업도구 : GitHub, Notion, ERD Cloud, Figma

### 2. 🤔**기능 정의서**

- 초안

![img.png](readme/mindmap.png)

- 완료

![img.png](readme/FeatureSpecification.png)

### 3. 🔎**개발 일정**

![img.png](readme/DevelopmentSchedule.png)

## ✨UI(화면) 설계서 

- [피그마 링크 바로가기](https://www.figma.com/design/aozGh2OXMbjzGZTOw2yqdf/Food%2FCooking-Recipe-website-design-(Community)?node-id=0-3&t=rwlxgjsQjsXHZpRp-0)

|                                                                                                                       |                                                                                                                   |
|-----------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|
| Main Page (Member)                                                                                                    | Main Page (Guest)                                                                                                 |
| <img src="https://github.com/lth01/ormi-community/assets/139758405/2eb7e023-322b-42f2-a676-60a5603d1766" width="370"> | <img src="https://github.com/lth01/ormi-community/assets/139758405/c1397cc9-51d8-46fe-8133-6467f75a85f0" width="370"> |
| Login Page                                                                                                            | SignUp Page                                                                                                       |
| <img src="https://github.com/lth01/ormi-community/assets/139758405/91d139f6-fa1e-4a8e-af42-1d3eed0fe794" width="370"> | <img src="https://github.com/lth01/ormi-community/assets/139758405/457792b5-48d8-424c-92fb-bd79caeba71e" width="370">    |
| SignUp complete Page                                                                                                  | Modify-info Page                                                                                                  |
| <img src="https://github.com/lth01/ormi-community/assets/139758405/962ca99e-8d30-4508-b3ec-edca7d906694" width="370"> | <img src="https://github.com/lth01/ormi-community/assets/139758405/2d3fb2b9-c49c-4f65-a0fd-ae020204cb01" width="370">    |
| Find Password Page                                                                                                    | Change Password Page                                                                                              |
| <img src="https://github.com/lth01/ormi-community/assets/139758405/179ce85e-6933-4474-b8a9-951149c3292c" width="370"> | <img src="https://github.com/lth01/ormi-community/assets/139758405/96eb0e20-a95c-4ce2-b990-7abd2f56e05c" width="370">    |
| Board Write Page                                                                                                      | Admin Page                                                                                                        |
| <img src="https://github.com/lth01/ormi-community/assets/139758405/18ac552c-7592-4eaf-993e-8e43cc11f01e" width="370"> | <img src="https://github.com/lth01/ormi-community/assets/139758405/4e27ac65-c996-43fe-9ecf-b38799f0f5b7" width="370">    |
## 📂Project Structure

### 🌐 Front-End
```
📁 src
├── 📁 assets
├── 📁 components
│   ├── 📁 Board
│   ├── 📁 Comment
│   ├── 📁 Document
│   ├── 📁 Icon
│   ├── 📁 Industry
│   ├── 📁 Layout
│   ├── 📁 Menu
│   ├── 📁 Password
│   └── 📁 ui
├── 📁 lib
├── 📁 routes
│   ├── 📁 Board
│   ├── 📁 Document
│   ├── 📁 Main
│   ├── 📁 Password
│   ├── 📁 Signup
│   ├── 📁 User
│   └── 📁 admin
└── 📁 utils
```
### ⚙️ Back-End
```
📁 src
├── 📁 config
│   ├── 📃 SecurityConfig.java
│   └── 📃 SwaggerConfig.java
├── 📁 controller
│   ├── 📃 AdminController.java
│   ├── 📃 BoardController.java
│   ├── 📃 CommentController.java
│   ├── 📃 CompanyController.java
│   ├── 📃 DocumentController.java
│   ├── 📃 IndustryController.java
│   ├── 📃 LikeItController.java
│   ├── 📃 MemberController.java
│   ├── 📃 PasswordQuestionController.java
│   ├── 📃 ReportController.java
│   └── 📃 ViewershipController.java
├── 📁 domain
│   ├── 📁 dto
│   └── 📁 entity
├── 📁 repository
├── 📁 security
│   ├── 📃 MemberDetailsService.java
│   ├── 📁 exception
│   ├── 📁 filter
│   └── 📁 handler
└── 📁 service
```

## 🏭System Structure
![img.png](readme/SystemStructure.png)


## 🔐ERD Structure
![img.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e8f11927-b70c-4524-9227-a3efac08e7aa/f9326d6c-03f6-4f90-b451-d07febfd9b61/Untitled.png))

## 🎈API 명세서

### 🧑‍🍳 글 목록 조회 / 댓글
| 🏷 NAME | ⚙ METHOD | 📎 URL | 📖 DESCRIPTION | ⬇️ REQUEST BODY | ⬆️ RESPONSE SUCCESS | ⬇️ Query Param|
| --- | --- | --- | --- | --- | --- | --- |
| getAllPost | GET | /api/posts | 게시판 글 목록 조회 |  |  |  |
| getAllCommentsById | GET | /api/posts/{post_id} | 게시물의 전체 댓글 불러오기 |  |  |  |
| createComment | POST | /api/posts/{post_id}/comment | 해당 게시글에 댓글 생성 |  |  |  |
| updateComment | PATCH  | /api/posts/{post_id}/comment/{id} | 해당 게시글의 해당 댓글 수정 |  |  |  |
| deleteComment | DELETE  | /api/posts/{post_id}/comment/{id} | 해당 게시글의 해당 댓글 삭제 |  |  |  |

### 🧑‍🍳 정보 조회 / 수정

| 🏷 NAME | ⚙ METHOD | 📎 URL | 📖 DESCRIPTION | ⬇️ REQUEST BODY | ⬆️ RESPONSE SUCCESS | ⬇️ Query Param |
| --- | --- | --- | --- | --- | --- | --- |
| confirmPassword | POST | /api/users/{pasword} | 비밀번호 확인 |  |  |  |
| changePassword | PUT | /api/users/{pasword} | 비밀번호 변경 |  |  |  |
| getUserInfo | GET | /api/users | 사용자 정보 조회 |  |  |  |
| getUserPost | GET | /api/posts/{user_id} | 자신의 게시글 목록 조회 |  |  |  |
| getUserComment | GET | /api/comments/{user_id} | 자신의 댓글 목록 조회 |  |  |  |
| deleteUser | DELETE | /api/users | 회원탈퇴 |  |  |  |

### 🧑‍🍳 관리자

| 🏷 NAME | ⚙ METHOD | 📎 URL | 📖 DESCRIPTION | ⬇️ REQUEST BODY | ⬆️ RESPONSE SUCCESS | ⬇️ Query Param |
| --- | --- | --- | --- | --- | --- | --- |
| getUserId | GET | /api/users/{id} | 특정 회원의 아이디 조회 |  |  |  |
| modifyAuthority | PUT | /api/auth/{auth} | 특정 회원의 권한 수정 |  |  |  |

### 🧑‍🍳 공지사항

| 🏷 NAME | ⚙ METHOD | 📎 URL | 📖 DESCRIPTION | ⬇️ REQUEST BODY | ⬆️ RESPONSE SUCCESS | ⬇️ Query Param |
| --- | --- | --- | --- | --- | --- | --- |
| createNotice | POST | /api/notice | 공지사항 쓰기 |  |  |  |
| getNotice | GET | /api/notice/{notice_id} | 공지사항 조회 |  |  |  |
| modifyNotice | PUT | /api/notice/{notice_id} | 공지사항 수정 |  |  |  |
| deleteNotice | DELETE | /api/notice/{notice_id} | 공지사항 삭제 |  |  |  |
| getAllNotice | GET | /api/notices | 공지사항 목록 |  |  |  |

### 🧑‍🍳 게시글 조회/ 작성/ 수정/ 삭제

| 🏷 NAME | ⚙ METHOD | 📎 URL | 📖 DESCRIPTION | ⬇️ REQUEST BODY | ⬆️ RESPONSE SUCCESS | ⬇️ Query Param |
| --- | --- | --- | --- | --- | --- | --- |
| getPost | GET | /api/post/{postId} | 게시글 조회 |  |  | postId: 게시글 번호 |
| writePost | POST  | /api/post | 게시글 작성 |  |  |  |
| modifyPost | POST  | /api/post/{postId} | 게시글 수정 |  |  |  |
| deletePost | DELETE  | /api/posts/{postId} | 게시글 삭제 |  |  |  |

### 🧑‍🍳 로그인 / 회원가입

| 🏷 NAME | ⚙ METHOD | 📎 URL | 📖 DESCRIPTION | ⬇️ REQUEST BODY | ⬆️ RESPONSE SUCCESS | ⬇️ Query Param |
| --- | --- | --- | --- | --- | --- | --- |
| login | POST  | /api/users/login | 사용자 로그인 | { "id": string, "password": string } |  |  |
| signup | POST  | /api/users/signup | 회원가입 |  |  |  |
| findId | GET | /api/users/find-id | 아이디 찾기 |  |  |  |
| findPassword | POST  | /api/users/find-password | 비밀번호 찾기 |  |  |  |

## 🎞시연 영상

https://github.com/lth01/ormi-community/assets/139758405/a0ee498f-a7e4-4640-a62e-661d693c177f

https://github.com/lth01/ormi-community/assets/139758405/8b932928-b806-47aa-8b2b-f31235d78359

https://github.com/lth01/ormi-community/assets/139758405/9ab64b24-33f5-48f2-9f5f-c7e4e7e796d2

https://github.com/lth01/ormi-community/assets/139758405/2dad5efc-d509-4098-9f3b-79637befee37

https://github.com/lth01/ormi-community/assets/139758405/f846baef-432b-4e98-9525-312e34f93f10

https://github.com/lth01/ormi-community/assets/139758405/b959897c-04e2-4969-bff0-3e675c7735d3


## 🛠Coding Convention

### Java Convention

[자바 컨벤션](https://github.com/lth01/ormi-community/wiki/01-Java-Coding-Convention#java-coding-convention)

### Other Convention

[기타 컨벤션](https://github.com/lth01/ormi-community/wiki/02-Other-Convention)

## 👨‍💻Participation Member
- 이태희
- 김요한
- 김경록

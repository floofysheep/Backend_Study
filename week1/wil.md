## <백엔드 스터디 1주차 WIL>

### 이번주 스터디 목표
너무 모든 것을 세세히 이해하기보다는 전체적인 흐름과 틀을 보자!!

### 오늘의 키워드
웹, 클라이언트-서버, HTTP, 프론트엔드-백엔드, API

**1. 웹** <br>
   &ensp웹에서 컴퓨터가 서로 정보를 주고 받는 일반적인 형태는 클라이언트-서버 패러다임

**2. 클라이언트-서버**
   - 클라이언트 : 데이터의 **생성/조회/수정/삭제** 요청을 전송
   - 서버 : 요청대로 동작을 수행하고 **응답**을 전송

**3. HTTP**
   - 웹에서 사용하는 프로토콜(규칙)
   - 프로토콜 : 네트워크 안에서 요청과 응답을 보내는 **규칙**

   &ensp;HTTP를 통해 요청을 보낼 땐 HTTP Method, URL이 필요
   - HTTP Method : 데이터를 다루는 방법
   - URL(Uniform Resource Location) : 다룰 데이터의 위치

   &ensp;자주 사용하는 HTTP Method
   - **GET** : 데이터를 가져온다
   - **POST** : 데이터를 게시한다
   - **PUT** : 데이터를 교체한다
   - **PATCH** : 데이터를 수정한다
   - **DELETE** : 데이터를 삭제한다

**4. 프론트엔드-백엔드**
   - 프론트엔드 : 화면에 채울 컨텐츠 데이터를백엔드에게 **요청**
   - 백엔드 : DB에서 가져온 컨텐츠 데이터를프론트에게 **응답**

**5. API**
   - API(Application Programming Interface)
   - 어플리케이션에서 원하는 기능을 수행하기 위해 어플리케이션과 소통하는 방법(창구)을 정의한 것

   **백엔드 API** 
   - 어떤 http method, url을 사용해야 하는지 정의한 것
   - 각 요청에 대해 어떤 응답을 보내는지 정의한 것
     
**6. API 명세**
   - 회원가입 : POST &ensp;  /users/signup
   - 로그인 : POST &ensp;  /users/login
   - 할 일 생성 : GET &ensp;  /todo/list
   - 할 일 목록 조회 : POST &ensp;  /todo
   - 할 일 상세 조회 : POST &ensp;  /todo/{todo_id}
   - 할 일 수정 : PATCH &ensp;  /todo/{todo_id}
   - 할 일 삭제 : DELETE &ensp;  /todo/{todo_id}
   - 할 일 체크 : POST &ensp;  /todo/{todo_id}/check
   - 할 일 체크 해제 : POST &ensp;  /todo/{todo_id}/uncheck
   - 친구 찾기 : GET &ensp;  /users/search?username={username}
   - 친구 팔로우 : POST &ensp;  /friends/{user_id}/follow
   - 친구 언팔로우 : DELETE &ensp;  /friends/{user_id}/unfollow
   - 나의 친구 리스트 조회 : GET &ensp;  /friends/{user_id}/todo
   - 특정 친구의 할 일 조회 : GET &ensp;  /friends

### 느낀점
전공 시간에 봤던 내용들이 많아서 어렵지 않게 접근할 수 있었다. 한편으로 어떻게 활용이 되는지 조금 더 쉽게 다가갈 수 있어서 의미가 있었다.

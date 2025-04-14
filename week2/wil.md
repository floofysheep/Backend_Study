## <백엔드 스터디 2주차 WIL>

### 이번주 스터디 목표
너무 모든 것을 세세히 이해하기보다는 전체적인 흐름과 틀을 보자!!

### 오늘의 키워드
  - 스프링 빈과 스프링 컨테이너의 개념
  - 스프링 빈을 컨테이너에 저장(등록)하는 방법
  - 의존성 주입 (DI) 개념과 스프링에서 의존성을 주입하는 방법

**1. 스프링 빈과 스프링 컨테이너의 개념** <br>
  **스프링 빈**
  - 어플리케이션 전역에서 사용할 공용 **객체**
  - 스프링 컨테이너라고 하는 공용 창고에 빈(객체)을 저장해두고, 필요한 빈을 컨테이너에서 받아 사용
  - 필요한 빈은 스프링 프레임워크가 자동으로 가져다 준다
  - 빈을 사용하는 주체 역시 스프링 빈이므로 서로가 서로를 필요로 하는 구조 <br>
  **스프링 컨테이너**
  - 스프링 빈이 저장되는 공간
  - 어플리케이션 컨텍스트(Application Context) 라고도 한다

**2. 스프링 빈을 컨테이너에 저장(등록)하는 방법**
   **설정 파일 작성 (수동 등록)**
   
   **컴포넌트 스캔 (자동 등록)**
   

**3. 의존성 주입 (DI) 개념과 스프링에서 의존성을 주입하는 방법**
   

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

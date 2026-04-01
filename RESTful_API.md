# RESTful API란?
* 정보를 교환하는 절차의 규약
  
# API의 구성
* CREATE
* READ(조회)
* UPDATE(수정)
* DELET


# 어떻게??
* `URL` : 데이터의 주소
* `http method` : 명령어
* `ex)` : 이 데이터 주소의 데이터들을 명령어로 이러이렇게 해줘
    * `GET` /students/1 -> `GET` : 명령어 , `students/1` : URL(데이터의 주소)
        * GET(조회) -> **students/1**의 데이터들을 **조회하겠다**
    * `POST` /students/1 -> `POSt` : 명령어 , `students/1` : URL(데이터의 주소)
        * POST(데이터 생성) -> **students/1**의 데이터들을 **새로 생성 하겠다**
    * `PUT`/students/1 -> `PUT` : 명령어 , `students/1` : URL(데이터의 주소)
        * PUT(전체 수정) -> **students/1**의 데이터들을 **수정하겠다**
    * `PATCH` /students/1 -> `PATCH` : 명령어 , `students/1` : URL(데이터의 주소)
        * PATCH(일부 수정) -> **students/1**의 데이터들을 **일부를 수정 하겠다**
    * `DELET` /students/1 -> `DELET` : 명령어 , `students/1` : URL(데이터의 주소)
        * DELET(삭제) -> **students/1**의 데이터들을 **삭제 하겠다**
* 위 예시들 처럼 **같은 데이터여**도 **다른 명령어**어들을 쓰면 각자 다른 행동을 함
   
* *주의사항* : URL의 이름은 명사로 지음
    * http 명령엉에는 **행동만** , URL에는 **자원만**
  

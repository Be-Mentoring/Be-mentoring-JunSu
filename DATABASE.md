# 데이터베이스란?
  * `정의`: 정보화 시대에 넘치는 데이터의 집합

# 데이터베이스의 종류
* `관계형 DB` -> **SQL DB**
    * 관계형 DB를 관리할때 쓰는 언어가 **SQL**임
    * 행,열로 저장하는 방식임
    * 대표적으로 My SQL,Postgre SQL,SQLite,ORACLE
* `그외 DB` -> **NOSQL DB**
    * `Key vlaue` : 파이썬의 딕셔너리 형태(Key : value)로 이루어짐 
        * 속도가 굉장히 빠름,단순함
        * 대표적으로 redis,amazon
    * `DOcument` : Key value가 조금 더 진화하여 집합의 느낌임
        * 제이슨 데이터의 형식,스키마가 변경되는것에 유연함
        * 대표적으로 mongoDB,Cloud Firestore,amazon DOcument DB
    * `Graph`: 노드 중심의 저장
        * 인스타,페이스북이 이 방식임
        * 사용자 한명 한명의 데이터를 저장함
# 백엔드와 DB의 관게
* 백엔드는 사용자가 친 정보를 DB형태로 저장함
* 프론트엔드에 요청에 백엔드가 처리하고, 데이터베이스에 있는 데이터를 주고 받아 로직(절차)을 구현함
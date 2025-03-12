[미션2] 테이블 설계하기

![image](https://github.com/user-attachments/assets/3f2d77ec-64c1-47be-90f6-a424ff5f7eec)



[미션3] REST API 설계하기

기능 | 메서드 | Endpoint
--- | --- | ---
 회원가입 | POST | /user/signup 
 로그인 | POST | /user/login
 로그아웃 | POST | /user/logout 
 수강과목 조회 | GET | /user/subject/{userId}
 수강과목 추가 | POST | /user/subject/{subId}
 수강과목 삭제 | DELETE | /user/subject/{subId}
 회원탈퇴 | DELETE | /user/{userId}

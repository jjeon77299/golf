# golf
## 강사조회
![image](https://user-images.githubusercontent.com/97486359/207213708-ce581a31-440f-4148-ad0c-07c2559d32d1.png)  
while문을 사용해 DB에 이미 저장되어있는 데이터를 차례대로 가져옵니다. 
  
![image](https://user-images.githubusercontent.com/97486359/207213991-10ae1053-3429-4d41-a3ba-552e055440fb.png)
## 수강신청

![image](https://user-images.githubusercontent.com/97486359/207215154-0db74110-a96d-4f8b-9333-df17e687cbf7.png)  
![image](https://user-images.githubusercontent.com/97486359/207215183-870bf14d-1cf2-4004-b891-05fc360a6475.png)  
요휴성 검사하는 코드입니다 오류를 방지하기위해 드롭다운을 사용하는 name에는 ex)document.data.c_name.value==none처럼 한다

![image](https://user-images.githubusercontent.com/97486359/207214355-c2f7537a-d3a6-4088-a186-8ec03b552219.png)   
![image](https://user-images.githubusercontent.com/97486359/207214712-afa0d6fe-1bb8-484e-baad-10592fe2e0e9.png)
![image](https://user-images.githubusercontent.com/97486359/207215057-d5058fad-4a7c-4e8f-bf2f-4d32583b8c02.png)  
회원명의 value값을 회원번호의 값으로 저장하고 vDisplay함수를 이용해 회원명의 value값을 가져와서 회원명의 value값을 회원번호에 저장하는 코드입니다.  
![image](https://user-images.githubusercontent.com/97486359/207214952-9f52e487-539a-4c5a-b12f-3593c63aaf5e.png)   
강의명의 value값을 강사코드로의 값으로 저장하고 calTuition함수를 이용해 강사명의 value값을 가져와서 if문을 사용해 강사명의 value값에 맞는 강사코드를 찾아 변수 수강료에 알맞은 금액을 저장하고, 만약 회원번호의 1번째 값이 2이면 50% 나눠서 수강료에 저장하는 코드입니다.

## 수강신청 저장

![image](https://user-images.githubusercontent.com/97486359/207753447-057184af-9dd0-4208-aebd-30cc1225936f.png)  
join에 있는 value값들을 가져와서 DB에 insert문을 이용해 DB에 저장하는 파일입니다.  

## 회원정보조회

![image](https://user-images.githubusercontent.com/97486359/208015129-f41e7839-ec58-4a28-9656-1263daf93eef.png)
![image](https://user-images.githubusercontent.com/97486359/208014377-cc817ad8-f9a5-49dc-9293-423f5d8a2b5f.png)  
tbl_class_202201과 tbl_member_202201테이블에 있는 회원번호와 tbl_class_202201과 tbl_teacher_202201에 강사코드를 조인해서 테이블을 만드는 쿼리문이다.  
테이블은 while문을 사용해 DB에 이미 저장되어있는 데이터를 차례대로 가져옵니다. 


## 강사매출현황

![image](https://user-images.githubusercontent.com/97486359/208015100-e677e3ec-7446-4835-8bf4-7a188283f1ba.png)  
![image](https://user-images.githubusercontent.com/97486359/208014702-1ed741c7-16c7-4e42-9ba4-3051264baa2a.png)  
tbl_class_202201과 tbl_teacher_202201에 강사코드를 조인하고 group by와 sum을 이용해 강사코드, 강의명, 강사명과 같은 것끼리 합치고 수강료는 다하는 쿼리문이다

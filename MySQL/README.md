## mysql 설치
1. `sudo apt-get update`<br>
2. `sudo apt-get install mysql-server`

## mysql 실행
1. `sudo service mysql start`
2. `sudo mysql`
---
### 데이터베이스: 정보를 실시간으로 저장하고 불러오기 위한 tool<br>
#### '데이터베이스 관리 시스템' DBMS
 -> 관계형 데이터베이스 Relational database
   '엑셀처럼 데이터를 다루는것'
   Table 형태로, Column이 정의가 되어있고,
   (table이 정의가 되어있다면) row를 한줄씩 추가하는 형태<br>
---
1. 디비 생성<br>
`CREATE DATABASE HankukUniversity;`
2. 디비 목록 보기<br>
`SHOW DATABASES;`
3. 디비 안에 접속하기<br>
`USE 데이터베이스이름`
4. 디비 안의 테이블 목록 출력하기<br>
`show tables;`
5. (DB 안) 테이블 만들기<br>
`CREATE TABLE`
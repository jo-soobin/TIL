## mysql 설치
1. `sudo apt-get update`<br>
2. `sudo apt-get install mysql-server`

## mysql 실행
1. `sudo service mysql start`
2. `sudo mysql`
---
#### 데이터베이스: 정보를 실시간으로 저장하고 불러오기 위한 tool<br>
'데이터베이스 관리 시스템' DBMS
 -> 관계형 데이터베이스 Relational database
   '엑셀처럼 데이터를 다루는것'
   Table 형태로, Column이 정의가 되어있고,
   (table이 정의가 되어있다면) row를 한줄씩 추가하는 형태
데이터베이스 = 다중의 테이블을 가질 수 있는 어떤 구조 (Excel file)
Table = Excel file의 sheet
  : 특정 column으로 정의가 되어있고
    한줄 한줄 row가 추가됨..
  : 한 줄을 '특정'하려면, 데이터에는 Key가 있어야 함
   (주민번호, 학번, 사번) Primary key
  : Column을 2개를 조합했을 때 key되는 경우가 있음
  데이터를 가져오는 어떤 질의 (Query)
  ex1: 주민번호가 200111인 사람이 사는 주소는?					
-> SELECT address FROM person where ID=200111;
-> SELECT 컬럼아이디
    FROM 테이블이름
    WHERE 조건
1. 디비 생성
CREATE DATABASE HankukUniversity;
2. 디비 목록 보기
SHOW DATABASES;
3. 디비 안에 접속하기
USE 데이터베이스이름
4. 디비 안의 테이블 목록 출력하기
show tables;
5. (db안의) 테이블 만들기
CREATE TABLE
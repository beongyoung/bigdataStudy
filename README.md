# bigdataStudy
*  Since '22.08.22 to '22.12.09

# 자격증
```
$ Keras, AWS cloud practitioner <https://mlmlml.tistory.com/6>
$ Register here <https://aws.amazon.com/ko/training/?nc2=sb_tc>
$ SQL-D : SQL 개발자용 자격증
```

# 데이터
```
* 데이터 + 가공 → 정보
$ 데이터 종류 : 텍스트 데이터, 멀티미디어 데이터(사진,음성,영상)
$ 데이터 무결성 : 데이터는 현시점에서 생성되어야 하며 신뢰할 수 있는 정확한 상태여야 한다.
```

# 데이터의 활용
```
1. 데이터 수집 <Data set> : crawling, opensource
2. 데이터 저장 <Data sort> : sorting
3. 데이터 분석 <Data analyze> : Machine Learning(keras)
4. 데이터 예측 <Data precision> : Deep Learning, Artificial Intelligence
5. 서비스 <Service> : JSP, node.js, luby, Django, java, python
```

# 빅데이터(ML, DL)
```
1. 정형 데이터 : DB의 규칙에 맞는 데이터 <의미 파악이 쉬운 데이터> ex) 문자, 숫자
2. 비정형 데이터 : 정해진 규칙없이 그 의미를 파악하기 힘든 데이터 ex) 이미지, 음성, 영상
```

# 데이터 저장 (DB : Data base)
* No SQL, SQL, Google Cloud Platform. Amazon Web Service
```
1. 무결성이 보장된 데이터를 모아두는 저장소 (Storage)
2. 데이터 무결성 : 데이터의 가치, 신뢰
3. Table(표 제목) : 데이터를 저장하는 단위
  → 분류라는 항복을 통해 분류에 맞는 데이터를 저장하기 위함
  → 데이터의 무결성 보장
4. Column(표의 열 이름) : 테이블을 구성하는 단계
  → 하나의 분류, 컬럼 별 특성에 맞는 데이터들을 저장
5. Primary Key (기본 키) : 테이블을 대표하는 컬럼의 설치, 무결성 보장
 * 후보 키 : Not null + unique
  → 조건 : Not null(값이 반드시 존재해야 한다.), unique
  → 가장 이상적인 테이블은 한 개의 칼럼에 하나의 PK가 설치
  → 검색 속도 향상
6. Foreign Key (참조(외부) 키) : 다른 테이블의 데이터를 참조
  → 테이블과 테이블 간의 관계 설정
  → 테이블 간의 무결성 보장
  → 종속적인 삭제 방지
7. DBMS (Data Base Management System) : DB 유지보수 및 사용자 요청 피드백
```

# SQL
* 열 머릿글 : 대문자로 
* 문자, 날짜 : 왼쪽 정렬 / 숫자 : 오른쪽 정렬
```
1. SQL 문은 대소문자를 구분하지 않는다.(장/단점 존재)
2. SQL 문은 하나 이상의 줄에 입력할 수 있다.
3. 키워드는 약어로 쓰거나 여러줄로 나눠 쓸 수 없다.
4. 절은 일반적으로 서로 다른 줄에 쓴다.
5. 들여쓰기를 사용하면 SQL 문을 좀 더 읽기 쉽게 작성할 수 있다.
```

# SQL_Alias
* 열 별칭 정의
```
1.1개의 column당 1개의 별칭 사용 가능하다.
2. {column_name} as {별칭} / {column_name} {}
```

# SQL_Select
* select {column_name} : List 절(명시된 Column별 data가 결과로 출력)
* from {table_name} : From 절(명시된 Column을 소유한 Table)
```
* : all
1. Selection : 모든 Column의 데이터
  ex) select * from departments;
2. Projection : 원하는(특정) Column의 데이터
  ex) select department_id from departments
3. Join : 여러개의 Table의 데이터 검색
```

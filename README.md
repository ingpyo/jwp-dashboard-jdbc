# JDBC 라이브러리 구현하기

## 1단계
 - 개발자는 SQL 쿼리 작성, 쿼리에 전달할 인자에만 집중할 수 있도록 라이브러리를 구현한다
 - SELECT 구문일 경우 조회 결과를 추출할 수 있도록 한다.
 - SQL 쿼리를 String으로 받고 쿼리에 전달할 부분은 `?`로 받아서 라이브러리에서 해석하도록 만들기
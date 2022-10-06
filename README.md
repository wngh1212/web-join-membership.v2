# web-join-membership.v2
기존의 회원 가입보다 향상된 버전의 회원 가입
개선점<br>
1. database.php의 페이지를 css적용하기
2. 데이터베이스에 null값도 데이터 상태로써 인식되어 로그인이 되는 취약점(?)을 발견하였기 때문에 이를 수정하는 작엄<br>
3. <잠재적인 취약점>데이터베이스와 연결하기위한 API코드와 쿼리문이 그대로 노출되기 때문에 SQL INJECTION에 대한 취약가능성을 확인<br>
아직은 내부ip로만 접근할 수 있기 때문에 큰문제는 아니다.<br>
4. 위의 주소를 쉽게 조작해서 원하는 페이지에 접근...(추후 수정예정)<br>
5. CSS 및 JS의 적용, 부족한 디자인적인 스타일을 충족하기위한 작업<br>
6. login.php상태에서 원하는 일부 페이지로 링크할 예정<br>
7. 데이터를 넘기거나 가져올때 복호화하기.<br>
8. 최종적으로는 퍼블리싱까지.


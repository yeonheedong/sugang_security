### 수강신청 시스템에 보안 적용
권승주/김연희/김주언/정드림
이화여자대학교 2019-2 시큐어코딩및실습프로젝트 팀 프로젝트

[1] 프로젝트 목적 : 강의 별로 장바구니에 담은 강의 순위를 노출해 수강신청에 도움을 준다. 이를 통해 학생들이 보다 더 용이하게 수강신청을 할 수 있는 환경을 만든다.

[2] 보안 적용 내용 :
a) 중요 개인정보를 암호화하여 데이터베이스에 저장 - 중요정보 평문저장
b) 즁요 개인정보 저장 시 안전한 알고리즘 사용 - 취약한 암호화 알고리즘
c) 학수번호 입력 시 입력 데이터 검증
d) 세션 아이디 검사 및 세션 만료 시간 제한
e) Prepared statement를 통한 SQL 인젝션 공격 방지

추가 정보는 pdf파일 참고

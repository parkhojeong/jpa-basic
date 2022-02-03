### H2 데이터베이스 파일 생성 방법
- http://localhost:8082 접속
- `jdbc:h2:~/test` 경로로 JDBC URL에 입력하여 접속 (최소 한번, 세션키 유지한 상태로 실행)
- `~/test.mv.db` 파일 생성 확인
- 이후 부터는 `jdbc:h2:tcp://localhost/~/test` 경로를 JDBC URL에 입력해 접속
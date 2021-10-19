##### GET, POST, PUT, PATCH, DELETE

- GET 조회 시, 쿼리 스트링 뿐만 아니라 바디에도 데이터를 담아 전송이 가능은 하지만 지원되지 않는 서버가 많기에 권장하지 않음.


- Content-Type:**application/x-www-form-urlencoded**
    - form 내용을 바디 통해서 전송(쿼리스트링)
    - 전송 데이터를 url encoding 처리


- Content-Type:**multipart/form-data**
    - 파일 업로드같은 바이너리 데이터 전송 시 사용
    - 다른 종류의 여러가지 파일과 폼 내용 함께 전송이 가능


##### GET, POST, PUT, PATCH, DELETE

- GET 조회 시, 쿼리 스트링 뿐만 아니라 바디에도 데이터를 담아 전송이 가능은 하지만 지원되지 않는 서버가 많기에 권장하지 않음.


- Content-Type:**application/x-www-form-urlencoded**
    - form 내용을 바디 통해서 전송(쿼리스트링)
    - 전송 데이터를 url encoding 처리


- Content-Type:**multipart/form-data**
    - 파일 업로드같은 바이너리 데이터 전송 시 사용
    - 다른 종류의 여러가지 파일과 폼 내용 함께 전송이 가능


- 파일 등록, 수정 시에는 PUT 기반 등록

### HTML FORM

HTML FORM은 GET, POST만 지원

- ### 컨트롤 URI
  - GET, POST만 지원하므로 제약이 있음
  - 이런 제약을 해결하기 위해 동사로 된 리소스 경로 사용
  - POST의 /reg, /mod, /del 컨트롤 URI
  - HTTP 메서드로 해결하기 애매한 경우에 사용(HTTP API 포함)
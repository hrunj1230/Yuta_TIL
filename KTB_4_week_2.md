1.HTTP 내용 정리 
* HTTP 항목 전체
* JSON
* REST API
2.FastAPI로 커뮤니티 서비스의 백엔드를 구현해보세요 
1. HTTP REST API 설계 및 구현 
2. AI 모델 서빙 
3. 데이터베이스 적용하기 
4. 구조 개선하기(예: Route - Controller - Model 패턴을 적용) 
5. (선택) HTML/CSS/S나 스트림릿으로 프론트엔드 만들기


http
hyper ~을 뛰어넘는
text 글,문서
transfer 전송
protocol 규약
글을 뛰어넘는 글,문서를 전송하는 규약
고유명사
html,css,js, png, jpeg 과 같은 파일이나 텍스트 등 일반적인 텍스트를 뛰어넘는 구조화된 텍스트를 전송하기 위해 사용되는 규약
사용이유
웹 서버와 클라이언트가 하이퍼텍스트 문서를 주고받을 수 있도록 정의된 규칙에 따라 문서를 전송하기 위해서
사용방법
클라이언트가 url을 통해 특정 웹 주소로 요청을 보냄
http message
고유명사
클라이언트와 서버간에 파일을 주고받는 통신의 기본 단위
사용이유 -클라이언트와 서버간의 데이터를 교환하기 위해서
사용방법 -http 요청 또는 요청에 대한 응답을 하게되면 자연스럽게 사용

http
html,css,js, png, jpeg 과 같은 파일이나 텍스트 등 일반적인 텍스트를 뛰어넘는 구조화된 텍스트를 전송하기 위해 사용되는 규약
http message
클라이언트와 서버간에 파일을 주고받는 통신의 기본 단위
http request method
웹 서버에서 어떤 작업을 수행하길 원하는지 알리는 방법을 정의하는 명령 규칙
-GET : 서버로부터 데이터 조회를 요청할 때 사용하는 메소드
-POST : 서버로 데이터를 전송하여 리소스를 생성하거나 업데이트 할때 사용하는 메소드
-PUT : 서버로 데이터를 전송하여 리소스를 전체 업데이트할 때 사용하는 메소드
-PATCH : 서버의 리소스를 부분적으로 수정 또는 업데이트 할떄 사용하는 메소드
-DELETE : 서버로부터 리소스를 삭제할 떄 사용하는 메소드

http status code
일반 문서를 뛰어넘는 구조화된 텍스트를 전송하기 위해 사용되는 통신규약의 진행상태를 표시하는 코드
1xx : 정보 메시지 (informational)
2xx : 성공 (successful)
3xx : 리다이렉션 (재요청) (redirection)
4xx : 클라이언트 오류 (client error)
5xx : 서버오류 (server error)

200 : 요청 성공
201 : 요청 성공 ,새로운 리소스 생성
202 : 요청 성공, 그에 대한 처리를 할 수 없음
204 : 헤더는 유효하나, 요청에 대해 보내줄 수 있는 내용이 없음
400 : 잘못된 문법으로 서버가 요청을 이해하지 못함
401 : 인증되지 않은 접근 (로그인 없이 회원이 볼수있는 페이지 접근 )
403 : 인가되지 않은 접근 ( 관리자 페이지 권한 없이 접근)
404 : 요청받은 리소스를 찾을 수 없음 
429 : 지정된 시간안에 너무 많은 요청
500 : 서버가 처리방법을 알수 없음
501 : 요청 방법이 서버에서 지원하지않아 처리불가
503: 서버가 요청을 처리할 준비가 되지않음

url
uniform resource locator : 리소스의 위치와 종류를 나타내는 주소

http://www.example.kr:80/path/to/example.html?key1=value1&key2=value2
http - (scheme : 스키마) 브라우저가 리소스를 요청할 떄 사용해야 하는 프로토콜 (https - http에서 보안이 적용된 버전)
www.example.kr - Domain 요청하는 웹 서버
80 - port 웹서버의 리소스에 접근하는데 사용되는 게이트
/path/to/example.html - (path to resource) 웹서버에 있는 리소스의 경로 (path variable)
?key1=value1&key2=value2 - 매개변수 parameters 웹서버에 제공하는 추가 매개 변수 (query string)
   
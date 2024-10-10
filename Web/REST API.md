### REST API
---
`REpresentational State Transfer`

- 자원을 이름으로 구분해 해당 자원의 상태를 전송하여 주고 받는 것
- Web 기술 + HTTP 프로토콜을 활용한 아키텍쳐 스타일 방식

<br>

#### 'RESTful하다'의 의미
: REST API를 제공하는 웹 서비스
설계 규칙에 맞게 통용되는 일관된 컨벤션을 유지하며 API의 이해도를 높여주는 것이 중요

<br>

#### REST API 특징
- 무상태성(stateless) : 서버는 각 요청에 대해 클라이언트의 상태를 저장하지 않음 -> 구현 단순, 각 요청은 독립적으로 처리됨
- 클라이언트-서버 구조 : 클라이언트는 사용자 인터페이스를 담당(자원 요청), 서버는 리소스를 관리(자원 존재). 클라이언트와 서버의 의존성 감소
- 캐시 가능성(Cacheable) : HTTP의 캐싱 기능 활용 가능 -> 응답 시간, 성능 빨라짐
- 계층형 구조 : 시스템은 여러 계층으로 구성될 수 있으며, 중간 서버가 로드 밸런싱, 캐싱 등을 처리할 수 있습니다.
- Uniform Interface : 특정 언어에 종속되지 않고 HTTP 프로토콜을 따르면 모든 플랫폼에 적용 가능

<br>

#### REST API 설계

설계 규칙
- '/'는 계층 관계를 나타냄
- URL 마지막 문자에는 '/' 포함 X
- URL 길어지면 '-'으로 가독성 높임
- URL 경로는 소문자 사용
- '_' 사용 X
- 파일 확장자는 URL에 포함 X, Accept Header 활용

<br>

HTTP 메소드 종류
- GET(조회)
- POST(생성)
- PUT(수정)
- DELETE(삭제) 등

<br>

참조 자료
https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2Fgyoogle%2Ftech-interview-for-developer%2Frefs%2Fheads%2Fmaster%2FWeb%2FREST%2520API.pptx&wdOrigin=BROWSELINK

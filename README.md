# lab4

1. 자신의 github 저장소에 lab4 프로젝트를 생성하고 아래의 모든 과제 프로그램을 업로드한다.
2. 스레드 관련 함수들을 사용하여 프로그램을 작성하고 실행하고, 익숙해지도록 사용해 본다.
3. 스레드를 사용하여 생산자, 소비자 문제를 해결하는 제한 버퍼(Bounded Buffer)를 생성하고 활용하는 프로그램을 구현하시오. 단, 생산자 소비자 스레드는 각각 둘 이상 가능해야 한다.
4. 클라이언트(자식) 스레드들로부터 메시지 전송 요청을 받으면 서버(부모) 스레드는 모든 클라리언트 스레드에게 메시지를 방송하는 프로그램을 구현하시오. (힌트 : 소켓은 사용하지 말고 데이터 전송을 위한 동기화를 위해 뮤텍스롸 조건 변수를 사용한다.)
5. 소켓을 이용하여 프로그램을 작성하고 실행하여 보고, 익숙해지도록 한다.
6. 멀티프로세스/스레드, select 또는 epoll을 사용하여 다중 클라이언트를 처리하는 채팅 프로그램을 구현하시오
7. TCP 소켓을 이용하여 HTTP GET 및 POST 메소드 및 CGI 프로그램 실행을 구현하는 간단한 웹서버를 구현하시오. (힌트: POST 메소드의 형식은 다음 링크를 참고하세요. http://developer.mozilla.org/ko/docs/Web/HTTP/Methods/POST)
8. GUI 관련 함수들을 사용하여 프로그램을 작성하고 실행하고, 익숙해지도록 사용해 본다.
9. GTK+ 또는 Qt를 이용하여 간단한 계산기 프로그램을 작성하여 본다.
10. 채팅과 파일전송이 가능한 GUI 메신저 프로그램을 구현하시오(팀프로젝트)
    A. 채팅방 구성과 사용자 등록 기능을 가진 소켓 서버를 구현한다.
    B. 위 5번에서 구현한 소켓 채팅 프로그램을 활용하여 채팅 기능을 구현한다.
    C. GTK+ 또는 Qt를 이용하여 간단한 채팅 프로그램을 위한 GUI 클라이언트 프로그램을 작성하고 구현한 채팅 프로그램에 적용하여 본다.
    D. 파일 전송 기능을 구현한다. FTP 프로토콜 등을 참고하는 것도 좋다.

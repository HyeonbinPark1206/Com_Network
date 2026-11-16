# 컴퓨터네트워크 (Computer Networks)

동아대학교 컴퓨터공학과 · 3학년 수업 과제 · C · Ubuntu

TCP/UDP 소켓 프로그래밍과 신뢰성 있는 전송, 혼잡 제어 알고리즘을 C로 구현했습니다.

## 과제 목록

| 과제 | 주제 | 내용 |
|---|---|---|
| HW1 | TCP | ① 서버-클라이언트 에코: 접속한 클라이언트의 IP·포트 표시, 주고받은 메시지와 바이트 수 출력<br>② 달력 서버: 클라이언트가 보낸 {년도. 월.}에 맞는 달력을 전송 |
| HW2 | UDP | ① HW1-①과 같은 기능을 UDP로 구현<br>② 파일 전송: 클라이언트가 `request ~.txt`를 보내면 서버의 텍스트 파일 내용을 전송 |
| HW3 | 채팅 | 서버와 클라이언트가 메시지를 주고받는 채팅을 TCP와 UDP로 각각 구현 |
| HW4 | 재전송 | Go-Back-N, Selective Repeat |
| HW5 | 빠른 재전송 | TCP Fast Retransmission |
| HW6 | 패킷 손실 | 버퍼 오버플로로 패킷이 손실되는 상황에서의 통신 |
| HW7 | 혼잡 제어 | Congestion Control을 고려한 TCP 통신 |

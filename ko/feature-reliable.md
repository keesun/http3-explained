<!--
## ‎Reliable data transfers

While UDP is not a reliable transport, QUIC adds a layer on top of UDP that
introduces reliability. It offers re-transmissions of packets, congestion
control, pacing and the other features otherwise present in TCP.

Data sent over QUIC from one end-point will appear in the other end sooner or
later, as long as the connection is maintained.
-->

## 신뢰할 수 있는 데이터 전송

UDP가 신뢰할 수 있는 전송이 아니지만 QUIC는 UDP 위에 계층을 추가해서 신뢰성을 추가했다.
QUIC은 패킷 재전송, 혼잡 제어, 속도 조정 및 TCP가 제공하는 그 외 기능을 제공한다.

한 엔드포인트에서 QUIC으로 데이터를 보내면 연결이 유지되는 한 언젠가는 다른 쪽 끝에
그 데이터가 나타날 것이다.

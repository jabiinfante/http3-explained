<!--
## Secure

QUIC is always secure. There is no clear-text version of the protocol so to
negotiate a QUIC connection means doing cryptography and security with TLS
1.3. As mentioned above, this prevents ossification as well as other sorts of
blocks and special treatments, as well as making sure QUIC has all the secure
properties of HTTPS that web users have come to expect and want.

There are only a few initial handshake packets that are sent in the clear
before the encryption protocols have been negotiated.
-->

## 안전

QUIC은 항상 안전하다. 이 프로토콜에는 일반 텍스트 버전이 없으므로 QUIC 연결과 협상하려면
TLS 1.3을 사용해서 암호화 및 보안을 수행해야 한다. 위에서 언급했다시피, 이는 다른 차단이나
특별한 처리 같은 경화 문제를 방지할 뿐만 아니라 QUIC이 웹 사용자가 기대하고 원하는
HTTPS의 모든 보안 속성을 가지게 만든다.

암호화 프로토콜 협상이 이뤄지기 전 초기 핸드쉐이크 패킷에 일반 텍스트 메시지가 아주 조금 있다.

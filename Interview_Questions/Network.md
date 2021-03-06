## 네트워크 예상 인터뷰 질문 정리

### 1/14 (Network 원리 Chapter.01)

1. LAN 과 WAN의 차이점은 무엇이고 각 종류의 네트워크가 어떻게 사용되는지 예시와 함께 설명하세요
2. TCP / IP 의 네가지 계층은 무엇이있나요? 계층화된 프로토콜을 사용하는것의 장점은 무엇인가요?
3. 서버관리측면에서 클라우드 서비스의 장단점은?
4. 클라우드 서비스를 활용하는 IaaS, Paas, Saas의 차이점은?
5. 네트워크의 주기능은? 네트워크를 사용하는 주된 목적은 무엇인가?

---

1. 직접 서버를 운용/관리하는 방법을 무엇이라고 부르고, 단점은 무엇인가?

   > 온프레미스 (On-Premise)
   >
   > 필요에 따라 바로바로 확장, 관리가 어렵고, 보안 관리가 어렵다.
   >
   > 서버 운용 ,관리 하는데 시간과 비용이 많이 든다.

2. 이것을 해결하기 위한 방법은 클라우드 서비스가 있다. 이것의 장점과 단점은?

   > **장점:** 확장성 - 필요에 따라 서버 저장 용량을 더 구매할 수 있기 때문에 빠른 확장에 용이하다
   >
   > **단점:** 보안이나 가용성에 주의가 필요  

3. TCP/IP 네 가지 계층 중 애플리케이션 층과 인터넷층의 예시 한가지 씩?

   > 애플리케이션 층: HTTP (제일 대표적), SMTP, POP3, IMAP4, DHCP, DNS등
   >
   > 인터넷 층: IP, ICMP, ARP

4. 서버를 거치지 않고 클라이언트끼리 직접 데이터를 주고 받는 애플리케이션은? 

   > 피어 투 피어 (Peer to Peer Application): Client Server Application과는 반대로 서버가 없이 클라이언트 애플리케이션들끼리 직접 데이터를 송수신 할 수 있다.

5. 프로토콜의 정의를 간단하게 설명하세요.

   > 통신에 필요한 규칙을 정의해 놓은 것 - 프로토콜의 집합이 네트워크 아키텍쳐라고 불린다.

---

1. 사설 네트워크와 인터넷의 차이는 무엇인가요?

   -> **사용자 한정의 유/무의 차이가 있다. 인터넷은 사용자를 제한하지 않고 누구나 데이터를 주고 받을 수 있다.**
  
2. 애플리케이션을 데이터 주고받는 주체에 따라 두가지로 나눠서 설명하면?

   -> **클라이언트 서버 애플리케이션 : 데이터 통신은 양방향. 클라이언트가 서버에 요청을 보내고, 서버는 그 요청의 처리결과를 응답으로 반환한다. 요청과 응답을 주고받는 것을 클라이언트 서버 애플리케이션이라고 부른다.**

   -> **피어투피어 애플리케이션 : 서버를 거치지 않고 클라이언트끼리 직접 데이터를 주고 받는 애플리케이션. 통신 상대를 특정하고자 서버를 이용하는 경우도 있다.**

3. ISP에 대해 아는대로 설명해보세요

   -> **Internet Service Provider. 인터넷 접속 서비스를 제공하는 기업. 최상위 ISP를 Tier1이라 부르고, Tier1 이외의 ISP도 최종적으로는 Tier1에 연결되어 인터넷 상의 모든 ISP는 Tier1을 경유해서 연결된다.**

4. 클라우드 서비스를 사용하게 된 배경은?

   -> **직접 서버를 운용/관리하게 되면, 서버의 상태를 항상 감시해야하고 문제 발생에 바로 대처해야한다. 필요에 따라서 처리 능력을 확장할 필요가 있기 때문에, 시간과 비용이 들어간다. 클라우드는 서버를 직접 관리 운용하지 않고 서버의 기능만을 이용하기 때문에, 위의 문제를 해결할 수 있다.**

5. 다음중 TCP/IP 응용 계층에서 사용하는 프로토콜이 아닌것은?
   - HTTP
   - ICMP
   - SMTP
   - DHCP
   - IMAP4
   
   -> **ICMP는 인터넷 계층에서 사용되는 프로토콜이다.**

---

1. LAN과 WAN의 풀네임을 말하고 간단히 설명하세요

   -> **LAN : Local Area Network  <br>거점 내의 네트워크 통신을 의미 , 기기 끼리의 통신**

   -> **WAN : Wide Area Network  <br>LAN 끼리의 네트워크 통신을 의미**

2. Client-Server구조와 P2P구조의 차이점을 설명하세요

   -> **Client-Server구조 : 클라이언트와 서버가 데이터를 주고받는 형태**

   -> **P2P구조 : 서버의 개입 없이 클라이언트 끼리 데이터를 주고받는 형태 <br>하지만 클라이언트 대상을 지정할 때 서버의 개입이 생기기도 한다.**

3. 클라우드 서비스의 장단점을 간단히 설명하세요

   -> **장점 : 서버 증설/축소 등 변경 시에 계약만 변경하면 돼서 편리하다<br>인터넷만 연결 된다면 어디서든 접속할 수 있다**

   -> **단점 : 보안에 취약하다   비용이 비싸다<br>데이터 관리가 손에 닿지 않는 범위에 있어서 관리를 직접할 수 없다**

4. 클라우드 서버와 온프레미스서버의 차이점을 설명하세요

   -> **클라우드 서버 : 서버 관리를 사업자가 한다**

   -> **온프레미스 서버 : 사용자가 직접 관리,보수 한다**

5. 클라우드 서비스중 IaaS, PaaS, SaaS에 대해 설명하세요

   -> **IaaS : 하드웨어까지 제공 + OS,미들웨어 직접 설치/애플리케이션도 직접 제작**

   -> **PaaS : 하드웨어,OS,미들웨어 제공 + 애플리케이션도 직접 제작**

   -> **SaaS : 하드웨어,OS,미들웨어,애플리케이션 제공 + 애플리케이션 사용 가능**

<hr>

1. 사내 네트워크의 구성 요소와 각 요소에 대해 간단히 설명하시오

   > 사내 네트워크의 종류로는 LAN과 WAN이 있습니다.
   >
   > LAN은 Local Area Network의 약자로 작은 지역의 네트워크를 말합니다.
   >
   > WAN은 Wide Area Network의 약자로 LAN과 LAN을 이어 광범위한 지역 단위로 구성한 네트워크입니다.

2. 애플리케이션의 종류를 말하고 간단히 설명하시오

   > 애플리케이션의 종류로는 Client-Server Application과 P2P Application이 있습니다.
   >
   > Client-Server Application은 Client는 Server에게 필요한 데이터를 요청하고, Server는 요청에 맞는 데이터를 응답합니다.
   >
   > P2P Application은 서버를 거치지 않고 클라이언트끼리 직접 통신하는 방식입니다.

3. 프로토콜에 대해 간단히 설명하고 네트워크 아키텍쳐와의 관계를 설명하시오

   > 프로토콜은 네트워크 통신 규약을 의미합니다.
   >
   > 네트워크 아키텍쳐는 그런 프로토콜들의 집합입니다.

4. 클라우드 서비스의 장단점을 설명하시오

   > 클라우드 서비스의 장점으로는 사용자가 서버를 직접 설치하고 운영할 필요가 없고, 그에 따른 비용을 절약할 수 있다는 점이 있습니다.
   >
   > 단점으로는 데이터를 조직 외부에 두기 때문에 보안에 유의해야한다는 점이 있습니다.

5. IaaS, PaaS, SaaS의 분류 기준과 어떤 기준으로 분류 하였는지 설명하시오

   > IaaS는 Infra as a Service로 인프라 즉 하드웨어를 제공해주는 서비스입니다.
   >
   > PaaS는 Platform as a Service는 하드웨어와 함께 OS, 미들웨어를 제공해주는 서비스입니다.
   >
   > SaaS는 Software as a Service는 하드웨어 OS, 미들웨어와 더불어 애플리케이션을 제공해주는 서비스입니다.

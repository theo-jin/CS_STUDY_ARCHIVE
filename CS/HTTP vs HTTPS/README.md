# HTTP vs HTTPS

### HTTP
- HTTP(Hypertext Transfer Protocol)와 HTTPS(Hypertext Transfer Protocol Secure)는 인터넷에서 정보를 주고받는 데 사용되는 프로토콜입니다.

- HTTP(HyperText Transfer Protocol)는 하이퍼 텍스트 전송 프로토콜으로 간단히 말해서 인터넷을 작동시키는 역할을 하며, 웹 서버 및 웹 브라우저 상호 간의 데이터 전송을 위한 응용계층 프로토콜입니다.
- 웹 사이트에 액세스하기 위해서는 프로토콜 변형이 필요한데, 이때 웹 사이트 URL이 일반적으로 “http://www..”로 시작하며 URL에 해당하는 웹 페이지를 가져오기 위해 웹 사이트 서버에 명령을 보내 작동하게 됩니다.

### HTTPS
- HTTPS는 HTTP에 SSL(Secure Socket Layer)이나 TLS(Transport Layer Security)를 추가하여 보안을 강화한 HTTP 요청을 말한다. 
- HTTPS는 데이터 전송 중에 암호화를 수행하여 제3자가 데이터를 볼 수 없게 만듭니다. SSL/TLS은 전송계층에서 보안을 제공하는 프로토콜입니다. 
- 클라이언트와 서버가 통신을 할 때, SSL/TLS를 통해 제 3자가 메시지를 도청하거나 변조하지 못하도록 합니다. 예를 들어 서버와 클라이언트 사이에 통신을 할 때 공격자가 서버인척하며 사용자 정보를 가로채는 인터셉터가 생길수있는데 SSL/TLS는 이러한 인터셉터를 방지할수있습니다.  
- 또한 구글은 ssl인증서를 강조해왔고 사이트 내 모든 요소가 동일하면 HTTPS서비스를 하는 서비스가 SEO순위가 높다고 공식적으로 밝혔습니다. 

HTTPS 구축하는 방법은 세가지입니다. 
- 직접 CA에서 구매한 인증키 기반으로 HTTPS서비스를 구축하거나
- 서버 앞단의 GTTPS를 제공하는 로드 밸런서를 두거나 
- 서버 앞단에 HTTPS를 제공하는 CDN을 둬서 구축합니다. 
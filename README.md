# IOSInterviewQuestion
iOS 면접 질문 모음

>1. 컴퓨터 구조와 관련하여 CPU, RAM, 저장장치의 역할과 상호 작용에 대해 설명해주세요.  <br/>

   CPU(중앙 처리 장치): CPU는 컴퓨터의 중앙 처리 장치로, 명령어를 해석하고 실행하는 주체, 산술 논리 연산, 제어 흐름 관리 등을 담당해 컴퓨터의 핵심적인 기능을 수행. 
   <br/>
   RAM(랜덤 액세스 메모리): RAM은 핸덤 액세스 메모리로, 현재 실행 중인 프로그램이나 작업의 데이터를 일시적으로 저장하는 역할, 빠른 읽기/ 쓰기 속도를 제공해 CPU가 빠르게 데이터에 접근할 수 O. 
   <br/>
   저장창치: 저장장치는 데이터를 영구적으로 보존하는데 사용, 하드 디스크나 SSD와 같은 매체를 통해 데이터를 저장하고, 전원이 꺼져도 정보를 유지할 수 O. <br/>

>2. 캐시 메모리의 개념과 종류, 역할에 대해 설명해주세요.  <br/>
   
   캐시메모리의 개념: 캐시 메모리는 컴퓨터의 성능을 향상시키기 위한 임시 저장소로, CPU와 주 기억장치 사이에 위치한다. 빠른 속도로 데이터에 접근해 프로세서의 작업 속도를 높이는 역할을 함.
   <br />
   캐시 메모리의 종류: 주로 레벨 1(L1), 레벨 2(L2), 레벨 3(L3) 세 가지 종류의 캐시 메모리가 있다. 각각은 크기와 액세스 속도에서 차이가 있으며, 계층 구조로 구성돼 CPU와 협력해 데이터를 효과적으로 관리함.
   <br />
   캐시 메모리의 역할: 캐시 메모리의 주요 역할은 CPU가 자주 사용하는 데이터를 주 기억장치보다 빠르게 제공해 프로세서 성능을 향상시크는 것이다. 또한, 에너지 소모 감소와 데이터 일관성 유지에도 기여함.
   <br />

>3. CPU 아키텍처의 종류(예: ARM, x86)와 특징에 대해 설명해주세요. <br />

   x86 아키텍처: 주로 인텔과 AMD에서 사용되며, 대부분의 개인 컴퓨터와 서버에 적용. CISC(Complex Instruction Set Computing) 아키텍처로, 다양한 명령어 세트를 지원해 유연하게 다양한 작업을 수행할 수 O.
   <br />
   ARM 아키텍쳐: 주로 모바일 기기와 임베디드 시스템에서 사용됨. RISC(Reduced Instruction Set Computing) 아키텍처로, 단순한 명령어 세트와 저전력 소모로 알려져 있어 이동식 장치 및 저전력 요구 시스템에 적합함.
   <br />
   RISC와 CISC의 차이: RISC는 적은 명령어를 가지고 빠른 속도를 지향하며, CISC는 다양하고 복잡한 명령어를 가지고 효율적인 프로그래밍을 지원.
   <br />

>4. iOS 기기에서 사용되는 AP(Application Processor)의 특징과 역할에 대해 설명해주세요. <br />

   AP(Application Processor)는 Apple의 A시리즈 칩셋으로 알려져있음. 이 칩셋은 Apple이 자체적으로 설계하고 제조한 것으로 고유한 아키텍처와 기술적인 특징을 가지고 있다. 주로 iPhone, iPad 및 iPod Touch와 같은 iOS 기기에서 사용된다.
   <br/>
   A시리즈 칩셋의 역할: A시리즈 칩셋은 iOS 기기에서 중앙 처리 장치, 그래픽 처리 장치(GPU), 머신러닝 가속기, 이미지 신호 처리 장치 등을 포함한 다양한 컴포넌트를 통합한 통합형 칩셋. 이는 최적화된 성능과 에너지 효율성을 제공해 iOS 기기의 뛰어난 성능을 구현하는데 기여한다.
   <br />
   특수 기능 및 최적화: A시리즈 칩셋은 Apple의 특수 기능과 최적화된 소프트웨어와의 조합으로 iOS 기기에서 원활한 사용자 경혐을 제공한다. 이는 iOS 운영 체제와의 높은 통합성과 최신 기술을 효과적으로 활용함으로써 이뤄진다.
   <br />
   보안 및 프라이버시 강화: A시리즈 칩셋은 iOS 기기에서의 보안 및 프라이버시를 강화하는 데 기여함. Secure Enclave같은 특수한 하드웨어 기능을 활용해 사용자 데이터의 안전성을 보장하고, Face ID 및 Touch ID와 같은 생체 인식 기술을 지원한다.
   <br />

>5. 운영체제의 역할과 iOS에서의 운영체제 구조에 대해 설명해주세요. <br />
운영체제의 역할: 컴퓨터 시스템 관리자로서 하드웨어 자원을 효율적으로 관리하거, 멀티태스킹, 자원 할당, 보안, 파일 관리 등 다양한 기능을 수행
<br />

iOS에서의 운영체제 구조: iOS는 애플이 개발한 운영체제로, Darwin 커널 기반에 UIKit, 코어 서비스, 코어 OS 등이 통합돼 있어 사용자 인터페이스부터 하드웨어 관리까지 종합적으로 제공한다.
<br />

>6. 프로세스와 스레드의 차이점, iOS에서의 프로세스와 스레드 관리 방법에 대해 설명해주세요. <br />

프로세스와 스레드의 차이: 프로세스는 독립된 실행 환경을 가진 프로그램이고, 스레드는 프로세스 내에서 실행되는 작은 실행 단위다. 프로세스는 독립된 메모리를 가지고 있고, 스레드는 프로세스의 자원을 공유함.
<br />

iOS에서의 프로세스와 스레드 관리: iOS에서는 각 애플리케이션이 독립된 프로세스로 실행되며, 메인 스레드에서는 UI 업데이트와 관련된 작업이 주로 처리됨. 추가 스레드는 GCD(Grand Central Dispatch)나 Operation Queue를 사용해 관리되며, iOS는 멀티코어 환경에서도 효과적으로 동작함.
<br />

>7. 메모리 관리 기법 중 iOS에서 사용되는 방식과 그 특징에 대해 설명해주세요. <br />

iOS에서 가장 일반적으로 사용되는 메모리 관리 기법은 Automatic Reference Counting(ARC)다. ARC는 컴파일러가 자동으로 객체의 참조 횟수를 관리해 메모리 누수를 방지하고 편리한 코드 작성을 가능하게 함. 순환 참조에 대한 주의가 필요하지만, 대체로 안전하고 간편한 메모리 관리 방식.
<br />

>8. iOS의 샌드박스(Sandbox) 개념과 역할, 앱 간 데이터 공유 방법에 대해 설명해주세요. <br />

iOS의 샌드백스는 각 앱이 독립된 실행 환경에서 실행되어 안전성을 보장하며, 앱 간 데이터 공유는 iOS 확장 기능, URL Scheme, Universal Links, App Groups를 이용해 간접적으로 이뤄진다. 이를 통해 사용자 개인 정보 보호와 시스템 안정성을 동시에 유지함.
<br />

>9. iOS에서의 메모리 구조와 관리 방식에 대해 자세히 설명해주세요. <br />

메모리 구조: iOS기기의 메모리는 코드, 데이터, 스택, 힙 등으로 구성됨
코드 영역: 앱의 실행 코드가 저장된다.
데이터 영역: 전역 변수와 정적 변수가 저장된다.
스택 영역: 함수 호출 및 지역 변수가 저장된다.
힙 영역: 동적으로 할당된 메모리가 저장된다.
<br />
메모리 관리 방식
iOS는 Automatic Reference Counting(ARC)를 사용해 메모리를 자동으로 관리한다.
ARC는 객체의 참조 횟수를 추적해 메모리를 자동으로 할당하고 해제한다.
메모리 최적화
개발자는 메모리 누수를 방지하기 위해 객체의 생명 주기를 관리해야한다.
Instruments와 같은 도구를 사용해 메모리 사용량을 모니터링하고 최적화할 수 O.
<br />
<br />

>10. 힙 영역에서 객체가 어떻게 할당되고 관리되는지 설명해주세요. <br />

힙 영역은 동적으로 할당된 메모리가 저장되는 영역, iOS 애플리케이션에서 객체를 생성하면 해당 객체는 힙 영역에 메모리가 할당된다. 객체에 대한 참조를 사용해 해당 객체에 접근할 수 있으며, 참조 횟수는 ARC를 통해 추적된다. 객체가 더 이상 필요하지 않을 때, 참조 횟수가 0이 되면 해당 객체의 메모리가 자동으로 해제된다. 이를 통해 힙 영역의 메모리를 효율적으로 관리해 앱의 성능을 유지할 수 O.
<br />
<br />

>11. 스택 영역에서 함수 호출과 로컬 변수의 메모리 할당 및 해제 과정을 설명해주세요. <br />

스택 영역은 함수 호출과 로컬 변수의 메모리 할당 및 해제에 사용된다. 함수가 호출될 때마다 스택에 새로운 프레임이 생성되고, 이 프레임에는 함수의 매개변수, 반환 주소 및 지역 변수등이 저장된다. 로컬 변수는 해당 함수가 호출될 때 생성되고, 함수가 종료될 때까지 메모리에 유지되며, 함수가 종료되면 해당 변수의 스택 프레임도 함께 해제된다. 이러한 방식으로 스택 영역은 함수 호출과 로컬 변수의 메모리 할당 및 해제를 관리한다.
<br />
<br />

>12. 네트워크 프로토콜 스택과 iOS에서의 네트워크 통신 방식에 대해 설명해주세요. <br />

네트워크 프로토콜 스택은 네트워크 통신을 위한 소프트웨어 구조체이며, iOS에서 URLSession을 통해 주로 HTTP및 HTTPS 프로토콜을 사용해 네트워크 통신을 한다. 이는 비동기적으로 이뤄지며 데이터 보안과 사용자 인증을 고려한다. iOS의 네트워크 통신은 기본적으로 TCP/IP 스택과 상호작용한다.
<br />
<br />

>13. HTTP와 HTTPS의 차이점, iOS에서의 보안 통신 방법에 대해 설명해주세요. <br />

HTTP와 HTTPS는 둘 다 웹 통신을 위한 프로토콜이지만, 그 중에서도 HTTPS가 보안 측면에서 뛰어나다. HTTP는 데이터를 암호화하지 않고 전송하기 때문에 보안에 취약하다. 그러나 HTTPS는 SSL or TLS 프로토콜을 사용해 데이터를 암호화하고, 이를 통해 중간자 공격을 방지하고 데이터의 안전한 전송을 보장한다.
iOS에서의 보안 통신은 주로 HTTPS를 사용한다. iOS는 URLSession 프레임워크를 통해 HTTPS 통신을 지원하며, 이는 데이터를 안전하게 전송할 수 있도록 도와준다. 또한, iOS는 TLS를 통해 데이터를 암호화하여 보안을 강화한다. 이를 통해 사용자의 개인 정보를 안전하게 보호하고 민감한 데이터를 안전하게 전송할 수 O.
<br />
<br />

>14. TCP와 UDP의 차이점에 대해서 설명해 주세요. <br />

TCP,UDP는 둘 다 네트워크 통신을 위한 프로토콜이지만, 그들 간에는 몇 가지 중요한 차이가 있다. TCP는 연결 지향적이며 신뢰성있는 데이터 전송을 보장하고, UDP는 비연결성이며 신속한 뎅터 전송을 강조한다.
TCP는 데이터 전송의 정확성과 순서를 보장하기 위해 패킷 재전송 및 흐름 제어와 같은 메커니즘을 제공하는 반면, UDP는 신뢰성이나 순서의 보장을 포기하고 데이터를 더 빠르게 전송함
일반적으로 TCP는 파일전송, 이메일 및 웹 브라우징과 같이 신뢰성이 중요한 응용 프로그램에서 사용되며 UDP는 스트리밍 미디어, 온라인 게임 및 DNS와 같이 신속한 데이터 전송이 필요한 응용 프로그램에 사용된다.
<br />
<br />

>15. 소켓 통신에 대해 설명해주세요. <br />

소켓통신은 네트워크 상에서 프로세스 간 통신을 가능하게 하는 방법 중 하나다. 소켓은 컴퓨터 네트워크에서 통신 엔드포인트를 나타며, 클라이언트와 서버 간의 양방향 통신을 설정하고 관리하는 데 사용된다.
<br />
<br />

>16. REST API와 iOS에서의 네트워크 요청 및 응답 처리 방법에 대해 설명해주세요. <br />

iOS 애플리케이션에서는 URLSession을 사용해 REST API와 통신한다. URLSession은 서버로 요청을 보내고, 서버에서 온 응답을 처리하는 역할을 한다. 응답은 JSON 형식으로 받아와 Swift의 Codable을 이용해 처리하고, 네트워크 에러는 NSError 객체를 통해 처리된다.
<br />
<br />

>17. REST API에서 Method들의 차이점을 설명해주세요. <br />

* GET: 서버로부터 리소스를 요청하는데 사용된다. 주로 데이터를 읽을 떄 사용되며, 요청 본문에 데이터를 포함하지 않는다.
* POST: 새로운 리소스를 생성하거나 업데이트할 때 사용된다. 요청 본문에 데이터를 포함해 전송하며, 서버가 새로운 리소스를 생성한다.
* PUT: 지정된 리소스를 업데이트하는 데 사용된다. 요청 본문에 데이터를 포함해 전송하며, 해당 리소스를 요청된 데이터로 대체한다.
* DELETE: 지정된 리소스를 삭제하는 데 사용된다. 요청 본문에 데이터를 포함하지 않고, 지정된 리소스를 삭제한다.
* PATCH: 리소스의 부분적인 업데이트를 수행한다. 요청 본문에 업데이트할 데이터를 포함하며, 해당 리소스의 일부를 수정한다.
<br />
<br />

>18. HTTP 상태 코드에 대해서 설명해주세요. <br />

* 1xx(정보):
  * 요청이 수신되었으며 처리가 진행 중임을 나타냄
  * 예: 100 (Continue), 101(Switching Protocols)
* 2xx(성공):
  * 요청이 성공적으로 수행되었음을 나타낸다
  * 예: 200(OK), 201(Created), 204(No Content)
* 3xx(리다이렉션):
  * 클라이언트가 추가 동작을 수행해야 함을 나타낸다. 주로 리다이렉션을 나타냄
  * 예: 301(Moved Permanently), 302(Found), 304(Not Modified)
* 4xx(클라이언트 오류):
  * 클라이언트의 요청이 잘못되었거나 서버가 처리할 수 없음을 나타냄
  * 예: 400(Bad Request), 401(Unauthorized),404(Not Found)
* 5xx(서버 오류):
  * 서버에서 처리 중에 오류가 발생했음을 나타냄
  * 예: 500(Internal Server Error), 502(Bad Gateway), 503(Service Unavailable)
<br />
<br />

>19. iOS에서 메모리 사이즈와 관련된 개념과 고려 사항에 대해 설명해주세요. <br />

* 먼저 iOS 앱이 실행될 때 기기의 메모리, RAM을 사용하게 된다. 이는 앱이 더 많은 메모리를 사용할수록 더 많은 기기 리소스가 필요하며, 더 많은 메모리를 소모하게 된다. 그래서 개발자는 앱이 메모리를 효율적으로 사용할 수 있도록 고려해야함.
* iOS앱은 ARC를 사ㅛㅇ해 메모리를 관리한다. ARC는 개발자가 메모리 관리를 수동으로 처리하지 않도록 도와주지만, 여전히 메모리 누수나 다른 무네를 주의해야 한다. 메모리 누수는 메모리를 할당한 후 해제하지 않아 메모리가 계속해서 사용되는 상황을 의미하며, 이는 앱의 성능을 저하시킬 수 O.
* 메모리 최적화도 중요, 이를 통해 앱의 성능을 향상시키고 배터리 수명을 연장할 수 O. 메모리 최적화는 불필요한 객체의 생성과 보유를 피하고, 필요없는 데이터 구조를 정리함으로써 이뤄짐.
* iOS는 메모리 부족 상태에 대응하기 위해 메모리 경고를 발생시킨다. 이는 앱이 현재 메모리 사용량을 줄이는 등의 조치를 취할 수 있도록 한다. 이러한 메모리 경고에 대한 적절한 처리는 앱의 안정성과 성능에 영향을 미친다.
<br />
<br />

>20. iOS 디바이스의 메모리 제약과 앱 메모리 제한에 대해 설명해주세요. <br />

모바일 기기의 제한된 메모리 용량은 앱의 성능과 안정성에 직접적인 영향을 미친다. 너무 많은 메모리를 사용하는 경우 다른 앱이나 시스템 프로세스에 영향을 줄 수 있으며, 디바이스 성능을 저하시킬수 O.
또한 iOS는 각 앱에 대한 메모리 사용량을 제한한다. 각 앱은 시스템에서 할당된 메모리 용량 내에서 작동해야한다. 이는 앱이 과도한 메모리를 사용해 시스템 전체의 성능을 저하시키는 것을 방지하기 위한 조치
따라서 iOS앱을 개발할 때는 제한된 메모리 용량을 고려해 메모리를 효율적으로 사용해야한다. 메모리 누수를 방지하고 최적화된 앱을 설계함으로써 사용자 경험을 향상시킬 수 O. 또한 iOS의 메모리 제한에 대한 이해는 앱의 안정성과 성능을 유지한ㄴ데 중요한 역할을 함.
<br />
<br />

>21. 메모리 워드(word) 크기와 데이터 정렬(alignment)이 메모리 액세스 성능에 미치는 영향에 대해 설명해주세요.<br />

메모리 워드 크기와 데이터 정렬은 메모리 액세스 성능에 중요한 영향을 미친다. 메모리 워드 크기는 한 번의 메모리 액세스로 읽거나 쓸 수 있는 데이터의 양을 나타낸다. 일반적으로 메모리 워드 크기가 클수록 한 번의 액세스로 처리할 수 있는 데이터 양이 많아지므로 성능이 향상된다.
데이터 정렬은 데이터가 메모리에 배치되는 방식 데이터 정렬을 지키면 CPU가 메모리를 효율적으로 읽고 쓸 수 있으므로 성능이 향상된다. 반면에, 비정렬된 데이터 액세스는 추가적인 메모리 액세스가 필요하고, 이는 성능 저하를 가져올 수 O.
<br />
<br />

>22. 포인터 크기(32비트, 64비트)에 따른 메모리 사용량 차이와 고려 사항에 대해 설명해주세요.<br />

포인터 크기가 64비트로 증가하면 메모리 사용량이 늘어난다. 이는 주소 공간이 더 커지기 때문 또한, 포인터의 크기가 더 커지면 일부 경우에는 메모리 액세스 성능에 영향을 줄 수 있다.
<br />
<br />

>23. iOS 앱에서 대용량 데이터를 다룰 때 메모리 사이즈를 고려한 최적화 방안에 대해 설명해주세요.<br />
* 레이지 로딩(Lazy Loading):
   대용량 데이터를 한 번에 모두 메모리에 로드하는 것이 아니라, 필요할 때 로드함.
* 메모리 캐시(Memory Cache): 불필요한 메모리 사용을 최소화하기 위해 이미 로드된 데이터를 메모리에 캐싱함. 이를 통해 동일한 데이터를 다시 로드하지 않고 이 전에 로드된 데이터를 재사용할 수 O.
* 외부 저장소 활용: 대용량 데이터를 메모리에 로드하기보다는 외부 저장소에 저장하고 필요할 때 로드합니다. 이를 위해 파일 시스템이나 데이터베이스를 사용할 수 O. Core Data나 Realm과 같은 데이터베이스 프레임워크를 활용해 데이터를 관리하고 액세스할 수 O.
* 메모리 관리: ARC를 사용해 메모리 누수를 방지하고 메모리 사용을 최적화한다. 더이상 필요하지 않은 데이터는 적절히 해제해 메모리를 해제한다.
* 백그라운드 작업: 대용량 데이터 처리 작업을 백그라우느에서 수행해 메인 스레드의 동작을 방해하지 않도록 한다. Crand Central Dispatch(GCD)나 Operation Queue를 사용해 비동기적으로 작업을 수행할 수 O.
<br />
<br />

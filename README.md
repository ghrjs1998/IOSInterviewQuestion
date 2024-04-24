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

>24. 알고리즘의 시간 복잡도와 공간 복잡도의 개념, 빅오 표기법에 대해 설명해주세요. <br />

1. 알고리즘의 시간 복잡도:
* 알고리즘이 입력 크기에 따라 실행되는 데 걸리는 시간을 설명
* 일반적으로 알고리즘의 실행 시간은 입력 크기에 비례하며, 입력이 커질수록 실행 시간이 증가함
* 시간 복잡도를 표현할 때, 주로 최악의 경우 시나리오를 고려해 표기함
2. 알고리즘 공간 복잡도:
* 알고리즘이 실행되는 동안 사용하는 메모리 공간의 양을 설명
* 일반적으로 알고리즘의 공간 복잡도는 입력 크기와는 독립적이지만, 일부 알고리즘은 입력 크기에 따라 필요한 공간이 달라질 수 O.
* 공간 복잡도 역시 주로 최악의 경우 시나리오를 고려해 표기함
3. 빅오 표기법(Big O Notation):
* 알고리즘의 시간 복잡도와 공간 복잡도를 수학적으로 표현하는 표기법 중 하나
* 빅오 표기법은 알고리즘의 성능을 상한선으로 표현함. 즉, 알고리즘이 어떤 상황에서든 주어진 입력에 대해 실행되는 시간이나 공간이 이 표기법에 따른 한계를 초과하지 않음을 나타냄
<br />
<br />

>25. 자주 사용되는 정렬 알고리즘(예: 퀵 정렬, 병합 정렬)의 동작 원리와 시간 복잡도를 설명해주세요. <br />

퀵 정렬:
* 주어진 리스트를 분할하고, 각 부분 리스트를 재귀적으로 정렬하는 분할 정복 알고리즘
* 리스트에서 피벗 요소를 선택해 작은 요소는 왼쪽에, 큰 요소는 오른쪽에 배치, 이후 각 부분 리스트에 대해 재귀적으로 이과정을 반복해 정렬을 완성
* 평균적으로 퀵 정렬의 시간 복잡도는 O(n log n)
* 최악의 경우 이미 정렬된 리스트에 대해서 O(n^2)의 시간 복잡도를 가질수 O.
병합정렬:
* 두 단계로 진행되는데, 리스트를 절반으로 잘라 두 개의 부분 리스트로 분할함, 그 다음 각 부분 리스트를 재귀적으로 정렬하고, 정렬된 부분 리스트를 병합해 최종적으로 정렬된 리스트를 생성한다.
* 병합 정렬은 항상 O(n log n)의 시간 복잡도를 가지며, 안정적이고 효율적인 정렬 알고리즘 중 하나
<br />
<br />

> 26. 이진 탐색의 원리와 시간 복잡도에 대해 설명해주세요. <br />

이진 탐색은 정렬된 리스트에 특정 요소를 찾는 알고리즘을, 매 단계마다 탐색 범위를 반으로 줄여가며 탐색을 수행 우선, 주어진 리스트의 중간 요소를 선택하고 대상 값과 비교함. 대상 값이 중간 요소보다 작으면 왼쪽 부분 리스트에서 재귀적으로 탐색을 수행하고, 대상 값이 중간 요소보다 크면 오른쪽 부분 리스트에서 재귀적으로 탐색을 수행. 이러한 과정을 반복해 대상 값이 일치하는 요소를 찾거나 탐색 범위가 1이 될 때까지 계속함
이진 탐색의 핵심 특징은 매 단계마다 탐색 범위를 반으로 줄여가는 것, 이로 인해 최악의 경우에도 탐색 시간이 O(log n)으로 매우 효울적이다. 입력 크기가 크더라도 탐색 시간이 로그 시간에 비례해 증가하므로 매우 빠르게 원하는 요소를 찾을 수 O.
<br />
<br />

>27. 다이나믹 프로그래밍(Dynamic Programming)의 개념을 설명해주세요. <br />

주어진 문제를 더 작은 하위 문제로 나눠 해결하는 알고리즘 설계 기법, 이를 통해 반복되는 계산을 효율적이고 줄이고 최적해를 구할 수 O. 다이나믹 프로그래밍은 문제를 해결하는 과정을 '분할 정복'과 유사하게 하위 문제로 분할하고, 나를 이를 활용해 최종적인 해를 구하는 방법
보통 다이나믹 프로그래밍은 두 가지 방식으로 구현되는데, 하나는 메모이제이션(Memoization)방식으로 이미 계산한 결과를 저장해 중복 계산을 피하는 것이며, 나머지는 보텀업(Bottom-up)방식으로 작은 하위 문제부터 시작해 상위 문제를 해결해 나가는 것
이러한 다이나믹 프로그래밍은 주로 최적 부분 구조와 중복되는 부분 문제가 있는 문제에 적용됨, 예를 들어, 피보나치 수열 계산이나 최장 공통 부분 수열(Longest Common Subsequence)문제 등에 다이나믹 프로그래밍을 적용할 수 O.
<br />
<br />

>28. 자료구조의 종류와 iOS 개발에서 자주 사용되는 자료구조에 대해 설명해주세요. <br />

배열은 여러 개의 요소들을 순차적으로 저장하는데 사용되며, 인덱스를 통해 요소에 접근할 수 O. 예를 들어, 테이블 뷰의 데이터 소스로 배열을 활용해 각 셀에 표시할 데이터를 관리할 수 O.
딕셔너리는 키-값 쌍을 저장하며, 키를 사용해 값을 검색하거나 수정할 수 O. 이를 통해 특정 데이터를 빠르게 찾거나 관리할 수 O.
집합은 중복을 허용하지 않는 요소들의 모임을 나타내며, 주로 중복된 데이터를 제거하거나 고유한 값들을 추출하는 데 사용됨
<br />
<br />

> 29. 배열, 연결 리스트, 스택, 큐의 특징과 iOS에서의 구현 방법을 설명해주세요. <br />

배열은 동일한 데이터 타입의 요소들을 순차적으로 저장하는 자료구조, iOS에서는 Swift의 Array를 사용해 배열을 구현할 수 O. 이 배열은 인덱스를 사용해 요소에 접근하고, 데이터를 추가하거나 삭제할 수 O.
연결 리스트는 각 요소가 데이터와 다음 요소를 가리키는 포인터로 구성되어 있는 자료구조, iOS에서는 클래스를 사용해 각 노드를 정의하고, 이를 연결해 연결 리스트를 구현할 수 O.
스택은 후입선출 원리를 따르는 자료구조로, 데이터를 삽입하고 삭제할 때는 항상 스택의 맨 위에서 이뤄진다. iOS에서는 배열을 사용해 스택을 구현할 수 O.
큐는 선입선출원리를 따르는 자료구조로, 데이터를 합입하는 연산읜 큐의 뒤쪽에서, 삭제하는 연산은 앞쪽에서 이뤄짐. iOS에서도 배열을 사용해 큐를 구현할 수 O.
<br />
<br />

> 30. 해시 테이블의 개념, 충돌 해결 방법을 설명해주세요. <br />

해시 테이블은 키와 값을 매핑해 데이터를 저장하는 자료구조. 이를 위해 해시 함수를 사용해 키를 해시 값으로 변환하고, 이 해시 값을 인덱스로 사용해 데이터를 저장하거나 검색한다. 그러나 해시 충돌이 발생할 수 O. 즉, 두 개 이상의 키가 동일한 해시 값으로 매핑될 수 있다. 이러한 충돌을 해결하기 위한 방법은
* 개방 주소법(Open Addressing):
   충돌이 발생하면 다른 빈 슬롯을 찾아 데이터를 저장한다. 선형 탐색, 이차 탐색, 랜덤 탐색 등의 방식을 사용할 수 O.
* 체이닝(Chaining):
   충돌이 발생하면 같은 해시 값을 갖는 데이터들을 연결 리스트 형태로 연결해 저장함. 충돌이 발생한 위치에 새로운 데이터를 연결 리스트에 추가한다.
* 이중 해싱(Double Hashing)이나, 완전 탐색(Cuckoo Hashing)과 같은 다른 방법도 있다.
<br />
<br />

> 31. 트리 자료구조의 종류(예: 이진 트리, 이진 탐색 트리, AVL 트리)을 설명해주세요. <br />

트리 자료구조는 계층적인 데이터를 표현하는데 사용되며, 각  노드는 부모-자식 관계로 연결된다. 여러 종류의 트리가 있다.

* 이진 트리(Binary Tree):
   이진 트리는 각 노드가 최대 두 개의 자식 노드를 가질 수 있는 트리. 왼쪽 자식 노드와 오른쪽 자식 노드로 구성되며, 데이터의 검색과 정렬에 널리 사용된다.
* 이진 탐색 트리(Binary Search Tree, BST):
   이진 탐색 트리는 이진 트리의 한 종류로, 왼쪽 자식 노드의 값이 현재 노드의 값보다 작고 오른쪽 자식 노드의 값이 현재 노드의 값보다 큰 규칙을 따른다. 이러한 특성으로 인해 데이터의 검색이 효율적으로 이뤄짐
* AVL트리(AVL Tree):
   AVL 트리는 이진 탐색 트리의 한 종류로, 균형 잡힌 트리 구조를 유지한다. 각 노드의 왼쪽 서브트리와 오른쪽 서브트리의 높이 차이가 항상 1 이하가 되도록 유지된다. 이로 인해 검색, 삽입, 삭제 연산의 시간 복잡도가 O(log n)을 보장한다.
*  레드-블랙 트리(Red-Black Tree): AVL 트리와 비슷하게 균형 잡힌 이진 탐색 트리의 한 종류다. 다양한 삽입, 삭제 연산에 대해 트리의 균형을 유지하면서도 검색 성능을 보장한다.
<br />
<br />

> 32. 동시성 프로그래밍의 개념과 iOS에서의 동시성 처리 방식에 대해 설명해주세요. <br />

동시성 프로그래밍은 여러 작업이 동시에 실행되는 것처럼 보이도록 프로그램을 설계하고 구현하는 것. 이를 통해 프로긂ㅇ의 성능을 향상시키고, 사용자 경험을 개선할 수 O. iOS에서는 이를 위해 주로 Grand Central Dispatch(GCD)와 Operation Queue를 사용한다. GCD는 저수준 API로, 큐를 사용해 작업을 비동기적으로 실행하고, 시스템 리소스를 효율적으로 관리한다. 반면에 Operation Queue는 좀 더 객체 지향적인 인터페이스를 제공하며, 작업을 순차적 또는 병렬로 실행하고 작업 간의 종속성을 관리할 수 O. 이들을통해 iOS 애플리케이션에서 멀티스레딩과 비동기 작업을 효과적으로 다룰 수 O.
<br />
<br />

> 33. 병렬 처리와 동시 처리의 차이, iOS에서의 멀티코어 활용 방안에 대해 설명해주세요. <br />

병렬 처리와 동시 처리는 비슷한 개념이지만 약간의 차이가 있다. 병렬 처리는 하나의 작업을 여러 부분으로 나눠 동시에 실행하는 것이고, 동시 처리는 여러 작업이 동시에 진행되는 것을 의미한다. iOS에서 멀티코어를 활용하는 방안은 다양하다. 예를 들어 GCD를 사용해 병렬 처리를 구현하거나, Operation Queue를 세밀하게 설정해 멀티코어를 효율적으로 활용할 수 O. 또한 데이터 병렬 처리를 통해 작업을 여러 스레드로 나눠 처리함으로써 멀티코어를 활용할 수도 O.
<br />
<br />

> 34. 암호화와 보안의 기본 개념, iOS 앱 보안을 위한 방안에 대해 설명해주세요. <br />

1. 암호화와 보안의 기본 개념:
* 암호화: 데이터를 안전하게 전송하고 저장하기 위해 사용되는 프로세스입니다. 이는 데이터를 의도치 않은 사용자로부터 보호하기 위해 데이터를 변환하는 과정
* 해시 함수: 해시 함수는 임의의 데이터를 고정된 크기의 값으로 변환합니다. 이러한 변환 과정을 통헤 데이터의 무결성을 확인할 수 O.
* 공개키 및 개인 키 암호화: 공개키는 데이터를 암호화하는 데 사용되고, 개인키는 데이터를 해독하는 데 사용된다. 이러한 방식으로 안전한 통신을 보장한다.
* 인증: 사용자의 신원을 확인하는 프로세스로, 암호화와 함께 사용하여 데이터의 안전성을 높임
2. iOS 앱 보안을 위한 방안:
* 암호화된 통신: 앱이 서버와 통신할 떄는 TLS/SSL과 같은 프로토콜을 사용해 데이터를 암호화해야함.
* 저장된 데이터 보호: iOS에서 제공하는 키체인을 사용해 중요한 데이터를 안전하게 저징한다. 또한 데이터를 저장할 때는 암호화를 사용해 보호한다.
* 앱의 코드 보안: 앱의 코드를 난독화하고, 취약점을 최소화하기 위해 정기적인 코드 리뷰와 보완을 수행
* 보안 업데이트 및 모니터링: 새로운 보안 취약점에 대응하기 위해 앱을 업데이트하고, 앱의 사용 및 보안 이벤트를 모니터링해 신속하게 대응
<br />
<br />

> 35. 대칭키 암호화와 비대칭키 암호화의 차이에 대해 설명해주세요. <br />

* 키 사용 방식: 대칭 키는 엄호화와 복호화에 동일한 키를 사용하고, 비대칭키는 공개키와 개인키를 사용
* 보안성: 비대칭키는 대칭키보다 높은 보안성을 제공
* 속도와 효율성: 대칭키가 비대칭키에 비해 속도가 빠르고 효율적이다
* 키관리: 대칭키의 경우 키 관리가 어려울 수 있지만, 비대칭키의 경우 키 관리가 상대적으로 간단하다.
<br />
<br />

> 36. 해시 함수의 개념과 활용 사례에 대해 설명해주세요. <br />

해시 함수는 데이터를 고유한 고정 크기에 값으로 변환하는 함수로, 주로 데이터 무결성을 검증하고 보안에 활용된다. 이 함수는 임의의 길이의 데이터를 받아들여 항상 동일한 크기의 고유한 해시 값으로 변환한다. 이러한 특징으로 인해 해시 함수는 다양한 분야에 사용된다.
데이터 무결성을 검증하기 위해 데이터 전송 시에 데이터의 해시 값을 함께 전송해 수신 측에서 데이터의 무결성을 확인할 수 O. 또한, 암호화에서 해시 함수가 HMAX과 같은 메시ㅈ 인증 코드를 생성하는데 사용된다. 비밀번호 보안에도 해시 함수가 활용되어 사용자의 비밀번호를 안전하게 저장하고 검색에 사용될 수 O.
데이터 검색에세도 해시 함수는 빠른 검색을 위한 해시 테이블과 같은 자료 구조에서 사용된다. 이러한 방식으로 해시 함수는 데이터 무결성 검증부터 비밀번호 보안까지 다양한 분야에서 중요한 역할을 한다.
<br />
<br />

> 37. 가상 메모리(Virtual Memory)의 개념과 동작 원리에 대해 설명해주세요. <br />

주 기억장치인 RAM의 용량을 넘어서는 프로그램의 실행을 지원한다. 기본적으로 운영체제가 프로세스에게 실제 메모리보다 더 큰 가상 주소 공간을 할당하고, 필요한 부분만 물리 메모리에 올려서 사용하는 방식. 이렇게 사용함으로써 프로그램은 실제로는 물리 메모리보다 큰 메모리 공간을 사용하는 것처럼 느낄 수 O.
가상 메모리는 페이징이라는 기술을 사용해 동작한다. 메모리는 작은 크기의 페이지로 분할되고, 각 프로세스는 가상 주소를 이 페이지들로 나타낸다. 필요한 페이지가 물리 메모리에 없을 때 페이지 폴트가 발생하고, 해당 페이지를 디스크에서 가져와 물리 메모리에 하당한다.
가상 메모리를 사용함으로써 메모리 관리가 효율적으로 이뤄지고, 여러 프로세스 간의 메모리 공간이 격리되어 안정성이 높아진다. 또한 가상 메모리를 통해 실제 물리 메모리보다 큰 메모리 공간을 사용할 수 있어서 대용량 데이터 처리나 여러 프로그램 동시 실행 등의 작업을 효율적으로 처리할 수 O.
<br />
<br />

> 38. 가상 메모리의 필요성과 장점에 대해 설명해주세요. <br />

1. 실행 가능한 프로그램의 크기 증가
* 가상 메모리를 사용하면 물리적인 메모리 용향보다 큰 프로그램을 실행할 수 O. 이는 프로그램의 크기가 커지고, 더 많은 리소스를 필요로 할 때 매우 유용함
2. 여러 프로그램의 병행 실행
* 여러 프로그램이 동시에 실행될 때, 가상 메모리는 각 프로그램에게 독립적인 메모리 공간을 할당해 서로 간섭이 없도록 보장함. 이는 운영체제의 멀티태스킹 환경에서 매우 중요한 역할을 함
3. 메모리 관리의 효율성 향상
* 가상 메모리는 메모리의 효율적인 관리를 가능하게 합니다. 필요한 만큼의 메모리만 사용하고, 실제로 필요하지 않은 데이터는 디스크에 저장함으로써 물리 메모리의 활용도를 높인다.
4. 메모리 단편화 완화
* 가상 메모리를 사용하면 물리 메모리의 크기에 상관없이 연속된 메모리 공간을 할당할 수 O. 이는 메모리 단편화를 완화시키고, 메모리 관리를 더욱 쉽게 만든다
5. 빠른 응답 시간 유지
* 가상 메모리를 사용하면 필요한 데이터가 물리 메모리에 없을 경우에도 빠른 응답 시간을 유지할 수 O. 이는 페이지 폴트와 가튼 기술을 통해 디스크에서 필요한 데이터를 가져와서 메모리에 할당함으로써 가능
6. 시스템 유연성 향상
* 가상 메모리를 사용함으로써 시스템의 유연성이 향상된다. 프로그램의 요구에 따라 가상 메모리의 크기를 동적으로 조절할 수 있으며, 여러 프로그램을 동시에 실행하는 환경에서 유용하다.
<br />
<br />

> 39. 페이징(Paging) 기법의 개념과 동작 원리, 페이지 테이블의 역할에 대해 설명해주세요. <br />

메모리를 일정한 크기의 블록인 페이지로 나눠 관리함. 각 프로세스는 이러한 페이지를 사용해 가상 주소 공간을 관리하며, 필요한 페이지만 물리 메모리에 올린다.
페이징 기법은 가상 메모리의 관리를 단순화하고 메모리 사용의 효율성을 높인다. 예를 들어, 프로세스가 물리 메모리보다 큰 메모리를 요구하는 경우, 페이징을 통해 필요한 페이지만 물리 메모리에 올리고 나머지는 디스크에 보관해 메모리를 효율적으로 활용할 수 O.
이때 각 프로세스는 자신의 가상 주소 공간에 있는 페이지를 실제 물리 메모리에 매핑하기 위해 페이지 테이블을 사용함. 페이지 테이블은 가상 주소와 물리 주소 간의 매핑 정보를 저장하고 있으며, 프로세스가 가상 주소에 접근할 때 이를 이용해 실제 물리 주소를 찾아내게 됨
페이지 테이블을 통해 가상 메모리와 물리 메모리 간의 매핑이 이뤄지므로, 프로세스는 자신만의 가상 주소 공간을 갖고 있으면서도 실제로는 물리 메모리를 공유할 수 O. 또한 페이지 테이블을 이용해 가상 주소 공간의 페이지를 물리 메모리에 적절히 매핑함으로써 메모리의 효율적 사용이 가능 
<br />
<br />

> 40. 세그먼테이션(Segmentation) 기법의 개념과 페이징과의 차이점에 대해 설명해주세요. <br />

세그먼테이션과 페이징은 모두 가상 메모리를 관리하는 기법이지만, 그 방식과 특징에서 차이가 있다. 세그먼테이션은 프로세스의 주소 공간을 서로 다른 크기의 논리적 단위인 세그먼트로 나눠 관리한다.
반면에, 페이징은 고정된 크기의 블록으로 나눠진 페이지를 사용해 가상 메모리를 관리함. 페이지는 일정한 크기로 나눠져 있으며, 프로세스의 주소 공간을 페이지 단위로 관리함
세그먼테이션과 페이징의 주요 차이점 중 하나는 크기다. 새그먼트는 서로 다른 크기를 가질 수 있지만, 페이지는 고정된 큭를 가지고 있습니다. 이러한 특징으로 인해 세그먼테이션은 내부 단편화와 외부 단편화가 발생할 수 있다. 반면에, 페이징은 내부 단편화와 외부 단편화를 방지할 수 O.
또한, 세그먼테이션은 세그먼트 단위로 가상 주소를 물리 메모리에 매핑하고, 페이징은 페이지 단위로 가상 주소를 물리 주소에 매핑한다.
<br />
<br />

> 41. iOS 앱의 메모리 사용량 최적화를 위한 방안과 고려 사항에 대해 설명해주세요. <br />

iOS 앱의 메모리 최적화는 성능과 사용자 경험을 향상시키는데 중요하다. 주요 방안으로는 메모리 관리, 리소스 최적화, 코드 최적화를 사용하며, 변경 사항을 테스트해 성능 저하를 방지해야 한다. 이전 경험에서는 Instruments를 활용해 메모리 누수를 해결하고 이미지 압축을 통해 메모리 사용을 최적화했다.
<br />
<br />

> 42. 메모리 캐싱 기법(예: NSCache, 이미지 캐싱)의 개념과 iOS에서의 구현 방법을 설명해주세요. <br />

메모리 캐시은 iOS 앱에서 성능을 향상시키는 중요한 기법 중 하나다. NSCache는 키-값 쌍의 객체를 메모리에 캐싱하는데 사용되며, 자동으로 메모리 부족 시에 캐시된 객체를 해제해 메모리를 효율적으로 관리한다. 이를 화룡해 자주 사용되는 데이터를 캐싱함으로써 앱의 성능을 향상시킬 수 O.
또한, 이미지 캐싱은 특히 많이 사용되는 콘텐츠인 이미지를 메모리에 저장해 반복적인 로드를 줄이고 성능을 개선하는데 도움을 준다. iOS에서는 NSCache를 사용해 이미지를 캐싱하는데, 이를 통해 반복적으로 로드되는 이미지를 효율적으로 관리할 수 O. 이를 활용해 사용자 경험을 향상시키고 앱의 성능을 최적화할 수 O.
<br />
<br />

> 43. 대용량 데이터(예: 이미지, 비디오) 처리 시 메모리 최적화 방안(예: lazy loading, 썸네일 활용)에 대해 설명해주세요. <br />

대용량 데이터를 처리할 때 메모리 최적화는 중요한 고려사항이다. 이를 위해 Lazy Loading과 썸네일 활용과 같은 방법을 사용해 필요한 시점에만 데이터를 로드하고 메모리를 효율적으로 관리한다. 또한, 메모리 캐싱을 활용해 자주 사용되는 데이터를 저장해 반복적인 로드를 최소화하고, 배치 처리를 통해 메모리 부하를 분산시킨다. 이러한 방법을 통해 대용량 데이터를 처리할 때 메모리 서용량을 최적화하고 성능을 향상시킬 수 O.
<br />
<br />

> 44. 데이터베이스의 종류와 iOS에서 주로 사용되는 데이터베이스에 대해 설명해주세요. <br />

데이터베이스는 데이터를 구조화해 저장, 관리 및 검색하는 시스템으로, 주로 관계형 데이터베이스, NoSQL 데이터베이스, 객체 지향 데이터베이스 등으로 분류된다. iOS 애플리케이션에서는 Core Data, SQLite, Realm과 같은 데이터베이스가 주로 사용된다.
* Core Data
   Apple이 iOS와 macOS용으로 제공하는 객체 그래프ㅘ 영속성 프레임워크, 객체 간의 관계를 관리하고 데이터를 SQLite, XML 또는 이진 파일과 같은 백엔드 저장소에 영속적으로 저장할 수 O.
* SQLite
   경량의 오픈 소스 데이터베이스 엔진으로, C 라이브러리 형태로 제공. 단일 파일로 데이터를 저장하고 SQL 문을 사용해 데이터에 액세스할 수 O. 내장 애플리케이션에 적합한 데이터베이스
* Realm
   모바일 앱용으로 설계된 객체 지향 데이터베이스. SQLite보다 더 빠른 속도와 쉬운 사용성을 제공하며, 객체 간의 관계를 자연스럽게 처리
각 데이터 베이스는 자신의 장점과 단점을 가지고 있으며, 애플리케이션의 요구 사항에 맞게 선택되어 사용된다.
<br />
<br />

> 45. 관계형 데이터베이스의 ACID 특성과 트랜잭션의 개념에 대해 설명해주세요. <br />

1. 원자성(Atomicity):
* 트랜잭션은 하나의 논리적인 작업 단위로 간주되며, 모든 연산이 성공적으로 롼료되거나 실패할 경우 이전 상태로 롤백되어야 함.
* 즉, 트랜잭션 내의 모든 작업은 원자적으로 실행되어야 함. 어떤 작업이 실패하면 트랜잭션 전체가 실패해야 하고, 모든 변경 사항은 취소되어야 함
2. 일관성(Consistency):
* 트랜잭션 전후에 데이터베이스는 일관된 상태를 유지해야 한다.
* 즉, 트랜잭션 실행 전의 데이터베이스 상태가 트랜잭션 실행 후의 상태와 일관되어야한다. 데이터베이스의 제약 조건(예: 외래 키 제약, 무결성 제약)은 언제나 만족되어야 함
3. 고립성(Isolation):
* 여러 트랜잭션이 동시에 실행될 떼 각각의 트랜잭션은 서로 영향을 주지 않고 독립적으로 실행되는 것처럼 보여야 한다.
* 한 트랜잭션이 실행 중일 때 다른 트랜잭션의 연산이 그 영향을 미치지 않아야 한다.
4. 지속성(Durablility):
* 트랜잭션이 성공적으로 완료되면 그 결과는 영구적으로 반영되어야 한다.
* 시스템 장애나 전원 공급 장애와 같은 문제가 발생하더라도 트랜잭션의 결과는 유지되어야 함
<br />
<br />

> 46. iOS에서 데이터베이스 스키마 버전 관리와 마이그레이션을 처리하는 방법을 설명해주세요. <br />

1. 모델 버전 관리:
* Xcode에서 Core Data 모델을 생성하고 관리한다. 각 모델은 버전을 가질 수 O.
* 변경된 스키마에 대해 새로운 모델 버전을 추가하고, 변경된 엔터티나 속성을 정의
2. 마이그레이션 준비:
* 변경된 모델을 기반으로 마이그레이션을 준비. Xcode는 변경 사항을 감지하고 이에 따른 마이그레이션 코드를 자동으로 생성해 줌
3. 마이그레이션 수행:
* 애플리케이션이 처음 실행될 때 또는 데이터베이스에 접근하기 전에 마이그레이션을 수행한다.
* 마이그레이션은 Core Data 스택 초기화 시에 이뤄지며, 이 과정에서 변경된 모델을 기바느로 이전 버전의 데이터를 새로운 버전의 모델에 맞게 변환한다.
4. 자동 혹은 수동 마이그래이션:
* Core Data는 자동으로 간단한 마이그레이션을 처리할 수 O. 이 경우, 모델을 업데이트하면 Core Data가 자동으로 이전 데이터를 새로운 모델에 맞게 변환한다.
* 복잡한 마이그레이션 작업의 경우, 수동으로 마이그레이션 코드를 작성해 데이터의 변환 과정을 더우 세밀하게 제어할 수 O.
5. 마이그래이션 테스트:
* 마이그레이션 프로세스를 테스트해 데이터 손실이나 오류가 없는지 확인
* 테스트를 통해 안정적인 마이그레이션 프로세스를 보장한다.
<br />
<br />

> 47. iOS에서 자동 참조 카운팅(ARC)과 가비지 컬렉션(Garbage Collection)의 차이점에 대해 설명해주세요. <br />

ARC와 가비지 컬렉션은 iOS 애플리케이션에서 메모리 관리를 다루는 두 가지 주요 방식입니다. ARC는 자동 참조 카운팅을 의미하며, 컴파일러가 객체의 참조를 추적해 더 이상 필요하지 않은 객체를 자동으로 해제하는 기술. 앱이 실행 중에 메모리 관리 오버헤드가 발생하지 않도록 하는 장점이 O. 반면에 가비지 컬레션은 런타임에 주기적으로 메모리를 검사해 더 이상 사용되지 않는 객체를 제거한다. 이는 개발자가 객체의 수명을 명시적으로 관리할 필요가 없다는 장점이 있지만, 실행 중인 앱의 성능에 영향을 줄 수 O. 주로 iOS 개발에서는 ARC를 사용하고 있지만, 특정 상황이나 플랫포메 따라 가비지 컬레션도 사용될 수 O.
<br />
<br />

> 48. 가비지 컬렉션의 동작 원리와 장단점에 대해 설명해주세요. <br />

가비지 컬렉션은 메모리 관리를 자동화해 개발자가 메모리를 명시적으로 관리할 필요가 없도록 하는 기술. 일반적으로 가장 많이 사용되는 Mark-and-Sweep 알고리즘을 통해 작동한다. 이 알고리즘은 주기적으로 실행되며, 사용되지 않은 객체를 식별하고 메모리에서 제거한다. 또한, 참조 카운팅과 같은 기능을 결합해 참조횟수가 0인 객체를 해제할 수 도 O.
<br />
가비지 컬렉션의 주요 장점은 개발자가 메모리 관리에 신경 쓸 필요가 없다는 것이다. 이를 통해 개발자는 코드 작성에 집중할 수 있으며, 메모리 누수와 같은 문제를 방지할 수 O. 하지만 가비지 컬렉션은 실행 중인 앱의 성능에 영향을 줄 수 있고, 예측할 수 없는 동작이 있을 수 O. 또한 자원을 소모해 앱의 전반적인 성능을 저하시킬 수 O.
<br />
<br />

> 49. iOS에서 가비지 컬렉션을 사용하지 않는 이유와 ARC를 선택한 배경에 대해 설명해주세요. <br />

iOS에서 가비지 컬렉션을 사용하지 않는 이유는 주로 성능과 예측 가능성의 측면에서 기인한다. 가비지 컬렉션은 메모리 관리를 자동화하는 동시에 실행 스레드를 차단할 수 있고, 메모리 누수를 방지하는 데에도 한계가 있다. 또한 가비지 컬렉션의 작업은 예측할 수 없는 시간에 발생할 수 있어서 앱의 성능을 예측하기 어렵게 만든다. 그래서 iOS 개발에서는 주로 ARC를 선택한다. ARC는 컴파일 타임에 객체의 참조를 추적해 메모리를 관리하므로, 메모리 관리 동작이 예측 가능하고 런타임에 성능에 영향을 미치지 않는다. 또한 ARC를 통해 메모리 누수를 방지할 수 있어 안정성을 높일 수 O.
결국 iOS 애플리케이션은 사용자 경험과 성능에 중점을 두는 경우가 많기 때문에 ARC가 가비지 컬렉션보다 더 적합한 메모리 관리 방식으로 선택된다.
<br />
<br />

> 레벨1
> 1. Swift에서 옵셔널이란 무엇이며, 언제 사용해야 하나요? <br />

옵셔널은 Swift에서 값이 없을 수 있는 변수나 상수를 나타내는 방법. 이는 다른 언어에서의 null, nil, undefined 등과 유사한 개념으로, 값이 없는 상태를 나타낸다. 옵셔널은 Swift에서 안전성과 코드의 명확성을 높이기 위해 사용
* 값을 가져올 때 옵셔널을 해제하고, 값이 없는 경우에 대비해 안전하게 콛를 작성할 수 O.
* 함수의 반환 값이 없을 수 있는 경우, 변수나 상수가 초기화되기 전에 사용될 수 있는 경우, 또는 값이 없는 상황에서의 예기치 않은 동작을 방지하기 위해 옵셔널을 사용한다.
* 옵셔널을 사용하면 컴파일러가 코드를 분석해 값이 없는 상황에서의 잠재적인 오류를 미리 찾아 낼 수 O.
옵셔널을 안전하게 사용하기 위해 옵셔널 체이닝과 옵셔널 해제를 배워야 한다. 옵셔널 체이닝을 총해 옵셔널을 연속적으로 접근할 수 있으며, 이를 통해 값이 있는 경우에만 연산이 수행되도록 할 수 O. 또한, if-let 구문이나 옵셔널 강제 해제 연산자인 ! 등을 사용해 옵셔널 값을 안전하게 가져올 수 O.
<br />
<br />

> 2. 옵셔널 바인딩과 강제 언래핑의 차이점은 무엇인가요? <br />

옵셔널 바인딩은 옵셔널 변수나 상수의 값을 안전하게 가져오기 위한 방법으로, if-let 구문이나 guard 구문을 사용해 옵셔널을 해제하고, 그 결과를 새로운 상수나 변수에 할당한다. 이를 통해 값이 있는 경우에만 코드 블록이 실행되며, 값이 없는 경우에는 else 블록이 실행된다. 변수나 상수의 범위는 if-let 블록 내로 제한된다.
반면 강제 언래핑은 옵셔널 값을 강제로 가져오는 방법으로, 옵셔널 값 뒤에 !를 붙여 사용한다. 이 때, 값이 없는 상태에서 강제 언래핑을 시도하면 런타임 오류가 발생할 수 있으므로 주의가 필요함. 따라서 옵셔널 값이 nil일 가능성이 있는 경우에는 옵셔널 바인딩을 사용해 안전하게 값을 가져오는 것이 좋다.
<br />
<br />

> 3. 옵셔널 체이닝의 동작 원리를 설명해주세요. <br />

옵셔널 체이닝은 옵셔널 값들의 연속적인 접근과 호출을 편리하게 처리하는 방법이다. 이를 통해 중첩된 옵셔널들을 안전하게 다룰 수 O. 옵셔널 체이닝은 옵셔널 값들이 서로 연결되어 있을 때 사용하는 방법으로, 옵셔널 값 뒤에 ?를 붙여 호출한다. 이것은 만약 이 값이 nil이 아니라면 이 메서드나 속성을 호출하고, 그렇지 않으면 전체 표현식을 nil로 평가해라라는 의미. 이롤 통해 중첩된 옵셔널들을 안전하게 다룰 수 O. 만약 중간에 nil이 발견되면 체이닝된 메서드나 속성의 호출은 중지되고 전체 표현식은 nil로 평가된다. 옵셔널 체이닝은 코드를 간결하게 작성할 수 있고, nil을 검사하고 처리하는 코드를 줄일 수 있어 유용하다. 따라서 옵셔널 값들이 서로 연결되어 있을 때 사용하면 좋다.
<br />
<br />

> 4. 암시적 언래핑 옵셔널을 사용하는 경우는 언제인가요?<br />

암시적 언래핑 옵셔널은 주로 세 가지 경우에 사용된다. 암시적 언래핑 옵셔널은 옵셔널이지만 사용될 때 자동으로 해제되어 일반적인 값처럼 사용할 수 있는 형태다. 주로 다음과 같은 경우에 사용된다. 첫째, IBOutlet 또는 IBAction과 같은 인터페이스 요소들은 초기화된 후에는 nil이 될 수 없으므로 암시적 언래핑 옵셔널로 선언된다. 둘째, 클래스의 속성이 초기화 과정에서 nil로 설정되지 않고, 초기화된 이후에 nil이 될 가능성이 거의 없는 경우에 사용된다. 셋째, Optional Chaining으로 인한 불편함을 피하고자 할 때, 특히 값이 nil일 수 있는 가능성이 거의 없는 경우에 암시적 언랲ㅇ 옵셔널을 고려할 수 O. 암시적 언래핑 옵셔널을 사용할 때에는 항상 nil 체크를 해줘야 하며, 이를 통해 런타임 오류를 방지할 수 O. 따라서, 안전한 사용을 위해 옵셔널 바인딩(if-let 또는 guard)을 함께 사용하는 것이 좋다. 
<br />
<br />

> 5. nil 병합 연산자(??)의 사용 예시를 들어주세요. <br />

nil 병함 연산자(??)는 옵셔널 값이 nil인 경우에 대비해 기본값을 제공하는 데 사용됨. 옵셔널 변수나 상수의 값이 nil인 경우에 대비해 기본값을 제공하기 위해 nil 병합 연산자(??)를 사용한다. 예를 들어, optionalName이라는 옵셔널 변수가 있을 때, 이 값이 nil이라면 기본값으로 'Guest'를 사용하고, nil이 아니면 해당 값을 사용한다.
이처럼 nil 병합 연산자를 사용해 옵셔널 값이 nil일 때 대비해 기본값을 제공할 수 O.
<br />
<br />

> 6. iOS 앱의 생명주기(App Life Cycle)에 대해 설명해주세요. <br />

iOS 앱의 생명 주기는 앱이 시작되고 종료될 때까지의 상태 변화를 의미. 주로 앱이 Not Running 상태에서 시작해 Active, Inactive, Background, Suspended 상태로 전환된다. 앱이 시작되면 Not Running 상태에서 Active 상태로 전환된다. 이때 앱이 화면에 나타나고 사용자의 상호작용을 받을 수 O. 사용자가 앱을 홈 버튼으로 나가거나 다른 앱으로 전환되면, 앱은 Inactive 상태로 전환되며, 이때는 이벤트를 받지 않은 상태. 백그라운드로 전환될 때는 Background 상태로 이동한다. 이 상태에서는 앱이 화면에는 표시되지 않지만 백그라운드에서 실행되는 작업들을 처리할 수 O. 예를 들어, 음악 앱은 백그라운드에서 음악을 계속 재생할 수 O. 마지막으로 앱이 종료되거나 시스템이 자원을 관리하기 위해 일시 중단될 때는 Suspended 상태로 전환된다. 이떄는 앱이 메모리에 남아 있지만 실행이 중단되며, 다시 실행될 때 이전 상태에서 이어서 작업을 수행할 수 O. 앱의 생명주기를 이해하면 사용자 경험을 개선하고 앱의 성능을 최적화하는데 도움이 된다.
<br />
<br />

> 7. 앱의 각 상태(Not Running, Inactive, Active, Background, Suspended)에서 할 수 있는 작업은 무엇인가요? <br />

1. Not Running: 앱이 실행되지 않은 상태. 이 상태에서는 아무런 작업도 수행할 수 X. 사용자가 앱을 실행하지 않았거나 시스템이 앱을 종료한 경우
2. Inactive: 앱이 실행 중이지만 이벤트를 받지 않고 있는 상태. 주로 앱이 화면 전환 중이거나 다른 이벤트를 처리하는 동안에 있다. 사용자의 입력을 받지 않으므로 주로 대기 상태에 있다. 
3. Active: 앱이 화면에 표시되고 사용자의 이벤트를 수신하고 있는 상태. 이 상태에서는 앱이 사용자와 상호작용하고 있으며, 사용자 입력에 따라 작업을 수행한다. 예를 들어, 화면을 탭하거나 버튼을 클릭하는 등의 작업이 가능.
4. Background: 앱이 백그라운드에서 실행되고 있지만, 화면에는 표시되지 않는 상태. 이 상태에서는 주로 백그라운드 작업을 수해한다. 예를 들어, 음악 재생, 위치 추적, 네트워크 작업 등이 백그라운드에서 실행될 수 O.
5. Suspended: 앱이 백그라운드에 있지만 실행이 일시 중단된 상태. 시스템이 자원을 관리하기 위해 앱을 일시 중단할 수 O. 이 상태에서는 앱이 메모리에는 남아 있지만 코드가 실행되지 X. 사용자가 다시 앱을 실행하면 이전 상태에서 계속된다.
<br />
<br />

> 8. 앱 상태 변화에 따라 호출되는 AppDelegate 메서드들을 나열해주세요. <br />

1. 앱이 시작될 때:
   * application(_ : willFinishLaunchingWithOptions:): 앱이 실행되고 초기화가 완료되기 직전에 호출된다. 이 시점에서의 앱의 상태는 Not Running
   * application(_ : didFinishLaunchingWithOptions:): 앱이 실행되고 초기화가 완료된 후에 호출된다. 이 시점에서 앱의 상태는 Active
2. 앱이 포그라운드로 전환될 때:
   * applicationWillEnterForeground(_ :): 앱이 포그라운드로 전환되기 직전에 호출된다. 이 시점에서 앱의 상태는 Inactive or Background.
   * applicationDidBecomeActive(_ :): 앱이 포그라운드로 전환된 후에 호출된다. 이 시점에서 앱의 상태는 Background.
3. 앱이 백그라운드로 전환될 때:
   * applicationDidEnterBackground(_ :): 앱이 백그라운드로 전환된 후에 호출된다. 이 시점에서 앱의 상태는 Background.
4. 앱이 종료될 때:
   * applicationWillTerminate(_ :): 앱이 종료되기 직전에 호출된다. 이 시점에서 앱의 상태는 Active 또는 Background. 종료되는 이유가 시스템이나 사용자에 의한 것인지에 따라 달라짐
5. 앱이 일시 중단될 때:
   * applicationDidEnterBackground(_ :): 앱이 백그라운드로 전환될 때 호출되며, 이때 앱의 상태가 Suspended로 변할 때도 호출된다. Suspended 상태로 진입하 때 앱이 백그라운드에서 실행되는 마지막 코드를 처리할 수 O.
<br />
<br />

> 9. 백그라운드에서 작업을 완료하기 위한 방법들은 무엇이 있나요? <br />

1. Background Modes 설정: iOS 앱은 백그라운드에서 실행되는 여러 가지 작업을 처리하기 위한 다양한 Background Modes를 설정할 수 O. 예를 들어, 음악 재생, 위치 업데이트, 백그라운드에서 데이터 수신 등의 작업을 처리할 수 O. 이를 위해 Xcode의 프로젝트 설정에서 Background Modes를 활성화하고 필요한 모드를 선택해 설정할 수 O.
2. Background Tasks: 앱이 백그라운드로 전환될 때 실행되는 작업을 완료하기 위해 백그라운드 테스크를 사용할 수 O. 백그라운드 테스크는 beginBackgroundTask(withName: expirationHandler:)메서드를 사용해 시작하고, 작업이 완료한 후에는 endBackgroundTask(_ :)메서드를 호출해 종료한다. 이를 통해 백그라운드에서 지정된 시간 동안 작업을 수행할 수 O.
3. Background App Refresh: 앱이 백그라운드에서 주기적으로 데이터를 업데이트하거나 작업을 수해해야 하는 경우, Background App Refresh를 사용할 수 O. 이를 통해 iOS는 앱을 백그라운드에서 주기적으로 실행해 필요한 작업을 수행할 수 O. Background App Refresh를 활성화 하려면 Info.plist 파일에 UIBackgroundModes 키에 fetch 값을 추가
4. Background URLSession: 네트워크 작업을 백그라운드에서 처리해야 하는 경우, Background URLSession을 사용할 수 O. 이를 통해 백그라운드에서 네트워크 요청을 보내고 데이터를 다운로드할 수 O. 백그라운드 URLSession은 앱의 Background Modes 설정에서 Background Fetch 또는 Background Processing을 활성화해야 함
5. 로컬 알림 사용: 백그라운드에서 작업을 완료하기 위한 다른 방법으로는 로컬 알림을 사용하는 것. 작업이 완료되면 앱이 백그라운드에서 사용저에게 알림을 보내 작업을 완료했음을 알릴 수 O.
<br />
<br />

> 10. Storyboard와 XIB의 차이점은 무엇인가요? <br />

1. Storyboard:
   * 여러 개의 View Controllers를 하나의 파일에 통합해 관리한다.
   * 여러 화면 간의 이동과 전환을 시각적으로 표현할 수 O.
   * 특정 화면 간의 전환 및 연결을 시각적으로 구성할 수 있어서 앱의 흐름을 파악하기 쉽다.
   * 앱의 전채적인 구조를 한눈에 파악할 수 있어서 대규모 프로젝트에서 효과적이다.  
2. XIB(XML Interface Builder):
   * 단일한 View나 View Controller의 인터페이스를 설계하고 관리한다.
   * 개별 화면에 대한 디자인과 레이아웃을 구성하는 데 사용된다.
   * 보다 모듈화된 구조로 코드를 유지할 수 O. 하나의 XIB 파일은 하나의 View나 ViewController에 대응되므로, 작은 단위로 화면을 관리하기 용이하다.
   * 코드에 대한 분리가 더 쉽다. 디자인과 로직이 분리되어 개발과 유지보수를 효율적으로 할 수 O.

Storyboard는 앱의 전체적인 흐름과 여러 화면 간의 관계를 시각적으로 표현하는 데 유용하며, XIB는 개별 화면의 디자인과 레이아웃을 보다 모듈화된 방식으로 관리하는 데 효과적이다.
<br />
<br />

> 11. Storyboard에서 세그(Segue)를 사용하는 이유는 무엇인가요? <br />

1. 시각적 흐름 표현: 세그는 사용자 인터페이스의 전환과 이동을 시각적으로 표현한다. 이는 앱의 전반적인 흐름을 이해하는 데 도움이 된다. 시각적인 인터페이스를 통해 개발자는 각 화면 간의 관계를 더 명확하게 파악할 수 O.
2. 간편한 연결: Storyboard에서 세그를 사용하면 View Controller 간의 전환 및 연결을 손쉽게 구성할 수 O. 드래그 앤 드롭 또는 인터페이스 빌더의 시각적 요소를 사용해 연결을 설정할 수 있어서 개발 과정을 간소화한다.
3. 인터페이스 빌더와 코드의 분리: 세그를 사용하면 화면 전환에 필요한 코드를 직접 작성할 필요가 X. 대신, 시각적으로 연결을 설정하고 세그의 유형을 정의해 빠르게 작업할 수 O. 이는 인터페이스 디자인과 로직을 분리해 유지 보수와 협업을 요이하게 한다.
4. 애니베이션 및 전환 제어: 세그를 사용하면 화면 전환 시 애니메이션과 전환 방식을 간편하게 구성할 수 O. 인터페이스 빌더에서 세그의 속성을 설정해 애니메이션 효과를 추가하거나 전환 스타일을 변경할 수 O.

세그를 사용하면 Storyboard에서 화면 간의 전환과 연결을 시각적으로 구성하고, 코드와 인터페이스를 분리해 개발 및 유지 보수를 간소화할 수 O.
<br />
<br />

> 12. Storyboard 참조(Storyboard Reference)의 장점은 무엇인가요? <br />

Storyboard 참조는 앱의 인터페이스를 논리적으로 모듈화하고 재사용 가능한 단위로 분할하는 데 도움이 된다. 이를 통해 앱을 작은 부분으로 나눠 개발 및 유지 보수를 용이하게 할 수 O. 예를 들어, 큰 규모의 앱에서는 하나의 거대한 Storyboard 파일을 관리하기 어려울 수 있지만, Storyboard 참조를 사용하면 작은 단위의 파일로 분할해 각 화면 또는 기능을 개별적으로 관리할 수 O. 또한, Storyboard 참조는 성능 개선에도 도움이 된다. 앱의 크기가 커지만 하나의 거대한 파일을 로드하는 데 시간이 오래 걸릴 수 있지만, Storyboard 참조를 사용하면 필요한 모듈만 로드해 성능을 향상시킬 수 O. 또한, 각각의 모듈을 별도의 파일로 분리하면 테스트가 용이해진다. 특정 화면 또는 기능을 개별적으로 테스트할 수 있으며, 이는 앱의 품질을 향상시키는 데 도움이 된다. 마지막으로, Storyboard 참조는 개발자 간 협업을 촉진한다. 각각의 모듈이 별도의 파일로 분리되어 있으며, 여러 개발자가 동시에 다른 모듈에 작업할 수 O. 이는 개발 프로세스를 효율적으로 만들어준다.
<br />
<br />

> 13. 뷰를 구현할때 Storyboard와 Code로 구현하는 각각의 장단점은 무엇인가요? <br />

뷰를 구현하는 데 Storyboard와 코드 모두 장단점이 있다. Storyboard를 사용하면 시각적으로 레이아웃을 디자인하고 빠르게 프로토타입을 제작할 수 O. 또한 시각적으로 화면 간의 흐름을 파악하기 쉽고, 간단한 애니메이션 효과를 추가하기도 용이하다. 하지만 큰 규모의 프로젝트에서는 Storyboard 파일이 복잡해지면 관리가 어려워질 수 있고, 협업 시 충돌이 발생할 수 O. 반면에 코드로 뷰를 구현하면 유연성이 높아져 동적으로 UI를 생성하고 수정할 수 O. 또한, 복잡한 레이아웃을 관리하기 쉽고, 협업 시 충돌이 발생할 가능성이 적다. 하지만 초기 프로토타입 제작이 시각적으로 어려울 수 있고, 애니메이션 구현이 조금 더 복잡할 수 O.
<br />
<br />

> 14. Auto Layout을 사용하는 이유와 장점은 무엇인가요? <br />

1. 다양한 디바이스 지원: Auto Layout을 사용하면 앱이 다양한 디바이스 크기와 화면 방향에 적응할 수 O. 이는 iPhone과 iPad를 포함한 여러 iOS 디바이스 및 macOS에서 앱을 실행할 때 중요하다
2. 유연한 UI 구축: Auto Layout은 제약 조건을 사용해 UI 요소의 크기, 위치 및 간격을 정의한다. 이를 통해 UI 요소들 간의 관계를 유연하게 설정할 수 있어 UI의 유동적인 변화에 대응할 수 O.
3. 다국어 및 글꼴 크기 지원: Auto Layout은 다국어 및 글꼴 크기 변경과 같은 동적인 변화에 대응할 수 O. 이는 앱이 여러 언어로 번역되거나 사용자가 글꼴 크기를 조정할 때 UI가 깨지지 않고 적절하게 조정되도록 한다.
4. 인터페이스 빌더 통함: Xcode의 Interface Builder를 통해 Auto Layout을 시각적으로 구성할 수 O. 제약 조건을 시각적으로 추가하고 조정해 UI를 만들 수 있으며, 실시간으로 변경 사항을 확인할 수 O.
5. 코드와의 통함: Auto Layout은 코드로도 구현할 수 O. 프로그래밍 방식으로 제약 조건을 추가하고 수정해 동적인 UI를 구현할 수 O. 이는 특정 상황에 따라 UI를 프로그래밍적으로 조작해야 할 때 유용
<br />
<br />

> 15. 제약 조건(Constraints)의 우선순위(Priority)는 어떤 역할을 하나요? <br />

제약 조건의 우선 순위는 Auto Layout 시스템에서 각 제약 조건의 중요도를 나타내는 값. 이 우선 순위는 제약 조건이 충돌할 때 시스템이 어떻게 해결해야 하는지 결정하는 데 사용
우선순위 값은 1~1000까지의 범위에서 설정할 수 있으며, 기본적으로 1000이 가장 높은 우선순위를 가진다.
1. 충돌 해결: 여러 제약 조건이 동시에 충돌할 경우, 시스템은 우선순위에 따라 어떤 제약 조건을 우선해 적용할지 결정
2. 유연성 제어: 우선순위를 조정해 UI 요소의 동작을 제어할 수 O. 예를 들어, 특정 상황에서 UI 요소가 더 많은 공간을 차지하도록 하거나, 반대로 다른 UI 요소에 우선권을 부여할 수 O.
3. 동적인 UI 구성: 우선순위를 프로그래밍적으로 변경해 동적인 UI 구성을 가능하게 한다. 특정 이벤트나 조건에 따라 제약 조건의 우선순위를 조정해 UI를 동적으로 조작할 수 O.
4. 사용자 경험 개선: 우선순위를 조절해 사용자 경험을 개선할 수 O. 예를 들어, 특정 디바이스에서 UI요소가 더 잘 표시되도록 우선순위를 조정할 수 O.
<br />
<br />

> 16. 스택 뷰(Stack View)의 속성들을 설명해주세요. <br />

스택 뷰는 iOS 및 macOS 앱에서 UI를 구성하는 데 사용되는 유용한 컨테이너 뷰. 주요 속성으로는 축(axis), 정렬(alignment), 분배(distribution), 간격(spacing), 레이아웃 여백(layout margins)등이 있다. 축은 하위 뷰들이 배치되는 방향을 결정하며, 정렬은 하위 뷰들의 정렬 방법을 설정한다. 분배는 하위 뷰들의 크기를 어떻게 분배할지를 결정하며, 간격은 하위 뷰둘 사이에 간격을 설정한다. 레이아웃 여백은 스택 뷰와 하위 뷰들 간의 여백을 지정한다. 이러한 속성들을 조절해 스택 뷰를 사용하면 유연하고 반응형인 UI를 간편하게 구성할 수 O.
<br />
<br />

> 17. 인터페이스 빌더에서 제약 조건 충돌을 해결하는 방법은 무엇인가요? <br />

1. 제약 조건 검토: 먼저, 충돌이 발생하는 뷰나 제약 조건을 확인, 각 뷰의 제약 조건이 예상대로 설정되어 있는지, 충돌이 발생하는지를 확인
2. 우선순위 조정: 충돌이 발생하는 경우, 각 제약 조건의 우선순위를 조정해 충돌을 해결할 수 O. 충돌이 있는 제약 조건을 선택하고 우선순위를 낮추거나 높려서 다른 제약 조건보다 우선되도록 조정할 수 O.
3. 간격 조정: 제약 조건의 간격을 조정해 충돌을 해결할 수 O. 뷰의 간격을 더 넓게 또는 좁게 설정해 충돌을 해결할 수 O.
4. 스택 뷰 사용: 스택 뷰를 사용해 복잡한 레이아웃을 구성할 수 O. 스택 뷰는 하위 뷰들을 자동으로 배치하고 제약 조건을 관리해주므로 충돌을 줄일 수 O.
5. 비활성화 또는 제거: 충돌을 일으키는 특정 제약 조건을 비활성화하거나 제거해 충돌을 해결할 수도 O. 하지만 이 경우에는 UI의 레이아웃이 변경될 수 있으므로 주의가 필요.
6. 외부 요인 고려: UI의 크기나 위치를 결정하는 외부 요인을 고려해 제약 조건을 수정할 수 O. 예를 들어, 디바이스의 크기나 회전에 따라 뷰의 크기와 위치를 조절하는 추가 제약 조건을 추가할 수 O.
<br />
<br />

> 18. Swift에서 클로저(Closure)란 무엇이며, 어떻게 사용하나요? <br />

클로저는 Swift에서 사용되는 코드 블럭으로, 일급 객체로서 함수와 비슷한 역할을 합니다. {}로 둘러싸인 코드 불럭으로, 매개변수와 반환 타입을 가지며, 함수와 마찬가지로 다른 함수의 매개변수로 전달되거나 함수의 반환 값으로 사용될 수 O. 예를 들어, 배열을 정렬하는 sorted(by:) 함수에 클로저를 전달하여 정렬 기준을 지정할 수 O. 또한 비동기 작업의 완료 핸들러로 사용되거나 간다난 코드 블럭을 실행하는 용도로도 자주 사용된다. 클로저는 주변 범위의 변수나 상수를 캡쳐해 사용할 수 있어, 주변 상태를 기억하고 활용할 수 O.
<br />
<br />

> 19. 클로저의 캡처 리스트(Capture List)는 어떤 역할을 하나요? <br />

클로저의 캡처 리스트는 클로저가 주변 범위의 변수나 상수를 캡쳐하는 방법을 지정하는데 사용된다. 클로저가 주변 범위의 변수나 상수를 캡처하면 해당 값이 클로저 내에서 보존되며, 클로저가 사용될 때마다 해당 값에 접근할 수 O. 캡처 리스트는 클로저의 매개변수와 반환 타입 사이에 위치하며, 주로 []로 둘러싸여 있다. 캡처 리스트에 주로 [weak self]나 [unowned self]와 같은 키워드를 사용해 강한 참조 순환을 방지하는 데 사용된다. 또한 캡처된 변수나 상수에 별칭(aliasing)을 설정해 클로저 내부에서 더 의미있는 이름을 사용할 수도 O.
<br />
<br />

> 20. @escaping 클로저와 non-escaping 클로저의 차이점은 무엇인가요? <br />

@escaping과 non-escaping 클로저는 클로저가 어떻게 사용되는지에 따라 차이가 있다.
1. @escaping 클로저:
   * @escaping 클로저는 함수의 범위를 벗어나서 저장되거나 다른 함수의 매개변수로 전달되는 경우를 말한다.
   * 함수 내부에서 비동기적으로 실행되거나, 함수 실행 후 저장되어 나중에 호출될 때 @escaping 클로저를 사용해야 한다.
   * 클로저가 함수의 범위를 벗어나므로 클로저 내부에서 함수 외부의 변수나 상수를 캡처할 떄는 명시적으로 self를 사용해 참조해야 한다.
2. non-escaping 클로저:
   * non-escaping 클로저는 함수 내부에서 사용되고 함수의 실행이 종료되면 함께 종룔되는 클로저를 말한다.
   * 함수 내부에서 동기적으로 실행되거나, 함수의 범위 내에서만 사용되는 경우에 non-escaping 클로저를 사용한다.
   * non-escaping 클로저는 함수의 범위를 벗어나 저장되거나 다른 함수의 매개변수로 전달되지 안으므로, 클로저 내부에서 self를 명시적으로 사용할 필요가 X.
  간단한 예시로 설명하자면, 비동기적으로 실행되는 클로저는 @escaping으로 선언되어야 하며, 함수의 범위를 벗어나 저장되거나 다른 함수의 매개변수로 전달된다. 그에 반해, 함수의 실행이 종료되면 함께 종료되는 동기적으로 실행되는 클로저는 non-escaping으로 선언된다.
<br />
<br />

> 21. 트레일링 클로저(Trailing Closure) 문법은 언제 사용하면 좋나요? <br />

트레일링 클로저 문법은 함수의 마지막 매개변수로 전달되는 클로저를 함수 호출의 괄호 밖에 작성하는 문법. 이 문법을 사용하면 함수 호출이 클로저와 인접하게 위치해 코드의 가독성을 향상시킬 수 O. 특히 클로저가 길거나 여러 줄에 걸쳐 복잡한 연산을 수행하는 경우에 유용.
<br />
<br />

> 22. iOS에서 델리게이트 패턴(Delegate Pattern)은 어떤 목적으로 사용되나요? <br />

델리게이트 패턴은 iOS 애플리케이션 개발에서 자주 사용되는 디자인 패턴 중 하나로, 객체 간의 통신과 이벤트 처리를 위해 사용된다. 주요 목적은
1. 객체 간의 느슨한 결합: 델리게이트 패턴을 사용하면 객체 간의 강한 의존성을 줄일 수 O. 한 객체가 다른 객체의 기능을 직접 호출하는 대신, 델리게이트를 통해 다른 객체에게 특정 작업을 위임함으로써 두 객체 사이의 결합도를 낮출 수 O.
2. 이벤트 처리 및 콜백: 델리게이트 패턴을 사용해 객체가 발생시키는 이벤트를 다른 객체에게 알리고 처리할 수 O. 이를 통해 비동기적인 작업의 완료나 사용자의 상호작용과 같은 이벤트를 쉽게 처리할 수 O.
3. 다중 상속 대체: iOS에서는 다중 상속이 지원되지 X. 델리게이트 패턴을 사용하면 다른 객체의 기능을 쉽게 확장하고 재사용할 수 O. 즉, 클래스가 하나의 다른 클래스를 상속하는 대신, 여러 클래스의 기능을 델리게이트를 통해 사용할 수 O.
4. 코드 재사용과 모듈화: 델리게이트 패턴을 사용하면 기능을 더 작고 독립적인 단위로 분리할 수 O. 이를 통해 코드의 재사용성을 높이고 각 모듈을 더 쉽게 관리할 수 O.
<br />
델리게이트 패턴은 iOS 애플리케이션 개발에서 MVC(Model-View-Controller) 아키텍처를 구현하거나, UITableView와 UICollectionView와 같은 UI 컴포넌트의 데이터 소스 및 델리게이트를 구현할 때 주로 사용.
<br />
<br />

> 23. 델리게이트 패턴과 콜백 함수의 차이점은 무엇인가요? <br />

1. 구현방식:
   * 델리게이트 패턴: 델리게이트 패턴은 객체 간의 상호 작용을 위해 인터페이스(또는 프로토콜)를 정의하고, 해당 인터페이스를 준수하는 객체를 델리게이트로 지정한다. 이후 델리게이트 객체가 특정 이벤트가 발생하거나 작업이 완료되었음을 알리면, 이벤트를 처리하거나 작업 결과를 전달하기 위해 델리게이트 객체의 메서드를 호출한다.
   * 콜백함수: 콜백 함수는 함수의 매개변수로 다른 함수를 전달해, 특정 이벤트가 발생하거나 작업이 완료되었을 때 호출되도록 한다. 일반적으로 비동기적인 작업이나 이벤트 기반 프로그래밍에서 많이 사용됨 
2. 사용 방법:
   * 델리게이트 패턴: 델리게이트 패턴은 보통 객체간의 상호 작용을 위해 사용된다. 객체가 특정 이벤트를 처리하거나 다른 객체와의 통신을 위해 델리게이트를 사용
   * 콜백 함수: 콜백 함수는 주로 비동기적인 작업의 완료를 처리하거나 이벤트를 처리하기 위해 사용된다. 비동기 작업이나 이벤트가 발생할 때마다 미리 정의된 콜백 함수가 호출된다.
3. 상호작용 방식:
   * 델리게이트 패턴: 델리게이트 패턴은 객체 간의 상호작용을 위해 델리게이트 객체를 통해 메시지를 전달하고, 해당 메시지에 대한 응답을 받는다. 델리게이트 객체는 델리게이트 프로토콜을 준수헤 필요한 동작을 구현한다.
   * 콜백 함수: 콜백 함수는 보통 함수의 매개변수로 전달되어, 특정 이벤트가 발생하거나 작업이 완료될 때 호출된다. 콜백 함수는 비동기적으로 실행되며, 이멘트가 발생할 때마다 호출된다.
<br />
<br />

> 24. 델리게이트 패턴과 옵저버 패턴의 차이점은 무엇이고 각각 어떨때 사용하면 좋나요? <br />

1. 차이점:
   * 델리게이트 패턴: 델리게이트 패턴은 객체 간의 일대일 관계를 가지며, 하나의 객체가 다른 객체에게 특정 작업을 위임함. 델리게이트 객체는 델리게이트 프로토콜을 준수하여 필요한 동작을 구현하고, 델리게이트하는 객체에게 해당 동작을 실행하도록 요청함. 따라서 델리게이트 패턴은 주로 한 객체가 다른 객체의 동작을 커스터마이징하거나 확장할 때 사용.
   * 옵저버 패턴: 옵저버 패턴은 일대다 관계를 가지며, 하나의 객체(주체, Subject)의 상태 변화를 감지하고 이를 관찰하는 다수의 객체(옵저버, Observer)에게 알림. 옵저버 객체들은 주체 객체의 상태 변화를 감지하고 필요한 동작을 수행. 따라서 옵저버 패턴은 주체 객체의 상태 변화를 여러 객체에게 알리고, 해당 상태 변화에 대한 처리를 분산하여 관리할 때 사용.
2. 사용 시기:
   * 델리게이트 패턴: 한 객체가 다른 객체의 동작을 커스터마이징하거나 확장할 때, 또는 객체 간의 결합도를 낮추고 상호 작용을 유연하게 구현할 때 델리게이트 패턴을 사용. 예를 들어, UITableView의 데이터 소스 및 델리게이트 패턴은 각 셀의 모양과 동작을 커스터마이징하고, 테이블 뷰와 컨트롤러 간의 결합도를 낮춘다.
   * 옵저버 패턴: 객체의 상태 변화를 감지하고 이를 여러 객체에게 알리고 싶을 때, 또는 주체 객체와 관찰자 객체 간의 결합도를 낮추고 상호 작용을 유연하게 구현할 때 옵저버 패턴을 사용. 예를 들어, NotificationCenter를 사용하여 여러 객체가 특정 이벤트를 관찰하고, 이벤트가 발생할 때마다 알림을 받는 경우가 옵저버 패턴의 대표적인 예시.
<br />
델리게이트 패턴은 일대일 관계를 가지고 서로 다른 객체 간의 상호 작용을 할 때 사용되고, 옵저버 패턴은 일대다 관계를 가지고 한 객체의 상태 변화를 여러 객체에게 알릴 때 사용됩니다.
<br />
<br />

> 25. 델리게이트 메서드에서 반환값을 사용하는 경우는 언제인가요? <br />

1. 결과 반환: 델리게이트 메서드가 호출되었을 때 처리된 결과를 반환해야 할 때 사용. 예를 들어, 뷰 컨트롤러가 특정 이벤트에 대한 처리 결과를 델리게이트 객체에게 요청하고, 이 결과를 사용하여 다음 동작을 결정하는 경우가 O.
2. 조건 확인: 델리게이트 메서드가 호출되었을 때 특정 조건을 확인하고 이에 따른 동작을 수행해야 할 때 사용. 델리게이트 메서드에서 반환값을 사용하여 조건을 확인하고 이에 따른 분기 처리를 수행할 수 O.
3. 데이터 요청: 델리게이트 객체가 데이터를 요청하고 해당 데이터를 반환받아야 할 때 사용. 예를 들어, 테이블 뷰의 데이터 소스 델리게이트는 셀에 표시할 데이터를 요청하고 반환값으로 데이터를 전달받아야 함
4. 유효성 검사: 델리게이트 메서드가 호출되었을 때 인자나 조건의 유효성을 검사하고, 이에 따라 처리할지 말지를 결정해야 할 때 사용.반환값을 사용하여 유효성을 검사하고 적절한 처리를 수행할 수 O.
<br />
<br />

> 26. Swift의 기본 데이터 타입에는 어떤 것들이 있나요? <br />

1. 정수형 타입(Integer Types):
   * Int: 플랫폼의 기본 정수형 타입
   * UInt: 부호 없는 정수형 타입으로, 양수만 표현함
   * Int8, Int16, Int32, Int64: 각각의 8비트, 16비트, 32비트, 64비트 부호있는 정수형 타입
   * UInt8, UInt16, UInt32, UInt64: 각각의 8비트, 16비트, 32비트, 64비트 부호없는 정수형 타입
2. 부동소수점 타입(Floating-Point Types):
   * Float: 32비트 부동소수점 타입
   * Double: 64비트 부동소수점 타입으로, 더 넓은 범위와 정밀도를 제공
3. 부울 타입(Bool Type):
   * Bool: 참(true) 또는 거짓(false)값을 가지는 부울 타입
4. 문자 타입(Character Type):
   * Character: 유니코드 문자를 나타내는 타입
5. 문자열 타입(String Type):
   * String: 유니코드 문자의 컬렉션을 나타내는 타입
6. 옵셔널(Optional Type):
   * Optional<Wrapped>: 값이 있을 수도 있고 없을 수도 있는 값을 나타내는 타입으로, nil을 포함할 수 O. 일반적으로 ?를 사용해 선언
<br />
<br />

> 27. 값 타입(Value Type)과 참조 타입(Reference Type)의 차이점을 설명해주세요. <br />

값 타입은 데이터를 복사해 전달하고 독립적으로 다루는 반면, 참조 타입은 실제 데이터의 참조를 전달해 여러 곳에서 공유하고 변경할 수 O. 값 타입은 구조체와 열거형을 통해 구현되며, 참조 타입은 클래스를 통해 구현됨
<br />
<br />

> 28. 구조체(Struct)와 클래스(Class)는 어떤 차이가 있나요? <br />

구조체와 클래스는 Swift에서 데이터를 모델링하고 관리하는 데 사용되는 두 가지 주요 타입. 구조체는 값 타입이며 데이터를 복사해 전달하고 스택에 할당된다. 이에 반해, 클래스는 참조 타입이며, 데이터를 참조해 전달하고 힙에 할당된다. 클래스는 상속을 지원하며 다중 프로토콜 준수를 할 수 O. 또한 클래스는 더욱 유연한 초기화 및 메모리 관리를 제고한다. 간단히 말해, 구조체는 간단한 데이터 유형을 모델링하고 불변성을 유지할 때 유용하며, 클래스는 복잡한 객체와 상속 계층을 관리할 때 유용
<br />
<br />

> 29. 열거형(Enum)의 원시값(Raw Value)과 연관값(Associated Value)은 무엇인가요? <br />

열거형은 Swift에서 관련된 값을 그룹화하고 정의하는 데 사용되는 타입. 열거형에는 두 가지 유형의 값이 O. 첫째는 원시값(Raw Value)으로, 열거형 케이스마다 고정된 값을 가지며 초기화할 때 사용됨. 둘쨰는 연관값(Associated Value)으로, 각 케이스마다 다른 타입의 값을 가지며 케이스와 관련된 데이터를 저장하고 전달할 수 O. 원시값은 모든 케이스에 대해 동일한 타입을 가지지만 연관값은 각 케이스마다 다른 타입을 가질 수 O.
<br />
<br />

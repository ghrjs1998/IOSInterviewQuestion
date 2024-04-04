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

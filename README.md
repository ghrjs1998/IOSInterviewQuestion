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

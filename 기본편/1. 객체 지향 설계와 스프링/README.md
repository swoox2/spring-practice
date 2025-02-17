### 스프링이란?

스프링은 자바 플랫폼을 위한 오픈 소스 애플리케이션 프레임워크이다. 스프링의 주요 특징은 다음과 같다.
- DI (Dependency Injection): 객체 간의 의존 관계를 외부에서 주입하여 결합도를 낮추고 테스트 용이성을 향상시킨다.
- IoC (Inversion of Control): 객체의 생명주기와 의존관계를 프레임워크가 관리하도록 하는 개념이고, 이를 통해 개발자는 객체간의 결함을 줄이고 유연한 구조를 만들 수 있다.
- AOP (Aspect-Oriented Programming): 로깅, 보안 등을 모듈화하여 비즈니스 로직과 분리하여 코드의 유지보수성을 높인다.
- MVC 아키텍처 : 웹 애플리케이션을 구성하는 모델, 뷰, 컨트롤러를 역할에 따라 분리하여 구조적인 개발을 지원한다.
- 트랜잭션 관리: 데이터베이스 트랜잭션을 쉽게 관리하며, 선언적으로 트랜잭션을 관리할 수 있다.
- 데이터 접근 통합: JDBC, JPA, Hibernate 등을 통합하여 일관된 데이터 접근 계층을 제공한다.
- 모듈화와 확장성: 필요한 기능만 선택적으로 사용할 수 있고, 다양한 서드파티 라이브러리와의 통합이 용이하다.

#### 스프링의 진짜 핵심
- 스프링은 객체 지향 언어가 가진 강력한 특징을 살려내는 프레임 워크
- 스프링은 좋은 객체 지향 애플리케이션을 개발할 수 있게 도와주는 프레임워크
<br></br>

### 객체지향 프로그래밍이란?

현실 세계의 사물과 같은 객체를 만들고, 그 객체에 필요한 특징을 뽑아내서 프로그래밍을 수행하는 것을 말한다.
- 캡슐화: 객체의 데이터와 메서드를 하나로 묶고 외부에서 접근을 제어하는 것을 말한다. 이를 통해 객체의 내부 구현을 숨기고 외부에는 인터페이스만 노출시킨다.
- 상속: 부모 클래스의 속성과 메서드를 자식 클래스가 물려받아 재사용할 수 있는 기능이다. 상속을 통해 코드의 중복을 줄이고 확장성을 높일 수 있다.
- 다형성: 동일한 메소드의 호출이 다양한 객체에서 다르게 동작하도록 하는 기능이다. 메서드 오버라이딩과 오버로딩을 통해 구현된다.
- 추상화: 복잡한 시스템에서 중요한 부분을 추출하여 단순화하는 과정이다. 클래스나 객체를 만들 때 필요한 특성을 강조하고 불필요한 세부 사항을 숨기는 것을 의미한다.
<br></br>

### 스프링과 객체 지향
- 다형성이 가장 중요하다!
- 스프링은 다형성을 극대화해서 이용할 수 있게 도와준다.
- 스프링에서 이야기하는 제어의역전(IoC), 의존관계 주입(DI)은 다형성을 활용해서 역할과 구현을 편리하게 다룰 수 있도록 지원한다.
- 스프링을 사용하면 마치 레고 블럭 조립하듯이 구현을 편리하게 변경할 수 있다.
<br></br>

### 좋은 객체 지향 설계의 5가지 원칙(SOLID)
- SRP(단일 책임 원칙)
  - 한 클래스는 하나의 책임만 가져야 한다.
  - 중요한 기준은 변경이다. 변경이 있을 때 파급 효과가 적으면 단일 책임 원칙을 잘 따른 것
- OCP(개방-폐쇄 원칙)
  - 소프트웨어 요소는 확장에는 열려 있으나 변경에는 닫혀 있어야 한다.
- LSP(리스코프 치환 원칙)
  - 프로그램의 객체는 프로그램의 정확성을 깨뜨리지 않으면서 하위 타입의 인스턴스로 바꿀수 있어야 한다.
  - 다형성에서는 하위 클래스는 인터페이스 규약을 다 지켜야 한다는 것, 다형성을 지원하기 위한 원칙, 인터페이스를 구현한 구현체는 믿고 사용하려면 이 원칙이 필요하다.
- ISP(인터페이스 분리 원칙)
  - 특정 클라이언트를 위한 인터페이스 여러 개가 범용 인터페이스 하나보다 낫다.
- DIP (의존관계 역전 원칙) 
  - 구현 클래스에 의존하지 않고, 인터페이스에 의존해야 한다.
  


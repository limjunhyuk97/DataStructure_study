# 기본개념

## 1. 시스템 생명 주기 (System Life Cycle)
  - 요구사항 분석 : 문제점 분석, 목표 파악 -> 문제단위 분해 -> 추상적인 데이터타입을 설정 -> 그에 맞는 알고리즘 기법 고려 -> 구체적 구현
  - 구체적인 구현은, 후에 여러가지 언어를 통해서 구현할 수 있도록 보류한다.
  
## 2. 객체지향적 프로그래밍
  - **객체의 정의**
    - 객체는 데이터와 절차적 요소의 결합이다.
  - **객체 지향 프로그래밍(object-oriented-programming)구현의 정의**
    - 객체가 기본 구성단위(building block)이다.
    - 각 객체는 어떤 타입, 또는 클래스의 인스턴스(instance) 이다.
    - 클래스는 상속에 의해서 연관되어 있다. (상속을 사용해야 객체지향적 프로그래밍이다.)
  - **객체 지향 언어(object-oriented-language)의 정의**
    - 객체를 지원한다.
    - 모든 객체는 class에 속한다.
    - 상속을 지원한다.
      - 상속을 지원하지 않는 언어는 객체 기반 언어(object-based-language)라고 한다. : 예) JavaScript 언어
  - **데이터 추상화의 정의**
    - 데이터 객체의 명세(specification, 무엇, 기능)와 구현(implementation, 어떻게, 방법)을 구분하는 것이다.
  - **데이터 캡슐화의 정의**
    - 외부세계로부터 데이터 객체의 자세한 구현을 숨기는 것이다.
  - **데이터 추상화, 캡슐화의 이점**
    - 1. 기능(명세) 단위로 분화되어 작업이 가능하므로, 간소화된 개발을 할 수 있다.
    - 2. 디버깅을 통한 버그 검사의 과정이 간소화 된다.
    - 3. 코드 재사용성을 높여준다.
    - 4. 데이터 타입의 내부구현의 변경은 수정의 과정을 간소화 시켜준다.
  - **데이터 타입(data type)의 정의**
    - 데이터 타입은 객체(object)들과 이 객체들에 동작하는 연산(operation)의 집합이다.
  - **추상 데이터 타입(abstract data type)의 정의 / ADT**
    - 추상 데이터 타입은 객체의 명세와 이들 객체에 대한 연산의 명세가 객체의 표현과 연산의 구현으로부터 분리된 방식으로 구성된 데이터 타입이다. 
    - '어떻게'를 통한 기능의 완성에 대해서는 언급하지 않고, '무슨' 기능을 하는지에 대해서만 다루는 것이다.
    
## 3. C++
  - **C++에서의 영역(scope)**
    - file scope
      - 함수 외부에 선언된 선언, class 선언, namespace 선언이 포함되는 영역이다.
      - 다른 file의 전역변수를 가져오려면 extern선언을, 이름이 겹치지만 별개의 개체로서의 전역변수로 사용하려면 static선언을 하면 된다.
    - namespace scope
      - 논리적으로 연관된 변수나 함수를 하나의 그룹으로 묶어주는 영역이다.
      - 이름 선언이 서로 겹치지 않도록 해준다.
      - **변수는 자신의 영역과 이름으로 유일하게 식별된다!**
    - local scope
      - { } 안의 영역이다.
      - { }의 블록 안에 선언된 이름은, 그 블록의 지역영역(local scope)에 속한다.
    - class scope
      - class 안의 영역이다.
  - **C와 C++의  몇가지 차이점**      
    - **연산자 다중화(operatior overloading)**
      - 연산자가 피연산자의 타입에 따라서 상이한 기능을 갖는다.
      - int형에 +를 쓰면 덧셈, string형에 +를 쓰면 문자열 catenation
    - **new 와 delete가 동적할당, 해제 역할을 한다.**
    - **자료 입출력 시에 << >>의 시프트 연산자를 사용한다.**
  - 오류를 잡는 try-catch문.
    
    
    
    
    
    
    
    
    
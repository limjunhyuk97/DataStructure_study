## 누적된 알고리즘
   - 이진탐색 알고리즘, 순차탐색 알고리즘

## 함수의 재귀적 호출
  - 재귀함수는 함수 내에서 자기 자신을 다시 호출하는 함수이다.
  - **완료되지 않은 함수를 다시 불러오는것, 가능하다!!**

## 재귀 함수 디자인
  - **함수의 탈출조건(기저사례)** 을 정의해 두는 것은 매우 중요하다.
  - **반복되는 상태**를 잡아내어 구현하는 것도 매우 중요하다.
    - **수학적 재귀의 상태가 코드로 그대로 옮겨지는 경우에 주목해보자!**
    - 피보나치, 팩토리얼...
  - 초기에 기저사례와 같이 쓸데없는 경우들을 제거하는 것도 하나의 방법이다.
  - 재귀함수의 호출과정을 하나하나 이해하기 보다는, 재귀함수 자체의 구현을 이해하려해보자.

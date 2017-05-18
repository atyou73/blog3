---
layout: post
title: 함수형 사고
author: 닐 포드 (지은이), 김재완 (옮긴이)
tags: book
---

 > 프로그래밍 언어는 개발자와 컴퓨터 간의 인터페이스다

## 1
개인적인 이야기를 좀 하자면, 요즘에 'C#' 관련 책을 자주 사서 보고 있다. 뭐 'C#'을 사용하겠다는 의지는 아니고 C#에 적용된 개념이나 문법 때문이다. C#에서 뭔가 적용되면 다음번 JDK에 반영되는 경우가 많고, C#의 경우 다양한 개념이나 문법이 빠른 속도로 반영되기 때문에 주의해서 모니터링 하고 있다.

## 2
이런 이유는 당연히 내가 사용하고 있는 도구를 좀 더 잘 다루고 싶다는 욕망과 함께 내가 알 수 없는 어떤 개념이 자주 등장하기 때문이다. 최근에 안드로이드 관련해서 스터디를 하면서 다양한 기사를 구경하고 있는데 'RxJava' 등과 같은 형태가 대표적인 예라고 할 수 있다.

## 3
이 책을 통해서 함수형 사고를 배울 수 있다면 좋겠지만, 난 그런 위대한 인물이 못되기 때문에 애초에 포기했다. 대신에 이 책에서 소개하는 함수형 언어에서 사용하는 개념이나 문법적인 표기법등에 집중해서 보았고, 현재 내가 사용하는 언어에 어떻게 반영되어 있는지 천천히 찾아보았다.

## 4
P.S. 배워야 할게 이렇게 많다니....

> 함수형 코드를 작성하기 위해선, 함수형 언어인 스칼라나 클로저로의 전환이 필요한 것이 아니라 문제에 접근하는 방식의 전환이 필요하다.

----

1. > 모든 시스템이 결국은 조합 구성되는 함수들의 모임이기 때문이다. 그래서 기획, 설계, 단계에서의 실착이 프로젝트 전체의 성패를 좌우하는 경우가 줄어들고, 그만큼 기획자, 설계자, 개발자 모두가 좀 더 행복하게 일을 진행할 수 있다.

2. > 객체지향은 1983년에 처음 등장한 C++가 보편화된 후에야 주류가 되었다. 종종 훌륭한 아이디어는 기반이 되는 기술이 쫓아오기를 기다리곤 한다. 자바는 초장기에는 느리고 메모리를 과하게 사용해서 고성능 애플리케이션으로는 적합하지 않다고 여겨졌다. 하지만 하드웨어 시장의 변화로 선호도가 높아졌다.

3. > [...] 한 번의 반복자 블록에서 실행함으로써 성능을 명료함과 맞바꾸었다. 이는 보편화된 트레이드오프지만 나는 별로 권장하고 싶지 않다.

4. > 나 역시 더는 가비지 컬렉션이 없는 언어로 코딩하고 싶지 않다. 이제는 고수준의 추상활르 통해 복잡한 비즈니스 문제를 풀 궁리를 하지, 까다로운 저수준 문제는 더 이상 생각하고 싶지 않다. 자바는 메모리 관리에 관한 어려움을 줄여주었고 나는 이를 향유하고 있다. 나아가 다른 곳에서도 편리한 방법을 모색하게 되었다.

5. > malloc에 시달리기엔 인생은 너무 짧다.

6. > 객체지향 프로그래밍은 움직이는 부분을 캡슐화하여 코드 이해를 돕고, 함수형 프로그래밍은 움직이는 부분을 최소화하여 코드 이해를 돕는다. - 마이클 페더스

7. > 함수 수준의 캡슐화는, 모든 문제에 대한 새로운 클래스 구조를 구축하는 것보다 세분화되고 기초적인 수준에서 재사용을 가능하게 한다.

8. > 절차보다는 결과에 집중하라

9. > 언어 설계자들은 반드시 규칙을 지킬 필요가 없기 때문에 그들이 만든 매커니즘이 항상 더 효율적이다.

10. > 메모아이즈된 함수는 부수효과가 없어야 하고, 외부 정보에 절대로 의존하지 말아야 한다.

# Iterator pattern
반복자 패턴(Iterator pattern)은 객체 지향 프로그래밍에서 반복자를 사용하여 컨테이너를 선회하고 컨테이너 요소에 액세스하는 디자인 패턴이다.

### 상세설명
 - 반복자 패턴은 어떤 문제를 해결할 수 있는가?
   1. 객체 집합의 원소들에 접근할 수 있으며, 자료구조의 노출 없이 순회할 수 있다.
   2. 새로운 순회 동작들은 인터페이스 변화 없이 객채 집합에 대해 정의할 수 있다. 
 - 반복자 패턴은 어떤 솔루션으로 설명되는가?
   1. 객체 집합에 대한 접근과 선회를 캡슐화하는 별도의 객체를 정의한다.
   2. 클라이언트는 자료구조의 정보없이 원소를 접근하고 선회하는데 반복자를 사용한다.
   
### 클래스 설명
 - [2][Iterator.java](https://docs.oracle.com/javase/9/docs/api/java/util/Iterator.html) : 자바가 기본적으로 제공하는 인터페이스
 - [3][Collection.java](https://docs.oracle.com/javase/9/docs/api/java/awt/Container.html) : 자바가 기본적으로 제공하는 인터페이스로, Map, List, Set, Table등의 자료구조를 제공한다. Iterable.java 를 상속한다. 
자바 5에서 Iterable 인터페이스를 구현하는 객체는 자바의 for each 루프 구문을 사용하여 추적 할 수 있다.
    
### 참조:
[1]https://en.wikipedia.org/wiki/Iterator_pattern
[2]https://docs.oracle.com/javase/9/docs/api/java/util/Iterator.html
[3]https://docs.oracle.com/javase/9/docs/api/java/awt/Container.html
# jpaShop
> To learn the web application
----------------------
## 프로젝트 생성
스프링 부트와 JPA를 사용하여 프로젝트를 만든다.
- 스프링 부트 스타터(Spring initializr)
  - Gradle Project
  - 버전은 안정화된 버전으로(2.4.1)
  - dependencies
    - **Spring Web** : 웹 애플리케이션 개발할 때 꼭 사용되는 것
     - **Thymeleaf** : jsp보다 권장한다.
    - **Spring Data JPA** : 이번 강의에서는 Spring이랑 JPA를 활용해서 어떡해 만드는지 설명, Spring Data JPA에 대해선 설명하지 않는다.
    - **h2 database** : mySQL도 좋지만(설치하는 것들이 까다롭다) 개발을 하거나 테스트할 때 h2가 편리하다.
    - **lombok** : 지루하게 반복하는 코드를 줄여준다.

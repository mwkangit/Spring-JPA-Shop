# Spring-JPA-Shop


## Description

본 프로젝트에서는 JPA를 사용하여 간단한 인터넷 쇼핑몰을 구현하였다. 회원 가입, 회원 목록, 상품 등록, 상품 목록, 상품 주문, 주문 내역 로직을 구현하여 인터넷 쇼핑몰의 주요 기능을 담았다. 상품에는 수정 기능, 주문에는 주문 상태와 회원명을 통한 조회 및 주문 취소를 추가로 구현하였다. Spring MVC를 사용하여 뷰를 생성하였고 JPA는 트랜잭션 스크립트 패턴으로 디자인하였다. 



------





## Environment

<img alt="framework" src ="https://img.shields.io/badge/Framework-SpringBoot-green"/><img alt="framework" src ="https://img.shields.io/badge/Language-java-b07219"/> 

Framework: `Spring Boot` 2.5.4

Project: `Gradle`

Packaging: `Jar`

IDE: `Intellij`

ORM: `JPA`(Hibernate, Spring Data JPA)

DBMS: `H2-Database`

Template Engine: `Thymeleaf`

Dependencies: `Spring Web`, `Spring Data JPA`, `Lombok`, `Validation`



------



## Installation



![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) 

```
./gradlew build
cd build/lib
java -jar hello-spring-0.0.1-SNAPSHOT.jar
```



![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white) 

```
gradlew build
cd build/lib
java -jar hello-spring-0.0.1-SNAPSHOT.jar
```



------



## Core Feature

- home.html

![practice function](/media/mwkang/Klevv/Spring 일지/스프링 JPA1/09.13/practice function.png)

어플리케이션의 메인 페이지로 인터넷 쇼핑몰 기능 사용을 시작할 수 있다.



- Entity Diagram

![Entity Analysis](/media/mwkang/Klevv/Spring 일지/스프링 JPA1/09.13/Entity Analysis.png)

어플리케이션의 Entity Diagram으로 Spring 코드를 기준으로 본 것이다. 각 Entity의 속성, 연관관계를 확인할 수 있다. 모두 JPA를 사용하여 H2-Database에 CRUD 방식을 적용하는 형식으로 구현하였다.



------



## Demonstration Video

- 회원

![Spring-JPA-Shop-Member](/home/mwkang/Downloads/Spring-JPA-Shop-Member.gif)



- 상품

![Spring-JPA-Shop-Item](/home/mwkang/Downloads/Spring-JPA-Shop-Item.gif)



- 주문

![Spring-JPA-Shop-Order](/home/mwkang/Downloads/Spring-JPA-Shop-Order.gif)



------



## More Explanation

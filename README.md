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

![practice function](https://user-images.githubusercontent.com/79822924/152636309-a86801a8-afc1-4513-b46a-cbb42124cde6.png)

어플리케이션의 메인 페이지로 인터넷 쇼핑몰 기능 사용을 시작할 수 있다.



- Entity Diagram

![Entity Analysis](https://user-images.githubusercontent.com/79822924/152636316-4f4fb5a9-12e6-4787-b0ae-7539b50a682f.png)

어플리케이션의 Entity Diagram으로 Spring 도메인 관점으로 본 것이다. 각 Entity의 속성, 연관관계를 확인할 수 있다. 모두 JPA를 사용하여 H2-Database에 CRUD 방식을 적용하는 형식으로 구현하였다.



------



## Demonstration Video

- 회원

![Spring-JPA-Shop-Member](https://user-images.githubusercontent.com/79822924/152636287-18d47fb1-2b0a-4e4a-821a-4e0124109eda.gif)



- 상품

![Spring-JPA-Shop-Item](https://user-images.githubusercontent.com/79822924/152636290-5642fbd6-8704-4b29-bc8a-e7dda875d77d.gif)



- 주문

![Spring-JPA-Shop-Order](https://user-images.githubusercontent.com/79822924/152636294-fd01475f-9ae9-46d9-be24-a1691d5e5af3.gif)



------



## More Explanation


[Spring-JPA-Shop-Note.md](https://github.com/mwkangit/Spring-JPA-Shop/blob/master/Spring-JPA-Shop-Note.md)

## Welcome using JPA-Bat

Welcome and thanks.

This is a IDEA plugin to help u to generate java files when you using SpringData JPA.

## Usage

When you using JPA-Bat, you just need to specify few values and take following steps:

1. Install JPA-Bat from "IDEA marketplace" and Restart IDEA.

2. Following next section named "Templates Usage" to CREATE your own templates.

3. Then, Click "JPA-Bat" menu form top menu items and Click "Start Config".

4. Then you just specify few "path" and click the "Generate" button.

5. Finally, Enjoy you develop.(σ´∀`)σ 

### Templates Usage

SpringData JPA generally contains three layers: Controller, Service and Dao.(Entity is used to create ORM relationship for you, so i didn't put in it)

> you can reference this link to know more details: [Spring Boot with Spring Data JPA](https://www.amitph.com/spring-boot-with-spring-data-jpa/)

#### Controller Expression

Current version for you in Controller are following:
---
|${expression}|meaning|example|
---
|${EntityName}|This the entity name you want to create.|${User}|
|${EntityName}|This the entity name you want to create.|${User}|

# Spring Unit testing
<p align="center">
</p>

---
<li> Welcome to Spring unit testing, It's a simple project to practice unit testing with spring using junit and mockito</li>

##  📝Table of content

---
- [Built Using](#built).
- [Features](#features).
- [Requirements](#requirements).
- [Installation Steps](#installation).
- [Api documentation](#api).
- [Acknowledgements](#acknowledgements).


## ⛏️ Built Using <a name = "built"></a>

---
- [MySQL](https://dev.mysql.com) - Database
- [Java](https://docs.oracle.com/en/java/) - Programming Language
- [Spring boot](https://spring.io/projects/spring-boot) - Web Framework
- [Junit](https://junit.org/junit5/) - testing framework
- [Mockito](https://site.mockito.org/) - mocking framework
- [H2](https://www.h2database.com/html/main.html) - lightweight in memory database for testing

## 🧐Features <a name = "features"></a>

---
- 3 endpoints to get all students, add a student and 
- delete a student
- StudentService, StudentRepository and exceptions
- unit tests for StudentService and StudentRepository

## 🔧Requirements <a name = "requirements"></a>

---
- java => 17
- spring boot => 3.2.3
- maven
- MySQL

## 🚀 Installation Steps <a name = "installation"></a>

---
First clone this repository, install the dependencies, and setup your .env file.

````
git clone https://github.com/VlixAli/spring-unit-testing.git
mvn clean install
cd src/main/resources
cp .env.example .env
````

then run the following commands to run the project

````
cd ../../../
mvn spring-boot:run
````

the application will be available at [http://localhost:8080](http://localhost:8080)




## 🎉 Acknowledgements <a name = "acknowledgements"></a>

---

this simple project was created based on this crash course
[Software Testing Tutorial - Learn Unit Testing and Integration Testing](https://www.youtube.com/watch?v=Geq60OVyBPg)

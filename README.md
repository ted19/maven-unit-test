Maven - How to run Unit Test (Maven, Junit)
===============================

Maven unit test examples, JUnit 5.

## 1. Technologies and tools used:
* Java 17
* Spring Tool Suite 4
* Maven 3.9
* JUnit 5.9.2

## 2. How to run this project?
```shell
$ git clone https://github.com/ted19/maven-unit-test.git

$ cd maven-unit-test

$ mvn test
$ mvn -Dtest=TestMessageBuilder test
$ mvn -Dtest=TestMessageBuilder#testHelloWorld test
```

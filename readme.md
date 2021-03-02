## What is it?
This source code is an Spring Boot SSL (HTTPS) example.

Tested with
* Maven 3
* Java 8
* Spring Boot 2.2.4.RELEASE
* Spring Boot default embedded Tomcat 9
* Self-signed certificate (PKCS12)

## How to run this?
```bash
$ git clone https://github.com/isaccanedo/Spring-Boot-SSL/

$ cd spring-boot-ssl

$ mvn clean package

$ java -jar target/spring-boot-web.jar

  access https://localhost:8443
```

Redirecione todo o tráfego da porta 8080 para 8443.
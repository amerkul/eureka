# Eureka 

Eureka Server is an application that holds the information about all client-service applications. Every Micro service will register into the Eureka server and Eureka server knows all the client applications running on each port and IP address. Eureka Server is also known as Discovery Server.

# Glossary
1.Eureka - Discovery Server.

# Prerequisites

You need to have [```Docker```](https://www.docker.com), ```Java 17+```, and ```Maven 3.3+``` installed.

# Get started

```shell
./mvnw clean install

docker-compose up
```

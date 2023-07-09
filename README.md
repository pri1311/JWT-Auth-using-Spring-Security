# Spring Boot 3.0 Security with JWT Implementation
This project demonstrates the implementation of security using Spring Boot 3.0 and JSON Web Tokens (JWT). It includes the following features:

## Features
* User registration and login with JWT authentication
* Password encryption using BCrypt
* Customized access denied handling

## Technologies
* Spring Boot 3.0
* Spring Security
* JSON Web Tokens (JWT)
* BCrypt
* Maven
 
## Getting Started
To get started with this project, you will need to have the following installed on your local machine:

* JDK 17+
* Maven 3+


To build and run the project, follow these steps:

* Clone the repository: `git clone https://github.com/ali-bouali/spring-boot-3-jwt-security.git`
* Navigate to the project directory: cd spring-boot-security-jwt
* Add database "jwt_security" to postgres under username `username` and password `password`
* Build the project: mvn clean install
* Run the project: mvn spring-boot:run 

-> The application will be available at http://localhost:8080.
* Register: `/api/v1/auth/register`
* Login: `/api/v1/auth/authenticate`
* Unsecure Page: `/api/v1/auth/hello`
* Secure Page: `/api/v1/demo/hello`

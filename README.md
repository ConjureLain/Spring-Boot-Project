This project contains technologies:
- Spring Boot 2.1.8
- Java 11
- JPA + Hibernate
- MySQL 8.0.18
- Bootstrap 4
- Maven 3.6.1

How to run application
---------------------------------------------
```bash
## Build application from base directory
mvn clean install

## Run initialization MySql scripts
initial-data-forms.sql
initial-data-users.sql

## Run Spring boot application
mvn spring-boot:run

```
A bank employee logs in (by Spring Security) to accept or reject the customer's request.
For Employee, Username:employee  Password:employee
For Manager, Username:manager  Password:manager

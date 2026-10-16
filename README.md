# Spring Boot Practice

A collection of small projects I built while learning Java, Spring Boot and testing. Each folder is a standalone Maven project.

| Project | Topic |
|---|---|
| [jwt](./jwt) | Authentication with Spring Security & JWT (BCrypt, custom filter) |
| [pageable](./pageable) | Pagination and sorting with Spring Data `Pageable` |
| [exception-management](./exception-management) | Global exception handling and custom error responses |
| [spring-data-jpa](./spring-data-jpa) | Entity relationships and repositories with Spring Data JPA |
| [junit-coffee-maker](./junit-coffee-maker) | Unit testing practice with JUnit |

## Tech Stack
Java, Spring Boot 3, Spring Data JPA, Spring Security, JWT, PostgreSQL, JUnit, Maven

## Running a project
```bash
cd jwt
./mvnw spring-boot:run
```
Database settings for each project are in `src/main/resources/application.properties`.

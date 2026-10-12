# BookHub — Library Management

A Java and Spring Boot learning app for managing a small library. It uses Spring MVC, Spring Data JPA, MySQL, and a server-rendered web interface.

This repository is a sibling copy of [bookhub](https://github.com/kavinash0310/bookhub), with the Maven project at the repository root rather than inside `BookHub/`.

## Run locally

Requirements: Java 8 or newer and MySQL.

1. Create the local database expected by `src/main/resources/application.properties`.
2. Replace the sample database credentials with your own local values.
3. Start the app:

```bash
./mvnw spring-boot:run
```

On Windows, use `mvnw.cmd spring-boot:run`. The app is configured for port `8011`.

This is a learning project. Do not use the committed sample database settings for a shared or production database.

# jhudevops

A basic starter Java Spring Boot application for DevOps testing.

## Prerequisites

- Java 17+
- Maven 3.6+

## Running the Application

```bash
./mvnw spring-boot:run
```

The application will start on `http://localhost:8080`.

## Endpoints

| Method | Path | Description        |
|--------|------|--------------------|
| GET    | `/`  | Returns "Hello, World!" |

## Running Tests

```bash
./mvnw test
```

## Building

```bash
./mvnw package
```

This produces a runnable JAR in `target/demo-0.0.1-SNAPSHOT.jar`.

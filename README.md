# Spring Boot Application

A sample Spring Boot application demonstrating basic setup and configuration.

## Prerequisites

- Java 17 or higher
- Maven 3.6+

## Getting Started

### Build the application

```bash
mvn clean install
```

### Run the application

```bash
mvn spring-boot:run
```

The application will start on `http://localhost:8080`

## API Endpoints

- `GET /` - Returns a simple greeting
- `GET /api/greeting` - Returns welcome message

## Project Structure

```
src/
├── main/
│   ├── java/com/example/
│   │   ├── Application.java
│   │   └── controller/
│   │       └── HelloController.java
│   └── resources/
│       └── application.properties
└── test/
```

## License

MIT License
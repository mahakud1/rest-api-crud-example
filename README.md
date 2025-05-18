# rest-api-crud-example
rest-api-crud-example

## Overview

This project demonstrates a simple REST API with CRUD (Create, Read, Update, Delete) operations using Java and Spring Boot. It is structured as a Maven project for easy dependency management and build automation.

## Features

- RESTful endpoints for CRUD operations
- In-memory database (H2) for development and testing
- Standard Maven project structure

## Prerequisites

- Java 17 or higher
- Maven 3.9+
- Ensure Path Variables are set properly

## Getting Started

1. **Clone the repository:**
    go to your windows/unix path where you want to clone the remote project
    ```bash
    git clone https://github.com/mahakud1/rest-api-crud-example.git
    cd rest-api-crud-example
    ```

2. **Build the project:**
    ```bash
    mvn clean package
    ```

3. **Run the application:**
    ```bash
    mvn spring-boot:run
    ```

4. **Access the API:**
    - The API will be available at 'http://localhost:8080/swagger-ui/index.html/' 


## Project Structure

```
rest-api-crud-example/
├── src/
│   ├── main/
│   │   ├── java/
│   │   └── resources/
│   └── test/
├── pom.xml
└── README.md
```

## API Endpoints

| Method | Endpoint        | Description          |
|--------|----------------|----------------------|
| GET    | /entities      | List all entities    |
| GET    | /entities/{id} | Get entity by ID     |
| POST   | /entities      | Create new entity    |
| PUT    | /entities/{id} | Update entity        |
| DELETE | /entities/{id} | Delete entity        |

## License

NA
# Spring Boot MongoDB REST API

This is a Spring Boot application that demonstrates the use of Spring Data MongoDB, Lombok, and Spring Web dependencies. The application provides RESTful endpoints to add and retrieve student records.

## Dependencies

- Spring Boot
- Spring Data MongoDB
- Lombok
- Spring Web

## Endpoints

- `POST /addStudent` - Adds a new student to the MongoDB database.
- `GET /students` - Retrieves all students from the MongoDB database.

## Configuration

### application.properties

```properties
spring.application.name=mongodb1
server.port=8081
spring.data.mongodb.uri=mongodb://localhost:27017/student

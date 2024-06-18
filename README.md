# Spring Boot MongoDB REST API

This is a Spring Boot application that demonstrates the use of Spring Data MongoDB, Lombok, and Spring Web dependencies. The application provides RESTful endpoints to add and retrieve student records.

![Screenshot 2024-06-18 171212](https://github.com/Tejas-24ytj/Spring-Boot-MongoDB/assets/105742352/eeafc5f2-4a2f-46a2-bfdf-9932d9748c6a)

![Screenshot 2024-06-18 171242](https://github.com/Tejas-24ytj/Spring-Boot-MongoDB/assets/105742352/19cf2c9a-dfe0-4f31-be08-cf65e6268e05)

![Screenshot 2024-06-18 171346](https://github.com/Tejas-24ytj/Spring-Boot-MongoDB/assets/105742352/f04c6416-2fe0-47ee-bbfd-2836073a4b50)

![Screenshot 2024-06-18 171443](https://github.com/Tejas-24ytj/Spring-Boot-MongoDB/assets/105742352/3c0cae15-fa3c-4569-b752-1272d13da509)


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

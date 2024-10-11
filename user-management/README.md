This project is a REST API for managing users, built using Java 17 and Spring Boot.
It allows you to perform basic CRUD (Create, Read, Update, Delete) operations on user data. 
The service supports JSON request and response formats and uses an embedded H2 database for persistence,
ensuring data is stored across application restarts.


##Features
Create new users
Retrieve all users
Retrieve a single user by ID
Update user details
Delete a user

###Technologies Used
Java 17
Spring Boot
Spring Data JPA
H2 Database (file-based for persistence)
Maven
Prerequisites
JDK 17 or higher
Maven 3.6+
Postman for testing API endpoints

## Testing endpoints
POST http://localhost:8080/users
GET http://localhost:8080/users
GET http://localhost:8080/users/{id}
PUT http://localhost:8080/users/{id}
DELETE http://localhost:8080/users/{id}

# H2 database
http://localhost:8080/h2-console
JDBC URL: jdbc:h2:file:./data/usermanagementdb
Username: sa
Password: password 
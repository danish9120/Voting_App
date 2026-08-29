🗳️ Voting App

A backend Voting Application built using Java and Spring Boot. The application provides REST APIs for managing voting-related operations and uses MySQL for persistent data storage.

🚀 Technologies Used
Java
Spring Boot
Spring Data JPA
Hibernate
MySQL
Maven
REST APIs
Postman for API testing
📌 Features
Create and manage users
Create and manage candidates
Cast votes
Retrieve voting-related data
Store application data in MySQL
RESTful API architecture
Layered architecture using Controller, Service, and Repository layers
JPA/Hibernate for database operations

🔄 Architecture
The application follows a layered architecture:

Client / Postman
       ↓
   Controller
       ↓
     Service
       ↓
   Repository
       ↓
      MySQL
Controller Layer

Handles HTTP requests and exposes REST endpoints.

Service Layer

Contains the application's business logic.

Repository Layer

Uses Spring Data JPA to communicate with the database.

Database

MySQL is used for persistent storage.

⚙️ Setup and Installation
1. Clone the repository
git clone https://github.com/danish9120/Voting_App.git
2. Open the project

Open the project in IntelliJ IDEA or another Java IDE.

3. Configure MySQL

Create a MySQL database and update the database configuration in:

src/main/resources/application.properties

Example:

spring.datasource.url=jdbc:mysql://localhost:3306/voting_app

spring.datasource.username=root
spring.datasource.password=**********

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

4. Run the application

Using Maven:

mvn spring-boot:run

Or run the main Spring Boot application class directly from IntelliJ IDEA.

The application will start on:

http://localhost:8080
🧪 API Testing

The REST APIs can be tested using Postman.

Example request:

POST http://localhost:8080/...

Add the required request body according to the API endpoint.

📂 Database

The application uses MySQL as the relational database and Spring Data JPA/Hibernate for object-relational mapping.

Database entities are mapped using JPA annotations such as:

@Entity
@Id
@GeneratedValue

🎯 Learning Outcomes

Through this project, I practiced:

Building REST APIs with Spring Boot
Dependency Injection
Controller-Service-Repository architecture
Spring Data JPA
Hibernate ORM
Entity relationships and database mapping
MySQL database integration
CRUD operations
API testing using Postman
Maven project management

👨‍💻 Author
Danish Margoob

GitHub:
https://github.com/danish9120
https://drive.google.com/file/d/1aLkYw0dXOFCzcnB2dzQol7gsUIIQBqn0/view?usp=drivesdk

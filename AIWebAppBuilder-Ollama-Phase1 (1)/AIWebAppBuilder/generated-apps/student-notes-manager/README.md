# Student Notes Manager

This is a minimal Java 17 Spring Boot website using Thymeleaf and H2. It includes a homepage with a welcome message styled with blue-and-white CSS.

## How to Run
1. Clone the repository.
2. Navigate to the project directory.
3. Run `mvn spring-boot:run` to start the application.

## Structure
- `pom.xml`: Maven configuration.
- `src/main/java/com/generated/app/GeneratedApplication.java`: Spring Boot application entry point.
- `src/main/resources/application.properties`: Spring Boot configuration properties.
- `src/main/resources/templates/index.html`: Thymeleaf template for the homepage.
- `src/main/resources/static/css/style.css`: CSS for styling the homepage.

## Dependencies
- Spring Boot Starter Web MVC: for building web applications.
- Spring Boot Starter Thymeleaf: for using Thymeleaf templates.
- Spring Boot Starter Data JPA: for using JPA with H2.
- H2 Database: for in-memory database.

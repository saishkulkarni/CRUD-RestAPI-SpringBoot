# CrudRestApi-SpringBoot

This project is a simple CRUD (Create, Read, Update, Delete) REST API built using Spring Boot. It demonstrates basic operations on a Student entity.

## Features

- Create new student records
- Retrieve student information
- Update existing student records
- Delete student records

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- MySQL Database
- Maven

## Project Structure

The project follows a standard Spring Boot application structure:

- `src/main/java/org/jsp/crudrestapi`: Contains the Java source code
  - `controller`: REST API endpoints
  - `dao`: Data Access Object for database operations
  - `dto`: Data Transfer Objects (Student entity)
  - `repository`: JPA repository interface
  - `service`: Business logic layer

## Setup and Installation

1. Clone the repository:

2. Navigate to the project directory:

3. Update the `application.properties` file in `src/main/resources` with your MySQL database configuration.

4. Build the project:

5. Run the application:

The application will start running at `http://localhost:8080`.

## API Endpoints

- POST `/api/students`: Create a new student
- GET `/api/students`: Retrieve all students
- GET `/api/students/{id}`: Retrieve a specific student by ID
- PUT `/api/students/{id}`: Update a student
- DELETE `/api/students/{id}`: Delete a student
- GET `/api/students/find-by-name/{name}`: Find students by name
- GET `/api/students/find-by-percentage/{percentage}`: Find students by percentage
- GET `/api/students/find-by-stream/{stream}`: Find students by stream
- GET `/api/students/find-by-phone/{phone}`: Find a student by phone number
- GET `/api/students/find-by-email/{email}`: Find a student by email


Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

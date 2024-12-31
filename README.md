# Java-Springboot-student-management-system

A web-based application built to manage student data effectively. This system allows administrators to perform CRUD (Create, Read, Update, Delete) operations on student records and offers a user-friendly interface for managing data.

## Features
- Add, update, and delete student information.
- View a list of all students in the database.
- Search for specific students using filters.
- Responsive design for an optimal user experience.

## Tech Stack
- **Backend**:
  - Spring MVC
  - Spring Boot
  - Spring Data JPA
- **Frontend**:
  - Thymeleaf 
- **Database**:
  - MySQL
- **Build Tool**:
  - Maven
- **Version Control**:
  - Git

## Installation

### Prerequisites
Ensure you have the following installed on your system:
- Java 8+
- MySQL
- Maven

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Chamudi-Samarasinghe/Java-Springboot-student-management-system.git
   ```

2. Navigate to the project directory:
   ```bash
   cd student-management-system
   ```

3. Configure the database:
   - Create a MySQL database named `sms`.


4. Build the project:
   ```bash
   mvn clean install
   ```

5. Run the application:
   ```bash
   mvn spring-boot:run
   ```

6. Access the application:
   Open your browser and navigate to `http://localhost:8080`.






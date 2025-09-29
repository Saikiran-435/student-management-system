# Student Management System

A simple web-based Student Management System built using Java, Spring MVC, Hibernate, and Thymeleaf.  
This project allows basic CRUD operations (Create, Read, Update, Delete) for student records.

##  Features

- Add new student
- View list of students
- Update existing student details
- Delete student records
- User-friendly interface with Thymeleaf

##  Technologies Used

- Java
- Spring MVC
- Hibernate (ORM)
- Thymeleaf (for front-end)
- MySQL (Database)
- Maven
- Spring Tool Suite (STS)

##  Project Structure
src/
└── main/
├── java/
│ └── com.example.student
│ ├── controller
│ ├── dao
│ ├── model
│ └── service
└── webapp/
└── WEB-INF/
└── views/
├── list-students.html
├── student-form.html


##  How to Run the Project

1. Clone this repository  
2. Open in Spring Tool Suite (STS) or IntelliJ  
3. Set up MySQL database (e.g., create `student_db`)  
4. Update `hibernate.cfg.xml` with your DB credentials  
5. Build and run the application  
6. Open browser and go to: `http://localhost:8080/student/list`  






# Expense Tracker System


A full-stack **Expense Tracker System** built using **Java, Spring Boot, MySQL, HTML, CSS, and JavaScript**. The application enables users to securely manage their personal finances by tracking income and expenses, monitoring account balances, and viewing transaction history through a clean and responsive interface.

---

## Features 

### User Features

* User registration and secure login
* Add income and expense transactions
* View complete transaction history
* Track current balance, total income, and total expenses
* Simple and responsive user interface

### Backend Features

* RESTful API architecture
* Spring Boot-based application
* Spring Data JPA for database operations
* Service and repository layer architecture
* MySQL database integration

### Frontend Features

* Responsive HTML, CSS, and JavaScript interface
* Login and registration pages
* Transaction management forms
* Dynamic financial reporting

---

## Tech Stack

| Technology      | Description                     |
| --------------- | ------------------------------- |
| Java            | Programming language            |
| Spring Boot     | Backend framework               |
| Spring Data JPA | ORM and database operations     |
| MySQL           | Database                        |
| HTML            | Frontend structure              |
| CSS             | Styling                         |
| JavaScript      | Client-side functionality       |
| Maven           | Build and dependency management |

---

## Project Structure

Expense-Tracker-System/
├── src/
├── controller/
├── service/
├── repository/
├── model/
├── resources/
├── frontend/
├── pom.xml
└── README.md

---

## Installation

### Clone the repository

git clone https://github.com/Bhushantrao/Expense-Tracker-System.git

### Navigate to the project

cd Expense-Tracker-System

### Create the MySQL database

CREATE DATABASE expense_tracker;

### Configure the database

Update the `application.properties` file with your MySQL credentials.

Example:

spring.datasource.url=jdbc:mysql://localhost:3306/expense_tracker
spring.datasource.username=your_username
spring.datasource.password=your_password

### Run the application

mvn spring-boot:run

The backend server will start on:

http://localhost:8080

### Run the frontend

Open the frontend files in a browser or use a Live Server extension in VS Code.

---

## API Modules

* Authentication
* Income Management
* Expense Management
* Transaction History
* Balance and Financial Reports

---

## Future Enhancements

* Budget planning
* Expense categories
* Monthly and yearly analytics
* Charts and data visualization
* Export reports to PDF and Excel
* Email notifications
* Mobile application integration

---

## Author

**Bhushan T Rao**

GitHub: https://github.com/Bhushantrao

---

## License

This project is developed for educational and portfolio purposes.

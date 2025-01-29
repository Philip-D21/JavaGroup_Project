# 🚀 Bank App - Spring Boot API

This is a simple **Banking Application** built with **Spring Boot** and **Maven**.  
It provides RESTful endpoints for managing users and handling errors.

---

## 📌 Features

- ✅ User Management (Basic Endpoints)  
- ✅ Custom Error Handling  
- ✅ RESTful API with Spring Boot  
- ✅ Maven-based project structure  

---

## 🛠️ Tech Stack

- **Java** (Spring Boot)  
- **Spring Web** (REST API)  
- **Maven** (Dependency Management)  
- **Spring Boot Starter**  

---

## 📂 Project Structure

```bash
bank-app/
│── src/
│   ├── main/
│   │   ├── java/com/example/demo/
│   │   │   ├── controller/
│   │   │   │   ├── UserController.java
│   │   │   │   ├── CustomErrorController.java
│   │   │   ├── model/
│   │   │   │   ├── User.java
│   │   │   ├── repository/
│   │   │   │   ├── UserRepository.java
│   │   │   ├── service/
│   │   │   │   ├── UserService.java
│   │   │   ├── DemoApplication.java
│   ├── resources/
│   │   ├── application.properties
│── pom.xml
│── README.md


## Installation

### CLone the repository 
- git clone https://github.com/your-username/bank-app.git
- cd bank-app


## Build the project

- mvn clean install

## Run the application

- mvn spring-boot:run

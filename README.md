# 📚 BookStore REST API

A Spring Boot RESTful API to manage a bookstore's inventory — supports full CRUD operations, in-memory database, and Swagger UI for testing.

---

## 🧾 Introduction

The BookStore project is a backend service developed using Java and Spring Boot. It allows users to perform Create, Read, Update, and Delete (CRUD) operations on book records via RESTful endpoints. The goal is to demonstrate core backend development concepts and best practices.

---

## 🔧 Tools & Technologies Used

- Java 17  
- Spring Boot 3.5.4  
- Spring Web & Spring Data JPA  
- H2 In-Memory Database  
- Swagger UI  
- Postman  
- Maven  
- Git & GitHub  
- IntelliJ IDEA / VS Code  

---

## 📌 Features

- Add new books  
- View all books  
- View book by ID  
- Update book info  
- Delete books  
- Swagger integration for testing  
- Postman collection for quick testing  

---

## 🚀 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/Ankitshahi895/bookStore.git
   cd bookStore

2. Run using Maven

mvn spring-boot:run


3. Open in browser:
Swagger UI: http://localhost:8081/swagger-ui/index.html




---

🔄 API Endpoints

Method	Endpoint	Description

GET	/books	Get all books
GET	/books/{id}	Get book by ID
POST	/books	Add new book
PUT	/books/{id}	Update book
DELETE	/books/{id}	Delete book



---

📬 Postman Collection

Import the included Postman collection to test all endpoints.

Check /postman/BookStore.postman_collection.json in the repo.

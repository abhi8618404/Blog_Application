# ✍️ Blog Application  ![Live Link](https://blog-application-01.onrender.com/) 

![Java](https://img.shields.io/badge/Java-007396.svg?&logo=java&logoColor=white) 
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F.svg?&logo=springboot&logoColor=white) 
![Hibernate](https://img.shields.io/badge/Hibernate-59666C.svg?&logo=hibernate&logoColor=white) 
![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?&logo=mysql&logoColor=white) 
![REST API](https://img.shields.io/badge/REST_API-000000.svg?&logo=fastapi&logoColor=white)  

A **RESTful blogging platform** built with **Spring Boot** and **Hibernate**.  
Supports authentication, blog post management, and comments.

---

## ✨ Features
- 📝 Create, edit, and delete blog posts.
- 💬 Commenting system.
- 🔐 User authentication & role-based access.
- 📊 Pagination & sorting for posts.
- 💾 MySQL database for persistent storage.

---

## 🛠 Tech Stack
- **Java 17**
- **Spring Boot**
- **Hibernate ORM**
- **Spring Data JPA**
- **MySQL**
- **Maven**

---

## 📂 Project Structure
```
Blog-Application/
│
├── src/main/java
│   ├── controller/
│   ├── service/
│   ├── repository/
│   └── model/
├── src/main/resources
└── pom.xml
```

---

## ⚡ Installation & Setup
```bash
git clone https://github.com/abhi8618404/Blog-Application.git
cd Blog-Application
mvn clean install
mvn spring-boot:run
```

---

## 🔗 API Endpoints
| Method | Endpoint              | Description           |
|--------|----------------------|-----------------------|
| GET    | /posts               | Get all posts         |
| GET    | /posts/{id}          | Get post by ID        |
| POST   | /posts               | Create new post       |
| PUT    | /posts/{id}          | Update post           |
| DELETE | /posts/{id}          | Delete post           |

---

## 📸 Screenshots
> <img width="1918" height="858" alt="Screenshot 2025-08-12 130835" src="https://github.com/user-attachments/assets/738e4648-b516-49d2-8d05-78bb4484c6c6" />


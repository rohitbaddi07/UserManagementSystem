📌 Project Overview

A simple User Management System built using Spring Boot.

Provides REST APIs for managing users (CRUD operations).

Uses Spring Data JPA for database interaction.

Follows layered architecture (Controller → Service → DAO → Repository → Entity).

✨ Features

Create a new user

Retrieve user details by ID

Update user information

Delete a user

Unified response format with ResponseStructure

🛠️ Tech Stack

Java 17+

Spring Boot

Spring Data JPA

Hibernate

Maven (build tool)

H2 / MySQL (configurable database in application.properties)

📌 Example Endpoints

POST /users → Create a user

GET /users/{id} → Get user by ID

PUT /users/{id} → Update user

DELETE /users/{id} → Delete user

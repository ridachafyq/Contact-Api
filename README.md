# Contacts API – Demo Project

A RESTful Web API **demo** built with **ASP.NET Core** for managing contacts.
The project implements full **CRUD** operations (Create, Read, Update, Delete) and follows a **layered architecture** that clearly separates concerns between the API, business logic, and data access layers.

---

## 🏗 Architecture

The solution is divided into three main layers:

* **ContactApi** → API layer
  Handles HTTP requests, controllers, routing, and DTOs.

* **Business** → Business logic layer
  Contains services, validations, and application rules.

* **Data** → Data access layer
  Responsible for database operations using SQL Server stored procedures (via EF Core / ADO.NET).

This structure improves **maintainability**, **scalability**, and **testability**.

---

## 🚀 Demo Features

* Create new contacts (using stored procedures)
* Retrieve all contacts
* Retrieve a contact by ID
* Update existing contacts
* Delete contacts
* SQL Server stored procedures for all database operations
* RESTful API endpoints
* Swagger UI for easy API testing and documentation

---

## 🛠 Tech Stack

* **ASP.NET Core Web API**
* **SQL Server** (Stored Procedures)
* **Swagger / OpenAPI**

---

## 📌 Demo Notes

* This is a demo application intended for learning and practice purposes.
* Stored procedures are used for better control over database operations.
* Swagger is enabled for quick testing and exploration of endpoints.

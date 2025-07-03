---
## Problem Statement 1: ORM Focus - "Library Management System - Basic Book and Author Tracking"

Design a simple Library Management System where you need to track **Books** and **Authors**. Each **Book** has a title, ISBN, publication year, and price. Each **Author** has a first name, last name, and a short bio.

* **ORM Objectives:**
    * Create `Book` and `Author` entities using JPA annotations.
    * Map basic properties (String, Integer, Double) to database columns.
    * Implement a `BookRepository` and `AuthorRepository` using `JpaRepository`.
    * Perform basic CRUD operations:
        * Add new books and authors.
        * Find books by title or ISBN.
        * Update book details (e.g., price).
        * Delete books or authors.
    * Demonstrate that JPA correctly maps Java objects to database tables and vice-versa, allowing you to interact with data using objects rather than raw SQL.

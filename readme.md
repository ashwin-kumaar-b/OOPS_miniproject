Employee Performance Tracker
Overview

Employee Performance Tracker is a Java-based application designed to manage employee details, performance reviews, and analytics. It demonstrates core Java concepts such as OOP, Exception Handling, Generics, Multi-threading, JDBC, Networking, and GUI programming with JavaFX.

This project is structured into five main modules, each covering key aspects of Java programming.

Modules
1️⃣ Module 1: Core OOP Concepts

Files: mod1.java

Features:

Classes: Employee, Manager, PerformanceEvaluator

Inheritance and Polymorphism

Encapsulation, Static members, Access specifiers

Constructors and finalize() method

Abstract classes and method overriding

Purpose: Models employees and managers with salary calculation and evaluation.

2️⃣ Module 2: Exception Handling & Data Management

Files: mod2.java

Features:

Custom Exceptions: InvalidDataException, EmployeeNotFoundException

Employee Data Management with EmployeeDataManager

Arrays, Strings, Collections

Interfaces (DataExport) and inner classes (EmployeeStatistics)

Serialization and file I/O

Object cloning (PerformanceReview.clone())

Purpose: Safely manage employee data, handle errors, and export data.

3️⃣ Module 3: Generics & Multi-threading

Files: mod3.java

Features:

Generic repositories for Employee and PerformanceReview

Multi-threaded performance calculation (PerformanceCalculator)

Thread synchronization and Executors

Synchronizers: Semaphore, CyclicBarrier

Purpose: Demonstrates advanced Java features like generics, threading, and synchronization for performance analytics.

4️⃣ Module 4: JDBC Database Management

Files: mod4.java

Features:

Connects to MySQL database employeetracker

Creates tables: employees, performance_reviews

Inserts sample data

Executes queries and joins

Database initialization and closing connection

Purpose: Persistent storage of employees and performance reviews using JDBC.

5️⃣ Module 5: GUI Programming (JavaFX)

Files: mod5.java

Features:

JavaFX GUI for displaying employee performance

TableView with columns: Name, Department, Score, Manager Comments

Refresh button to reload data from database

EmployeeDataModel for TableView binding

Purpose: User-friendly interface to view and monitor employee performance.

Technologies Used

Java 11+

JavaFX

JDBC (MySQL)

Collections, Generics, Multi-threading

Exception Handling

Object-Oriented Programming

Setup Instructions

Clone the repository

git clone https://github.com/yourusername/EmployeePerformanceTracker.git


Import project into your IDE (Eclipse, IntelliJ IDEA, NetBeans)

Setup MySQL database

Create database employeetracker (handled automatically in Module 4)

Update MySQL credentials in mod4.java and mod5.java

Run the modules

Run mod1.java to test OOP concepts

Run mod2.java to test data management and exceptions

Run mod3.java for multi-threading & generics

Run mod4.java for database operations

Run mod5.java for GUI interface

Explore the application through JavaFX GUI.

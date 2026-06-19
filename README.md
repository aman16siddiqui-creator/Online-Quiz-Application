# Online Quiz System

## Overview

The Online Quiz System is a Java-based console application developed using Object-Oriented Programming (OOP) principles. The system allows users to register, select quiz categories and difficulty levels, attempt quizzes, track their quiz history, and view their scores upon completion.

The project demonstrates key software engineering concepts such as abstraction, inheritance, polymorphism, encapsulation, high cohesion, loose coupling, exception handling, and input validation.


## Features

### User Authentication

* Registration Number Validation (8 digits)
* Password Validation (5 digits)
* User Profile Management

### Quiz Categories

* Mathematics
* Science
* History
* Geography
* Literature
* General Knowledge

### Difficulty Levels

* Easy
* Medium
* Hard

### Quiz Functionalities

* Multiple Choice Questions (MCQs)
* Automatic Score Calculation
* Quiz History Tracking
* Correct Answer Review
* Input Validation
* Error Handling

### User Experience

* Interactive Console Interface
* Color-Coded Difficulty Levels
* Quiz Rules Display
* Multiple Quiz Attempts


## Object-Oriented Programming Concepts Used

### Abstraction

* Implemented through the abstract `User` class.
* Defines common attributes and behaviors for all users.

### Inheritance

* `RegularUser` inherits from the `User` class.

### Polymorphism

* Method overriding through the `displayRole()` method.

### Encapsulation

* Data members are protected/private and accessed through methods.

### High Cohesion

* The `Quiz` class is responsible only for quiz-related operations.

### Loose Coupling

* `RegularUser` and `Quiz` classes interact with minimal dependency.


## Technologies Used

* Java
* ArrayList
* Scanner Class
* Exception Handling
* Object-Oriented Programming (OOP)


## System Workflow

1. User enters Registration Number and Password.
2. User selects a quiz category.
3. User chooses a difficulty level.
4. Quiz rules are displayed.
5. Questions are presented one by one.
6. User submits answers.
7. System calculates and displays the score.
8. Quiz history is updated.
9. User may attempt another quiz.


## Project Structure

### Classes

#### User (Abstract Class)

* Stores registration information.
* Defines common user behavior.

#### RegularUser

* Manages user profile.
* Maintains quiz history.

#### Quiz

* Stores quiz information.
* Manages questions, options, and answers.

#### OnlineQuiz

* Main application class.
* Handles user interaction and quiz execution.


## Learning Outcomes

This project demonstrates:

* Object-Oriented Programming Concepts
* Exception Handling
* Input Validation
* Collections Framework (ArrayList)
* Console-Based Application Development
* Software Design Principles


## How to Run

1. Open the project in Eclipse, IntelliJ IDEA, or NetBeans.
2. Compile the Java source file.
3. Run the `OnlineQuiz` class.
4. Enter valid credentials.
5. Select a subject and difficulty level.
6. Start attempting quizzes.

---
ented Programming (OOP) Project for learning software design principles and quiz management system development.

# Jweller-Shop-Loan-Management-System

## Overview

The Jewelry Loan Management System is a backend-driven application developed using Java and Spring Boot to help jewelry shops manage gold and silver loan operations efficiently. The system enables secure customer onboarding, loan calculation, repayment tracking, report generation, and overdue payment monitoring.
The application calculates loan eligibility, interest amounts, and repayment values dynamically based on metal type, weight, market rates, and loan duration. It also provides secure authentication, automated reminders, and downloadable reports to streamline daily loan management activities.

## Features

# Authentication & Authorization

* User Registration and Login
* JWT-based Authentication
* Refresh Token Mechanism for Session Management
* Role-based Access Control (Admin/User)

# Loan Management

* Create and manage Gold and Silver loans
* Dynamic loan eligibility calculation
* Interest calculation based on configurable rates
* Repayment amount calculation
* Loan status tracking

# Customer Management

* Customer registration and profile management
* Loan history tracking
* Loan repayment monitoring

## Report Generation

* Export loan reports in PDF format
* Export customer reports in Word format
* Download transaction and repayment reports

## Reminder & Notification System

* Automated overdue payment detection
* TAT (Turnaround Time) based reminder generation
* Pending repayment tracking


## Technology Stack

# Backend

* Java 17
* Spring Boot
* Spring Security
* Spring Data JPA
* Hibernate

# Database

* MySQL

### Security
* JWT Authentication
* Refresh Tokens

### Build Tools
* Maven

* Postman

# Reporting

* PDF Report Generation
* Word Document Generation

# Backend Architecture

The application follows a layered architecture:

* Controller Layer – REST API endpoints
* Service Layer – Business logic implementation
* Repository Layer – Database interaction using JPA/Hibernate
* Security Layer – JWT authentication and authorization
* Exception Layer – Centralized error handling

## Key Backend Implementations

* RESTful API Development
* JWT + Refresh Token Security
* Loan Calculation 
* Database Relationship Mapping using JPA
* Global Exception Handling
* Scheduler/Reminder Logic
* Report Generation APIs
  

## Author

Ashish Bhardwaj

Java Backend Developer | Spring Boot | REST APIs | SQL | Linux

GitHub: 

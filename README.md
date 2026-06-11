# Internship Management System

## Overview

The Internship Management System is a full-stack application developed to streamline the internship application and management process for students, mentors, and administrators.

This project was developed using Flutter for the frontend and ASP.NET Core Web API for the backend, with SQL Server as the database.

---

## Features

### Student Module
- Student Registration
- Student Login
- View Available Internship Roles
- Apply for Internships
- Track Application Status
- View Assigned Mentor Information

### Admin Module
- Admin Authentication
- Manage Internship Roles
- Manage Students
- Manage Mentors
- Review Internship Applications
- Assign Mentors to Students
- Monitor Internship Progress

### Backend Features
- RESTful API Architecture
- JWT Authentication & Authorization
- Entity Framework Core Integration
- SQL Server Database Support
- CRUD Operations
- Secure User Management

---

## Technology Stack

### Frontend
- Flutter
- Dart

### Backend
- ASP.NET Core Web API
- C#

### Database
- SQL Server

### Authentication
- JWT (JSON Web Token)

### ORM
- Entity Framework Core

---

## Project Architecture

Flutter Application

↓

ASP.NET Core Web API

↓

Entity Framework Core

↓

SQL Server Database

---

## Source Code

The project source code is currently provided as compressed files:

- front-end.zip (Flutter Application)
- back-end.zip (ASP.NET Core Web API)

Please download and extract the files before running the project.

---

## Installation Guide

### Backend Setup

1. Extract `back-end.zip`
2. Open the project in Visual Studio
3. Configure the SQL Server connection string in `appsettings.json`
4. Restore NuGet packages
5. Run database migrations

```bash
dotnet ef database update
```

6. Start the API

```bash
dotnet run
```

---

### Frontend Setup

1. Extract `front-end.zip`
2. Open the project in VS Code or Android Studio
3. Install dependencies

```bash
flutter pub get
```

4. Run the application

```bash
flutter run
```

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Full Stack Development
- Mobile Application Development
- REST API Development
- Authentication and Authorization
- Database Design
- Entity Framework Core
- SQL Server Integration
- Flutter Development
- Software Architecture
- CRUD Operations

---

## Future Enhancements

- Email Notifications
- File Upload Support
- Internship Progress Tracking
- Interview Scheduling
- Dashboard Analytics
- Cloud Deployment

---

## Author

Jeswin Jojo

B.Tech Student

GitHub: https://github.com/Jeswin-Jojo

---

## License

This project is intended for educational and portfolio purposes.

# TaskFlow Manager

TaskFlow Manager is a simple web-based platform developed during the Earny Internship Program. The purpose of this project is to help users manage tasks, collaborate with team members, and track work progress through a clean and user-friendly interface.

---

## Problem Statement

Many students and small teams struggle to organize their daily tasks and project activities. Existing tools are often complex for beginners. This project aims to provide a simple solution for task management and collaboration.

---

## Project Objectives

- Provide secure user registration and login.
- Allow users to create and manage tasks.
- Enable collaboration among team members.
- Maintain task-related information in a structured database.
- Build a beginner-friendly project using Flask and MySQL.

---

## Features

- User Registration
- User Login & Logout
- Session Management
- Create Tasks
- View Task Feed
- Task Discussion / Updates
- Database Integration
- Responsive User Interface

---

## Technology Stack

### Frontend
- HTML
- CSS

### Backend
- Python
- Flask

### Database
- MySQL

### Tools
- Git
- GitHub
- VS Code

---

## System Architecture

User Interface (HTML/CSS)
        ↓
Flask Application (Python)
        ↓
MySQL Database

The frontend collects user input, Flask processes requests, and MySQL stores the application data.

---

## Installation Guide

Clone Repository

```bash
git clone <repository-url>
```

### Install Dependencies

```bash
pip install -r requirement.txt
```

### Configure Database

1. Create MySQL database.
2. Import schema.sql.
3. Update database credentials inside app.py.

### Run Application

```bash
python app.py
```

Application will start on:

```text
http://127.0.0.1:5000
```

---

## Here simple steps again

1. Download or clone the project from GitHub.

2. Install all required Python packages using:
   pip install -r requirement.txt

3. Create the MySQL database and import schema.sql.

4. Update your database username and password inside app.py.

5. Start the application using:
   python app.py

6. Open http://127.0.0.1:5000 in your browser.

## Future Scope

- Task Priority Levels
- Team Dashboard
- Email Notifications
- Profile Management
- Search and Filter Tasks
- Project Analytics

---

## Contributors

### [@rajanmaurya12012008](https://github.com/rajanmaurya12012008)
- Backend Development
- Documentation

### [@imomrg](https://github.com/imomrg)
- Authentication Module
- Validation Improvements

### [@nyashagupta-24](https://github.com/nyashagupta-24)
- Feature Development
- Code Review

### [@rkriteshsingh1236-del](https://github.com/rkriteshsingh1236-del)
- Database Support
- Testing

### [@sanjanakum552-prog](https://github.com/sanjanakum552-prog)
- UI Improvements
- Documentation Support

---

## Learning Outcomes

Through this project, the team gained practical experience in:

- Flask Development
- MySQL Integration
- Git and GitHub Workflow
- Team Collaboration
- Software Documentation

---

## Conclusion

TaskFlow Manager demonstrates the implementation of a simple project management platform using Flask and MySQL. The project focuses on clean functionality, collaboration, and maintainable code structure while providing a foundation for future enhancements.

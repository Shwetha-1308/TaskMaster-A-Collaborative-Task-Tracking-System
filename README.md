TaskMaster – Collaborative Task Management System

TaskMaster is a full-featured collaborative task management system designed to help teams plan, organize, and track work efficiently.
Users can create boards, lists, tasks, add labels, set due dates, attach files, comment, search tasks, collaborate with team members, and manage task workflows through a drag-and-drop interface.

-----------------------------------------------------------------------------------------------------------------------

🚀 Project Overview

TaskMaster provides a structured way to manage projects by breaking them into:

Boards – represent projects

Lists – categorize workflow stages

Tasks (Cards) – individual work items

The system supports collaboration, allowing multiple users to work together on shared boards with full task activity tracking.

-----------------------------------------------------------------------------------------------------------------------------------

✨ Features

🔐 User Authentication

User registration & login

JWT/session-based authentication

Secured APIs

Access control for shared boards

🗂️ Boards, Lists & Tasks

Create, rename, delete boards

Add lists under each board

Add tasks under lists

Modify tasks at any time

Drag & drop tasks between lists

📝 Task Features

Title & description

Due dates

Labels (color-coded)

Comments

Attachments

Task order management

Status updates

👥 Collaboration

Share boards with team members

Multi-user access

Comment-based communication

Shared task visibility

🔔 Notifications

Task updates

Comments

Due date reminders (based on backend rules)

🔍 Search Functionality

Search tasks by title

Search by description

Filter tasks by labels, dates, status

---------------------------------------------------------------------------------------------------------------------

🛠️ Tech Stack
Backend

Java

Spring Boot

Hibernate / JPA

MySQL / PostgreSQL

JWT Authentication

REST API Architecture

-------------------------------------------------------------------------------------------------------------------------------

🏁 Getting Started

📥 Clone the Repository:

git clone https://github.com/Shwetha-1308/TaskMaster-A-Collaborative-Task-Tracking-System.git

cd taskmaster

⚙️ Backend Setup

Install Dependencies:

cd backend

mvn clean install

Configure application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/taskmaster

spring.datasource.username=root

spring.datasource.password=yourpassword

jwt.secret=your_secret_here

file.upload.path=/uploads

Run the Backend:

mvn spring-boot:run


Backend runs on:

http://localhost:8080

-------------------------------------------------------------------------------------

📡 API Documentation

Refer to these APIs Postman collections:

✔ Task-APIs.postman_collection

✔ User-APIs.postman_collection

----------------------------------------------------------------------------------------------------------------------------

🚀 Future Enhancements

AI-powered task suggestions

Calendar-based task view

Board activity analytics & dashboards

Export board as PDF or Excel

Voice notes inside tasks

Recurring task feature


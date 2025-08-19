Loan Management System is a full-stack web application that streamlines the process of applying for and managing loans. The system allows users to apply for loans, upload documents, track application status, view sanction letters, and provides role-based access for different stakeholders like customers, managers, and loan officers.

This repository contains both the Angular frontend and the Spring Boot backend for a complete solution.

🚀 Features

🔐 Authentication & Authorization – Secure login/registration with JWT

💼 Loan Applications – Apply, review, and manage loans

📄 Document Upload – Upload and verify required loan documents

📊 Application Tracking – Real-time updates on loan progress

📑 Sanction Letters – Auto-generate and view sanction letters

💰 Disbursement Management – Manage and track loan disbursements

🛠️ Role-based Access – Features for customers, loan officers, credit managers, and disbursement managers

📱 Responsive UI – Optimized for desktop and mobile

🧑‍💻 Tech Stack
Frontend

Angular 16.x

TypeScript / HTML / CSS

JWT Authentication

Backend

Java 17+ / Spring Boot

Hibernate / JPA

Spring Security (JWT)

RESTful APIs

MySQL

📂 Project Structure
loan-management-system/
 ├── frontend/                 # Angular Frontend
 │   ├── src/...
 │   └── angular.json
 ├── backend/                  # Spring Boot Backend
 │   ├── src/main/java/com/sit/homeloan/...
 │   └── pom.xml
 └── README.md

🔧 Setup Instructions
✅ Prerequisites

Node.js & npm

Angular CLI (npm install -g @angular/cli)

Java JDK 17+

Maven 3.6+

MySQL Server

⚡ Running the Backend
# Clone the repo
git clone https://github.com/spuffyffets/loan-management-system.git
cd loan-management-system/backend

# Configure DB in application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/home_loan?createDatabaseIfNotExist=true
spring.datasource.username=YourUserName
spring.datasource.password=YourPassword

# Run Spring Boot app
mvn spring-boot:run


Backend runs on 👉 http://localhost:8080/

⚡ Running the Frontend
cd loan-management-system/frontend
npm install
ng serve --open


Frontend runs on 👉 http://localhost:4200/

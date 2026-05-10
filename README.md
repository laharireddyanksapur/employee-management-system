# Employee Management System

A full stack Employee Management System built using React, Spring Boot, and MySQL.

## Features

- Add employee
- View employee records
- Update employee details
- Delete employee records
- REST API integration
- MySQL database connection
- Responsive frontend UI

## Tech Stack

Frontend:
- React.js
- Axios
- CSS

Backend:
- Spring Boot
- Spring Data JPA
- Maven

Database:
- MySQL

## Project Structure

employee-management-system/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── src/
│   ├── pom.xml
│   └── application.properties

## Backend Setup

1. Open MySQL Workbench
2. Create database:

```sql
CREATE DATABASE employeedb;
Frontend Setup
Go to frontend folder
cd frontend
Install dependencies
npm install
Start frontend
npm start

Frontend runs on:

http://localhost:3000
API Endpoints
Method	Endpoint	Description
GET	/employees	Get all employees
POST	/employees	Add employee
PUT	/employees/{id}	Update employee
DELETE	/employees/{id}	Delete employee

# Employee_Management

Payroll or Salary Management System
Efficient, easy-to-use payroll management solution built with ASP.NET Core and SQL Server.

✨ Project Overview
A web application for automating payroll processes, tracking employee attendance, managing user roles, and generating payslips. Designed to simplify HR tasks for small and medium organizations, ensuring accurate payroll calculation and quick reporting.

🚀 Features
Employee Management

Add, update, view, and delete employee profiles

Store department, designation, salary, joining date, and status

Attendance Tracking

Record daily attendance (Present, Absent, Leave)

View and edit attendance history per employee

Payroll Calculation

Auto-calculate net salary based on base pay, paid days, and deductions

Generate monthly payroll with a single action

Payslip Generation

Download or print payslips with full salary and attendance summary

Role-Based Authentication

Admins: Full management of data, payroll, users

Employees: View own profile, attendance, and payslips

Dashboard & Reports

Overview of employee count, salary expenses, attendance summary

Basic data export (CSV/Excel) for payroll and attendance

🏗️ Tech Stack
Backend: ASP.NET Core (Web API/MVC)

Frontend: ASP.NET MVC / Razor Pages

ORM: Entity Framework Core

Database: SQL Server

Authentication: Identity or custom roles (Admin/Employee)

Optional: Bootstrap for responsive UI

🗂️ Database Schema (Core Tables)
Table	Purpose
Employees	Staff profiles with salary and role info
Attendance	Daily records of presence/absence/leave
Payroll	Calculated salaries for each month
Users	Authentication data and roles
📝 Getting Started
Clone the repository

Configure your SQL Server connection string

Run database migrations or execute the provided SQL schema

Build and run the project (dotnet run)

Access the web app and login as admin to start managing data

📚 Contributing
Fork the repo and create feature branches

Submit PRs with clear descriptions

Report bugs, request features via issues

📄 License
This project is open source and distributed under the MIT License.




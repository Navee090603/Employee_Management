# 💼 Employee Management & Payroll System

An efficient and user-friendly web application designed to automate and simplify employee management, attendance tracking, and payroll generation. Built using **ASP.NET Core** and **SQL Server**, it's ideal for small to medium organizations looking to streamline HR operations.

---

## 🚀 Features

- 👨‍💼 **Employee Management**  
  Add, update, view, and delete employee profiles with department, designation, salary, and joining info.

- ⏱️ **Attendance Tracking**  
  Record daily attendance (Present, Absent, Leave) and view per-employee history.

- 💸 **Payroll Calculation**  
  Auto-calculate monthly salaries based on base pay, paid days, and deductions.

- 📄 **Payslip Generation**  
  View, print, or download detailed payslips for each employee.

- 🔐 **Role-Based Authentication**  
  - **Admin**: Manage employees, payroll, attendance, and users  
  - **Employee**: View own profile, attendance, and payslips

- 📊 **Dashboard & Reports**  
  View employee count, salary expenses, attendance summary  
  Export payroll and attendance data to CSV/Excel

---

## 🛠️ Tech Stack

| Layer        | Technology                          |
|--------------|-------------------------------------|
| **Backend**  | ASP.NET Core (MVC / Web API)        |
| **Frontend** | Razor Pages / ASP.NET MVC           |
| **ORM**      | Entity Framework Core               |
| **Database** | SQL Server                          |
| **Auth**     | ASP.NET Identity / Custom Roles     |
| **UI Tools** | Optional Bootstrap for responsiveness |

---

## 🗂️ Database Schema

| Table Name   | Description                               |
|--------------|-------------------------------------------|
| `Employees`  | Staff profiles with salary and role info  |
| `Attendance` | Daily attendance records (P/A/L)          |
| `Payroll`    | Monthly salary calculations               |
| `Users`      | Login credentials and role assignments    |

---

## 📦 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/payroll-system.git
   ```

2. **Configure database connection**  
   Update your SQL Server connection string in `appsettings.json`.

3. **Apply migrations or use provided SQL schema**

4. **Build and run the project**
   ```bash
   dotnet run
   ```

5. **Login and get started**  
   Use admin credentials to begin managing data.

---

## 🤝 Contributing

- Fork the project and create feature branches  
- Submit pull requests with meaningful commits  
- Use GitHub Issues for bugs or feature requests

---

## 📄 License

This project is licensed under the **MIT License** — open-source, free to use and modify.

---

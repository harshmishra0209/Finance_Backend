# Finance Data Processing and Access Control Backend

## 📌 Overview
This project is a backend system designed for managing financial records with role-based access control. It provides APIs for handling users, financial transactions, and dashboard analytics.

The system demonstrates clean backend architecture, proper data modeling, and structured API design.

---

## 🚀 Features

### 👤 User Management
- Create and manage users
- Assign roles (ADMIN, ANALYST, VIEWER)
- Manage user status (active/inactive)

### 💰 Financial Records
- Create, view, and delete financial records
- Filter records by:
  - Type (INCOME / EXPENSE)
  - Category

### 📊 Dashboard Analytics
- Total Income
- Total Expense
- Net Balance
- Category-wise totals
- Recent activity (latest records)

### 🔐 Access Control
- Role-based access implemented:
  - ADMIN → Full access
  - ANALYST → Read + analytics
  - VIEWER → Read only

---

## 🛠 Tech Stack

- Java
- Spring Boot
- Spring Data JPA
- MySQL

---

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/finance-dashboard-backend.git

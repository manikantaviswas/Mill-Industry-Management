# 🏭 Mill Industry Management System

A Java Swing-based desktop application designed to streamline the operations of a mill industry. This project leverages **Java**, **Swing**, **Oracle SQL**, and **JDBC** to manage raw materials, products, inventory, customers, employees, suppliers, sales, and expenses effectively.

---

## 📌 Features

- 🔧 Add, view, and manage:
  - Raw Materials
  - Products
  - Inventory
  - Employees
  - Customers
  - Expenses
- 🔐 Admin login system
- 🧾 Real-time CRUD operations with Oracle SQL database
- 📊 Organized GUI using Java Swing
- 🛡️ Data integrity and validation using JDBC

---

## 🛠️ Technologies Used

- **Java (Swing)** – Frontend interface
- **Oracle SQL** – Backend database
- **JDBC** – Java-Database connectivity
- **NetBeans IDE** – Development environment

---

## 📂 Modules Overview

| Module        | Description                                      |
|---------------|--------------------------------------------------|
| Login Page    | Authenticates admin credentials                  |
| Dashboard     | Central hub to navigate to different modules     |
| Raw Materials | Add/fetch raw material details                   |
| Products      | Manage product catalog and prices                |
| Inventory     | Track quantity and restock dates                 |
| Employees     | Maintain employee data and salaries              |
| Customers     | Store customer contact and order data            |
| Expenses      | Log and monitor operational expenses             |

---

## 🗄️ Database Schema

The database consists of multiple normalized tables:

- `RawMaterials(raw_material_id, material_name, quantity_available, unit_price, supplier_id)`
- `Products(product_id, product_name, unit_price, category)`
- `Inventory(inventory_id, product_id, quantity_available, last_restock_date)`
- `Customers(customer_id, customer_name, contact_info)`
- `Employees(employee_id, employee_name, position, salary)`
- `Expenses(expense_id, expense_type, amount, expense_date)`

> See the project report for DDL/DML scripts and ER diagram.

---

## 🚀 How to Run

1. **Install Oracle Database** and ensure it's running.
2. **Create the required tables** using the SQL scripts provided.
3. **Clone this repository**:
   ```bash
   git clone https://github.com/your-username/mill-industry-management.git
   cd mill-industry-management

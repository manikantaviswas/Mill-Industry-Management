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

> See the project report for DDL/DML scripts.


**ER-Diagram**:


<img width="598" height="354" alt="image" src="https://github.com/user-attachments/assets/f21007db-3feb-44b2-af57-5d9f182bc043" />


## 🚀 How to Run

1. **Install Oracle Database** and ensure it's running.
2. **Create the required tables** using the SQL scripts provided.
3. **Clone this repository**:
   ```bash
   [git clone https://github.com/your-username/mill-industry-management.git
   cd mill-industry-management](https://github.com/manikantaviswas/Mill-Industry-Management/tree/main)
 4.**Open the project in NetBeans or any Java IDE**.
 
 5.**Configure the database credentials in the JDBC connection strings**.
 
 6.**Run LoginPage.java to start the application**.

📸 Screenshots
</br>
**LOGIN:**
</br>
<img width="431" height="303" alt="image" src="https://github.com/user-attachments/assets/34190da3-0da5-4e93-acaa-9e248061bbd4" />
</br>
**SIGN UP:**
</br>
<img width="397" height="323" alt="image" src="https://github.com/user-attachments/assets/5b9dbd84-bc92-4a82-a1b3-eb4a2924cf54" />
</br>
**DASH BOARD:**
</br>
<img width="387" height="234" alt="image" src="https://github.com/user-attachments/assets/ef34e1e1-1efa-43e2-adc9-78c22244bbb1" />
</br>
**Raw Material (Details):**
</br>
<img width="536" height="307" alt="image" src="https://github.com/user-attachments/assets/3d5087f3-d4f0-4d49-8edc-e30cada09cdf" />
</br>
**Products (Details):**
</br>
<img width="568" height="352" alt="image" src="https://github.com/user-attachments/assets/4019a0c3-434d-46d4-a7ab-7b0ba429f5c8" />
</br>
**Inventory (Details):**
</br>
<img width="482" height="342" alt="image" src="https://github.com/user-attachments/assets/af5929c8-7fde-408c-b4af-1bd0b968480e" />
</br>
**Employees (Details):**
</br>
<img width="487" height="344" alt="image" src="https://github.com/user-attachments/assets/51902296-2e1e-4a24-9818-0f0eda6428f6" />
</br>
**Expenses (Details):**
</br>
<img width="453" height="345" alt="image" src="https://github.com/user-attachments/assets/3f142414-9ec3-415d-9f66-caa43e814414" />
</br>
**Customers (Details):**
</br>
<img width="450" height="342" alt="image" src="https://github.com/user-attachments/assets/706ab153-23df-4426-842c-55878bf3874d" />
</br>














# 🛒 E-commerce Store Database (MySQL)

A full-featured relational database schema designed for an e-commerce store. This project includes SQL scripts to create tables, define relationships, and set constraints for handling products, orders, customers, payments, and inventory.

---

## 📁 Project Structure

ecommerce-store-database/
│
├── answers # Main SQL file containing database schema
└── README.md # Project documentation


---

## 🧱 Features

- **Relational schema** for managing:
  - Customers
  - Products
  - Categories
  - Orders
  - Order Items
  - Payments
  - Inventory
- **Proper constraints**:
  - `PRIMARY KEY`, `FOREIGN KEY`, `NOT NULL`, `UNIQUE`, `CHECK`
- **Relationships**:
  - One-to-One: Orders ↔ Payments, Products ↔ Inventory
  - One-to-Many: Customers → Orders, Categories → Products
  - Many-to-Many: Orders ↔ Products (via `Order_Items`)

---

## 📦 Requirements

- MySQL 8.0 or higher
- A MySQL client (e.g., MySQL Workbench, DBeaver, CLI)

---

## 🚀 Getting Started

---

🗃️ Schema Overview
Tables and Relationships
| Table         | Description                  |
| ------------- | ---------------------------- |
| `Customers`   | Stores customer info         |
| `Categories`  | Product categories           |
| `Products`    | Product listings with prices |
| `Inventory`   | Tracks available stock       |
| `Orders`      | Customer orders              |
| `Order_Items` | Items within each order      |
| `Payments`    | Payment records per order    |

---

🔐 Constraints & Integrity

* FOREIGN KEYS ensure referential integrity.

* CHECK constraints on price and quantity fields.

* UNIQUE constraints on emails and category names.









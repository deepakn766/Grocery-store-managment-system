# 🛒 Grocery Store Management System

A relational database project designed to streamline operations in a grocery store, including inventory tracking, order processing, employee management, and supplier coordination. Built using **MySQL** and modeled with **EER diagrams** in **MySQL Workbench**.

## 📌 Features
- Manage customers, employees, suppliers, and product categories
- Track orders and order details with pricing and quantity
- Maintain product inventory with category and supplier linkage
- Timestamped records for auditing and updates
- User authentication module for secure access

## 🧩 Database Schema Overview

The system includes the following core tables:

| Table           | Description                                      |
|------------------|--------------------------------------------------|
| `employees`      | Stores employee details and hire dates           |
| `customers`      | Contains customer names and addresses            |
| `supplier`       | Tracks supplier info and addresses               |
| `categories`     | Defines product categories                       |
| `products`       | Links products to categories and suppliers       |
| `orders`         | Records customer orders handled by employees     |
| `order_details`  | Itemized breakdown of each order                 |
| `user`           | Stores login credentials and timestamps          |

## 🔗 Relationships
- Each **product** belongs to a **category** and is supplied by a **supplier**
- Each **order** is placed by a **customer** and processed by an **employee**
- **Order details** link products to orders with quantity and pricing
- **User** table supports authentication and audit trails

## 🛠️ Tech Stack
- **Database**: MySQL
- **Modeling**: MySQL Workbench (EER Diagram)
- **Language**: SQL
- **Tools**: ER modeling, normalization, foreign key constraints

## 📈 Business Relevance
This schema supports:
- Efficient inventory and sales tracking
- Role-based access and accountability
- Scalable design for multi-branch grocery chains

## 📷 ER Diagram Preview
> *(<img width="1920" height="1080" alt="Screenshot 2025-11-24 152216" src="https://github.com/user-attachments/assets/5438ab59-233e-48d3-bc69-f9a4ece27db3" />
)*


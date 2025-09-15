# 🛒 E-commerce Store Database (MySQL)

This project implements a relational database for managing an **E-commerce Store** using **MySQL**.  
The database covers users, products, categories, orders, order items, and payments.  

---

## 📌 Features
- Manage **users** (customers and admins) with roles.  
- Store **product details** with categories and stock tracking.  
- Handle **orders** and their items.  
- Support multiple **payment methods** (M-Pesa, card, PayPal, bank).  
- Enforce **referential integrity** with foreign keys and cascading rules.  

---

## 🗂️ Database Schema

### Entities
1. **Users** – customer/admin accounts  
2. **Categories** – product categories  
3. **Products** – items available for sale  
4. **Orders** – customer orders  
5. **Order Items** – line items for each order  
6. **Payments** – payment details for orders  

### Relationships
- A **User** can place many **Orders**.  
- An **Order** contains multiple **Order Items**.  
- Each **Order Item** is linked to a **Product**.  
- A **Category** can have multiple **Products**.  
- An **Order** has exactly **one Payment**.  

---


CREATED BY: Macharia Joseph

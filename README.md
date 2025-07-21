# Inventory Management System

This is a simple **Inventory Management System** developed in **Java** and backed by a **MySQL** database. The system provides basic CRUD (Create, Read, Update, Delete) functionality to manage inventory items, including the ability to search for items by name.

## Features

- **View Items**: Display all items in the inventory.
- **Add Item**: Add a new item with a name, quantity, and price.
- **Update Item**: Update the quantity and/or price of an existing item.
- **Delete Item**: Remove an item from the inventory.
- **Search Items**: Search for items based on their name (case-insensitive).

## Prerequisites

- **Java 8 or higher**.
- **MySQL** database installed and running.
 ## Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/inventory-management.git
   cd inventory-management

2. **Create a database inventory_db**:
   ```bash
   CREATE DATABASE inventory_db;
   USE inventory_db;
3. **Create the items table**:
   ```bash
   CREATE TABLE items (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100) NOT NULL,
    quantity INT NOT NULL,
    price DOUBLE NOT NULL
   );
4. **

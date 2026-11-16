# E-Commerce Watch Shopping Cart & Inventory System

## Project Description

The **E-Commerce Watch Shopping Cart & Inventory System** is a C++ console-based application designed to simulate an online watch shopping platform. It allows customers to browse different watches, search for products, filter items by brand and price range, manage their shopping cart, and process orders.

The system also includes an inventory management feature that allows administrators to add products, restock items, remove products, and monitor available stock.

## Features

### Customer Features

1. **View Complete Catalog** – Displays all available watches, including product ID, name, category, brand, price, and stock quantity.
2. **Filter by Brand** – Allows customers to view watches from a specific brand.
3. **Search by Keyword** – Searches for watches using their product name or related keywords.
4. **Filter by Price Range** – Displays watches within a selected minimum and maximum price.
5. **Shopping Cart** – Allows customers to add, remove, and navigate through selected products.
6. **Checkout System** – Allows customers to place orders and process pending transactions.
7. **Brand Showcase** – Displays different partner watch brands.

### Administrator Features

1. **Add Product** – Adds new watches to the inventory.
2. **Restock Product** – Updates the available quantity of existing products.
3. **Remove Product** – Removes products from the inventory.
4. **Admin Action Logs** – Records administrative inventory activities.
5. **Undo Function** – Allows administrators to undo previous inventory actions.

## Data Structures and Algorithms Used

| Data Structure / Algorithm | Purpose |
|---|---|
| Binary Search Tree (BST) | Organizes products and supports product ID searching. |
| Doubly Linked List | Manages shopping cart items with forward and backward navigation. |
| Circular Linked List | Displays partner watch brands continuously. |
| Queue (FIFO) | Manages checkout orders in first-in, first-out order. |
| Stack (LIFO) | Stores administrative actions for undo operations. |
| Binary Search | Helps filter products within a selected price range. |

## Technologies Used

- **Programming Language:** C++
- **Compiler:** GCC / G++
- **Code Editor:** Visual Studio Code
- **Version Control:** Git and GitHub

## Sample Products

The system includes different watch brands, such as:

- Casio
- Seiko
- Citizen
- Fossil
- Timex
- TOMI
- BINBOND
- Pablo Raez
- Generic

## How to Compile and Run

1. Open the project folder in Visual Studio Code.
2. Open the terminal.
3. Compile the C++ source code using:

   ```bash
   g++ main.cpp -o ecommerce
   ```

4. Run the program:

   **Windows:**
   ```bash
   ecommerce.exe
   ```

   **Linux / macOS:**
   ```bash
   ./ecommerce
   ```

## Project Objectives

- To develop a simple e-commerce shopping system using C++.
- To implement different data structures and algorithms in a practical application.
- To provide an organized product catalog and inventory management system.
- To demonstrate how shopping carts and checkout queues work.
- To improve product searching and filtering efficiency.

## Conclusion

The E-Commerce Watch Shopping Cart & Inventory System demonstrates how C++ programming, data structures, and algorithms can be integrated into an online shopping application. It provides basic shopping functionalities and administrative inventory management while demonstrating the practical use of BST, linked lists, queues, stacks, and binary search.

---

**Project Type:** Console-Based E-Commerce Application  
**Language:** C++  
**Category:** Data Structures and Algorithms (DSA)

# 📦 Mini Project - Inventory Management System With Files

---

## 🚀 Overview

Welcome to the **Inventory Management System With Files** — a simple yet powerful Python application designed to help you manage small to medium-sized inventories using plain text files!  
Perfect for beginners, this project teaches you essential **file handling**, **structured data management**, and **basic business logic** concepts in Python, all within a clean, easy-to-understand Jupyter Notebook environment.

---

## 🔍 What Can It Do?

- **Add new products** with unique ID, name, price, and stock quantity.  
- **View the entire inventory** in a neat, tabulated format.  
- **Search products** instantly by Product ID.  
- **Handle retail purchases** smoothly with live stock updates.  
- **Manage wholesale sales** by recording customer details and bulk orders.  
- **Automatically update stock levels** and maintain accurate inventory.  
- **Keep detailed sales logs** with timestamps for transparency and tracking.

---

## ✨ Key Features

| Feature                | Description                                                        |
|------------------------|--------------------------------------------------------------------|
| **Add Products**       | Add new items quickly with ID, name, price, and quantity          |
| **View Inventory**     | See all products in a clean table format                           |
| **Search Product**     | Find any product by its unique ID                                  |
| **Buy Product (Retail)** | Purchase by name and quantity with live stock check               |
| **Update Inventory**   | Inventory updates instantly after every sale                       |
| **Refill Stock**       | Easily restock existing products                                   |
| **Wholesale Sales**    | Process bulk orders with customer info and save transaction logs  |
| **Sales Logging**      | Detailed logs for all wholesale transactions with timestamps      |

---

## 🛠️ Technologies Used

- Python 3  
- Jupyter Notebook  
- File I/O (Text Files & CSV Format)  
- Timestamp Logging  

---

## 🗂️ Project Structure

| File Name                     | Purpose                                              |
|-------------------------------|-----------------------------------------------------|
| `Inventory-Management-System.ipynb` | Main Jupyter Notebook with all the code            |
| `Inventory-of-gadgets.txt`     | Stores product inventory in CSV format               |
| `sales.txt`                   | Logs wholesale sales and customer transactions       |
| `README.md`                   | Project documentation                                 |

---

## 🎯 How It Works

- Checks if `Inventory-of-gadgets.txt` exists on startup; creates it if missing.  
- Stores products as comma-separated values:  
  `ProductID,ProductName,Price,Quantity`  
- Enables quick viewing, searching, buying, and restocking of products.  
- Captures customer details for wholesale sales and records transactions with timestamps.

---

## 📖 Getting Started

1. Open the project in **Jupyter Notebook**.  
2. Run the initialization cell to create the inventory file if it doesn't exist.  
3. Use the available functions to:  
   - Add and manage products  
   - Search and view inventory  
   - Process retail and wholesale purchases  
   - Refill stock as needed  
4. Check `sales.txt` for detailed wholesale transaction logs.

---

## ⚠️ Known Limitations

- Uses plain text files — not optimized for large or multi-user environments.  
- Minimal input validation — incorrect inputs may cause errors.  
- Command-line/Jupyter interface only — no GUI yet.  
- No enforcement of unique Product IDs (duplicates possible).

---

## 🚀 Future Enhancements

- Build a **main menu** for easier navigation.  
- Switch to Python’s built-in `csv` module for safer file handling.  
- Add robust **input validation and error handling**.  
- Migrate from text files to an **SQLite database** backend.  
- Create a **GUI interface** using Tkinter or PyQt.  
- Enforce **unique Product IDs** to avoid duplicates.

---

## 🔗 Explore the Code

View the full project and source code on GitHub:  
[Inventory-Management-System.ipynb](https://github.com/vinayakmishra4/Mini-Project-Inventory-Management-System-Using-Text-Files/blob/main/Inventory-Management-System.ipynb)

---

👨‍💻 *Author:* Vinayak  
📅 *Created:* 2025

---
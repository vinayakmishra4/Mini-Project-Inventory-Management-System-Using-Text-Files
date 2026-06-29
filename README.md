# 📦 Inventory Management System (Using Text Files)

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter" alt="Jupyter">
  <img src="https://img.shields.io/badge/Storage-Text%20Files-success?style=for-the-badge" alt="Storage">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
</p>

<p align="center">
  <strong>A beginner-friendly Inventory Management & Billing System built using Python and plain text files.</strong><br>
  Learn Python File Handling, CRUD Operations, Inventory Management, and Billing without using SQL or external libraries.
</p>

---

## 🔗 Quick Links

- 🌐 **Repository:**  
  https://github.com/vinayakmishra4/Mini-Project-Inventory-Management-System-Using-Text-Files

- 📓 **Jupyter Notebook:**  
  https://github.com/vinayakmishra4/Mini-Project-Inventory-Management-System-Using-Text-Files/blob/main/Inventory-Management-System.ipynb

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Installation](#-installation)
- [Usage](#-usage)
- [Workflow](#-workflow)
- [Example](#-example)
- [Data Files](#-data-files)
- [Learning Outcomes](#-learning-outcomes)
- [Future Improvements](#-future-improvements)
- [Screenshots](#-screenshots)
- [Author](#-author)
- [License](#-license)

---

# 📖 Overview

The **Inventory Management System** is a beginner-friendly console-based Python project that uses **plain text (`.txt`) files** as its database instead of SQL.

This project demonstrates how to build a complete inventory and billing application using only Python's standard library. It provides hands-on experience with file handling, CRUD operations, data parsing, inventory tracking, and customer billing.

The complete implementation is available in a **Jupyter Notebook**, where each feature is organized into separate sections for easy understanding.

---

# ✨ Features

### 📦 Inventory Management

- ➕ Add New Products
- 📋 View Inventory
- 🔍 Search Products by Product ID
- 🔄 Refill Existing Stock
- 📉 Automatically Update Inventory After Purchase

### 💰 Billing System

- 🛒 Buy Products
- 🧾 Generate Customer Bills
- 💵 Automatic Total Calculation
- 📝 Save Sales Records

### 👤 Customer Information

Each purchase stores:

- Customer Name
- Phone Number
- Email Address
- Purchase Date & Time

All customer purchase records are automatically saved to **sales.txt**.

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| 🐍 Python 3 | Programming Language |
| 📓 Jupyter Notebook | Development Environment |
| 📂 Text Files | Database |
| 📚 os | File Handling |
| ⏰ datetime | Billing Timestamp |

> **No external libraries required.**

---

# 📁 Project Structure

```text
Mini-Project-Inventory-Management-System-Using-Text-Files/
│
├── Inventory-Management-System.ipynb
├── Inventory-of-gadgets.txt
├── sales.txt
├── LICENSE
└── README.md
```

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/vinayakmishra4/Mini-Project-Inventory-Management-System-Using-Text-Files.git
```

Move into the project directory

```bash
cd Mini-Project-Inventory-Management-System-Using-Text-Files
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```text
Inventory-Management-System.ipynb
```

Run all notebook cells sequentially from **top to bottom**.

---

# 🚀 Usage

The notebook is organized into the following sections:

| Step | Feature |
|------|---------|
| 1 | Create Inventory File |
| 2 | Add Product |
| 3 | Read Inventory |
| 4 | Search Product |
| 5 | Buy Product & Generate Bill |
| 6 | Update Inventory |
| 7 | Refill Stock |
| 8 | Complete Sales System |

---

# 🔄 Workflow

```text
Create Inventory File
        │
        ▼
Add Product
        │
        ▼
Read Inventory
        │
        ▼
Search Product
        │
        ▼
Purchase Product
        │
        ▼
Generate Bill
        │
        ▼
Update Inventory
        │
        ▼
Record Customer Details
        │
        ▼
Save Sale to sales.txt
```

---

# 💻 Example

### ➕ Add Product

```text
Enter Product ID: 3

Enter Product Name: iPad Air

Enter Product Price: 55000

Enter Product Quantity: 15

Product Added Successfully ✔
```

Stored in **Inventory-of-gadgets.txt**

```text
3,iPad Air,55000,15
```

---

### 📋 Read Inventory

```text
---------------------------------------------------------
Product ID   Product Name      Price       Quantity
---------------------------------------------------------
1            iPhone 15         79999       20
2            Samsung S24       68999       12
3            iPad Air          55000       15
---------------------------------------------------------
```

---

### 🧾 Purchase Product

```text
Customer Name : Rahul

Product ID : 2

Quantity : 2

Total Amount : ₹137998

Purchase Successful ✔
```

The inventory is automatically updated, and the transaction is saved to **sales.txt**.

---

# 📂 Data Files

### Inventory File

**Inventory-of-gadgets.txt**

```text
product_id,product_name,product_price,product_quantity
```

Example

```text
1,iPhone 15,79999,20
2,Samsung S24,68999,12
3,iPad Air,55000,15
```

---

### Sales File

**sales.txt**

```text
timestamp,
product_id,
product_name,
quantity_sold,
total_amount,
customer_name,
customer_phone,
customer_email
```

---

# 🎯 Learning Outcomes

This project helps you learn:

- Python File Handling
- CRUD Operations
- CSV/Text File Processing
- Inventory Management Logic
- Billing System Development
- Customer Record Management
- Console Application Development

---

# 🚀 Future Improvements

- ✅ Refactor notebook into a Python module
- ✅ Menu-driven CLI application
- ✅ Object-Oriented Programming (OOP)
- ✅ SQLite database integration
- ✅ Product Update & Delete functionality
- ✅ Duplicate Product ID validation
- ✅ Input validation
- ✅ Low stock alerts
- ✅ Sales analytics dashboard
- ✅ Export bills as PDF
- ✅ GUI using Tkinter or PyQt

---

# 📸 Screenshots

You can add screenshots here to showcase your project.

```text
📷 Home Menu

📷 Add Product

📷 Inventory List

📷 Billing Screen

📷 Sales History
```

---

# 🤝 Contributing

Contributions are welcome!

1. Fork this repository.
2. Create a new branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Add new feature"
```

4. Push to GitHub.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

# 👨‍💻 Author

## Vinayak Mishra

- **GitHub:** https://github.com/vinayakmishra4

If you found this project helpful, consider giving it a ⭐ on GitHub!

---

# 📜 License

This project is licensed under the **MIT License**.

Feel free to use, modify, and distribute this project for educational purposes.

---

<p align="center">
⭐ If you like this project, don't forget to star the repository! ⭐
</p>

<p align="center">
Made with ❤️ using Python
</p>

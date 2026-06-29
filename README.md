# 📦 Inventory Management System (Using Text Files)

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter" alt="Jupyter">
  <img src="https://img.shields.io/badge/Database-Text%20Files-success?style=for-the-badge" alt="Database">
  <img src="https://img.shields.io/badge/Platform-Console%20Application-lightgrey?style=for-the-badge" alt="Platform">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
</p>

<h3 align="center">
A Beginner-Friendly Inventory & Billing Management System built using Python and Plain Text Files 📦
</h3>

<p align="center">
Manage products, generate bills, update inventory, and store customer purchase records without using SQL or any external database.
</p>

---

## 🌟 Quick Links

<p align="center">

<a href="https://github.com/vinayakmishra4/Mini-Project-Inventory-Management-System-Using-Text-Files">
<img src="https://img.shields.io/badge/View-Repository-181717?style=for-the-badge&logo=github">
</a>

<a href="https://github.com/vinayakmishra4/Mini-Project-Inventory-Management-System-Using-Text-Files/blob/main/Inventory-Management-System.ipynb">
<img src="https://img.shields.io/badge/Open-Jupyter%20Notebook-F37626?style=for-the-badge&logo=jupyter">
</a>

</p>

---

# 📖 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Workflow](#-workflow)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Installation](#-installation)
- [Usage](#-usage)
- [Notebook Sections](#-notebook-sections)

---

# 📖 Overview

The **Inventory Management System** is a beginner-friendly **console-based Python application** that simulates a real-world inventory and billing system for a small retail shop.

Unlike traditional inventory systems that rely on SQL databases, this project stores all information in plain **`.txt` files**, helping beginners understand how persistent data storage works using Python's built-in file handling capabilities.

The project demonstrates practical implementation of:

- 📂 File Handling
- ✍ CRUD Operations
- 📊 CSV-style Data Parsing
- 📦 Inventory Management
- 🧾 Customer Billing
- 💾 Persistent Data Storage

Every feature is implemented step-by-step inside a **Jupyter Notebook**, making it easy to understand and modify.

---

# ✨ Key Features

## 📦 Inventory Management

| Feature | Description |
|---------|-------------|
| ➕ Add Product | Add new products with Product ID, Name, Price, and Quantity |
| 📋 Read Inventory | Display all available products in a tabular format |
| 🔍 Search Product | Search products by Product ID |
| 🔄 Refill Stock | Increase stock quantity of existing products |
| 📉 Auto Inventory Update | Deduct quantity after every purchase |

---

## 💰 Billing System

| Feature | Description |
|---------|-------------|
| 🛒 Purchase Product | Buy products from available inventory |
| 🧾 Generate Bill | Print customer bill automatically |
| 💵 Total Calculation | Calculate purchase amount |
| 📝 Sales History | Save every sale into `sales.txt` |

---

## 👤 Customer Information

Each completed purchase stores:

- 👤 Customer Name
- 📞 Phone Number
- 📧 Email Address
- 🕒 Purchase Date & Time
- 💵 Total Amount
- 📦 Product Purchased
- 🔢 Quantity Purchased

---

# ⚡ Workflow

```text
                Start
                  │
                  ▼
      Create Inventory File
                  │
                  ▼
         Add New Product
                  │
                  ▼
        Read Inventory File
                  │
                  ▼
        Search Product by ID
                  │
                  ▼
         Purchase Product
                  │
                  ▼
         Generate Customer Bill
                  │
                  ▼
        Update Inventory Stock
                  │
                  ▼
       Store Customer Details
                  │
                  ▼
        Save Sale to sales.txt
                  │
                  ▼
                 End
```

---

# 🛠 Tech Stack

| Technology | Description |
|------------|-------------|
| 🐍 Python 3 | Programming Language |
| 📓 Jupyter Notebook | Development Environment |
| 📂 Text Files | Database |
| 📚 os | File Operations |
| ⏰ datetime | Billing Timestamp |

> **No external libraries required.**

---

# 📂 Project Structure

```text
Mini-Project-Inventory-Management-System-Using-Text-Files/
│
├── 📓 Inventory-Management-System.ipynb
├── 📄 Inventory-of-gadgets.txt
├── 📄 sales.txt
├── 📜 LICENSE
└── 📘 README.md
```

### 📄 File Description

| File | Purpose |
|------|---------|
| Inventory-Management-System.ipynb | Main notebook containing all features |
| Inventory-of-gadgets.txt | Stores product inventory |
| sales.txt | Stores customer sales records |
| README.md | Project documentation |
| LICENSE | MIT License |

---

# ⚙️ Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/vinayakmishra4/Mini-Project-Inventory-Management-System-Using-Text-Files.git
```

---

## 2️⃣ Move into the Project Directory

```bash
cd Mini-Project-Inventory-Management-System-Using-Text-Files
```

---

## 3️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## 4️⃣ Open the Notebook

```
Inventory-Management-System.ipynb
```

Run all notebook cells sequentially from **top to bottom**.

---

# 🚀 Usage

After opening the notebook, execute each section in order.

Every section implements one major feature of the Inventory Management System.

The application automatically creates the required text files if they do not already exist.

---

# 📚 Notebook Sections

| Step | Feature |
|------|----------|
| 1️⃣ | Create Inventory File |
| 2️⃣ | Add Product Details |
| 3️⃣ | Read Inventory File |
| 4️⃣ | Search Product |
| 5️⃣ | Buy Product & Generate Bill |
| 6️⃣ | Update Inventory |
| 7️⃣ | Refill Stock |
| 8️⃣ | Complete Sales System |

---

# 🎯 What You'll Learn

By building this project, you'll gain hands-on experience with:

- ✅ Python File Handling
- ✅ CRUD Operations
- ✅ CSV/Text File Processing
- ✅ Inventory Management Logic
- ✅ Customer Billing System
- ✅ Console Application Development
- ✅ Data Persistence Without SQL
- ✅ Problem Solving Using Python

---

# 💡 Why This Project?

✔ Beginner Friendly

✔ No Database Required

✔ No External Libraries

✔ Easy to Understand

✔ Great Python Practice Project

✔ Ideal for College Mini Projects

✔ Resume & Portfolio Friendly

---
---

# 🎥 Project Demo

> 📽️ Add a short screen recording of your project here.

<p align="center">
  <img src="demo.gif" alt="Project Demo" width="900">
</p>

---

# 📸 Screenshots

## 🏠 Home Screen

<p align="center">
<img src="images/home.png" width="900" alt="Home Screen">
</p>

---

## ➕ Add Product

<p align="center">
<img src="images/add-product.png" width="900" alt="Add Product">
</p>

---

## 📋 Inventory

<p align="center">
<img src="images/inventory.png" width="900" alt="Inventory">
</p>

---

## 🔍 Search Product

<p align="center">
<img src="images/search-product.png" width="900" alt="Search Product">
</p>

---

## 🧾 Billing

<p align="center">
<img src="images/billing.png" width="900" alt="Billing">
</p>

---

## 📄 Sales Record

<p align="center">
<img src="images/sales-history.png" width="900" alt="Sales History">
</p>

---

# 🏆 Project Highlights

- 📦 Inventory Management System
- 🧾 Customer Billing Module
- 📂 File-Based Database
- 📄 CSV-style Text File Storage
- 🐍 Built using Pure Python
- 📓 Jupyter Notebook Implementation
- 🚫 No SQL Database Required
- 🚫 No External Libraries
- 🎯 Beginner Friendly
- 💼 Resume & Portfolio Ready

---

# 📈 Skills Demonstrated

<p align="center">

<img src="https://img.shields.io/badge/Python-100%25-blue?style=for-the-badge&logo=python">

<img src="https://img.shields.io/badge/File%20Handling-Advanced-success?style=for-the-badge">

<img src="https://img.shields.io/badge/CRUD-Operations-orange?style=for-the-badge">

<img src="https://img.shields.io/badge/Problem%20Solving-red?style=for-the-badge">

<img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter">

</p>

---

# 📊 Repository Statistics

<p align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=vinayakmishra4&show_icons=true&theme=tokyonight">

<img height="170" src="https://github-readme-streak-stats.herokuapp.com/?user=vinayakmishra4&theme=tokyonight">

</p>

---

# 🌐 Connect With Me

<p align="center">

<a href="https://github.com/vinayakmishra4">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github">
</a>

<!-- Replace with your LinkedIn URL -->
<a href="https://www.linkedin.com/in/YOUR-LINKEDIN">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin">
</a>

<!-- Replace with your Email -->
<a href="mailto:YOUR_EMAIL@gmail.com">
<img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail">
</a>

</p>

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

4. Push the changes.

```bash
git push origin feature-name
```

5. Open a Pull Request 🚀

---

# ⭐ Show Your Support

If you found this project helpful, please consider:

⭐ Starring this repository

🍴 Forking the repository

🐞 Reporting bugs

💡 Suggesting improvements

---

# 👨‍💻 Author

<div align="center">

## **Vinayak Mishra**

### Python Developer | Data Science Enthusiast

<a href="https://github.com/vinayakmishra4">
<img src="https://img.shields.io/badge/GitHub-vinayakmishra4-181717?style=for-the-badge&logo=github">
</a>

</div>

---

# 📜 License

This project is licensed under the **MIT License**.

Feel free to use, modify, and distribute this project for educational purposes.

---

<div align="center">

# ⭐ Thanks for Visiting!

If you enjoyed this project, don't forget to **Star ⭐ the repository**.

Made with ❤️ using Python

</div>

📦 Inventory Management System (Using Text Files)

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter" alt="Jupyter">
  <img src="https://img.shields.io/badge/Storage-Text%20Files-success?style=for-the-badge" alt="Storage">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
</p>
<p align="center">
  <b>A beginner-friendly Inventory Management & Billing System built using Python and plain text files.</b><br>
  Learn Python file handling, CRUD operations, inventory management, and billing without using SQL or external libraries.
</p>

⸻

🔗 Quick Links

* 🌐 Repository:
    https://github.com/vinayakmishra4/Mini-Project-Inventory-Management-System-Using-Text-Files
* 📓 Jupyter Notebook:
    https://github.com/vinayakmishra4/Mini-Project-Inventory-Management-System-Using-Text-Files/blob/main/Inventory-Management-System.ipynb

⸻

📖 Table of Contents

* Overview
* Features
* Tech Stack
* Project Structure
* Installation
* Usage
* Workflow
* Example
* Data Files
* Learning Outcomes
* Future Improvements
* Screenshots
* Author
* License

⸻

📖 Overview

This project is a console-based Inventory Management System built entirely in Python using plain .txt files as the database.

Instead of using MySQL or SQLite, all product and sales records are stored in text files, making this project ideal for beginners who want to understand:

* 📂 File Handling
* ✍ CRUD Operations
* 📊 CSV-style Data Processing
* 🧾 Billing System Logic
* 🐍 Python Fundamentals

The complete implementation is available inside a Jupyter Notebook, where each feature is explained and implemented step-by-step.

⸻

✨ Features

📦 Inventory Management

* ➕ Add New Products
* 📋 View Inventory
* 🔍 Search Products by ID
* 🔄 Refill Existing Stock
* 📉 Automatically Update Stock After Purchase

💰 Billing System

* 🛒 Buy Products
* 🧾 Generate Customer Bill
* 💵 Calculate Total Amount
* 📝 Save Sales History

👤 Customer Information

Each purchase records:

* Customer Name
* Phone Number
* Email Address
* Purchase Date & Time

All records are stored automatically in sales.txt.

⸻

🛠 Tech Stack

Technology	Purpose
Python 3	Programming Language
Jupyter Notebook	Development Environment
os	File Handling
datetime	Billing Timestamp
Text Files	Database

No external libraries or database required.

⸻

📁 Project Structure

Mini-Project-Inventory-Management-System-Using-Text-Files/
│
├── Inventory-Management-System.ipynb
├── Inventory-of-gadgets.txt
├── sales.txt
├── LICENSE
└── README.md

⸻

⚙️ Installation

Clone the repository

git clone https://github.com/vinayakmishra4/Mini-Project-Inventory-Management-System-Using-Text-Files.git

Move into the project directory

cd Mini-Project-Inventory-Management-System-Using-Text-Files

Launch Jupyter Notebook

jupyter notebook

Open

Inventory-Management-System.ipynb

Run all notebook cells from top to bottom.

⸻

🚀 Usage

The notebook is divided into multiple sections.

Step	Function
1	Create Inventory File
2	Add Product
3	Read Inventory
4	Search Product
5	Buy Product & Generate Bill
6	Update Inventory
7	Refill Stock
8	Complete Sales System

⸻

🔄 Workflow

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

⸻

💻 Example

➕ Add Product

Enter Product ID: 3
Enter Product Name: iPad Air
Enter Product Price: 55000
Enter Product Quantity: 15
Product Added Successfully ✔

Stored as

3,iPad Air,55000,15

⸻

📋 Inventory

---------------------------------------------------------
Product ID   Product Name      Price       Quantity
---------------------------------------------------------
1            iPhone 15         79999       20
2            Samsung S24       68999       12
3            iPad Air          55000       15
---------------------------------------------------------

⸻

🧾 Purchase

Customer Name : Rahul
Product ID : 2
Quantity : 2
Total Amount : ₹137998
Purchase Successful ✔

The inventory is updated automatically and the sale is recorded in sales.txt.

⸻

📂 Data Files

Inventory File

Inventory-of-gadgets.txt

product_id,product_name,product_price,product_quantity

Example

1,iPhone 15,79999,20
2,Samsung S24,68999,12
3,iPad Air,55000,15

⸻

Sales File

sales.txt

timestamp,
product_id,
product_name,
quantity_sold,
total_amount,
customer_name,
customer_phone,
customer_email

⸻

🎯 Learning Outcomes

This project demonstrates:

* Python File Handling
* CRUD Operations
* Text File Database Design
* CSV Data Parsing
* Inventory Management Logic
* Billing System Development
* Customer Record Management
* Console-Based Application Design

⸻

🚀 Future Improvements

* ✅ Convert Notebook into a Python Package
* ✅ Menu-Driven CLI Application
* ✅ Object-Oriented Programming (OOP)
* ✅ SQLite Database Integration
* ✅ Delete Product Feature
* ✅ Edit Product Details
* ✅ Duplicate Product Validation
* ✅ Input Validation
* ✅ Low Stock Alerts
* ✅ Sales Analytics Dashboard
* ✅ Export Bills as PDF
* ✅ GUI using Tkinter or PyQt

⸻

📸 Screenshots

You can add screenshots here for a more attractive repository.

📷 Home Menu
📷 Add Product
📷 Inventory List
📷 Billing Screen
📷 Sales History

⸻

🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch

git checkout -b feature-name

3. Commit your changes

git commit -m "Add new feature"

4. Push to GitHub

git push origin feature-name

5. Open a Pull Request 🚀

⸻

👨‍💻 Author

Vinayak Mishra

GitHub:
https://github.com/vinayakmishra4

If you found this project useful, consider giving it a ⭐ on GitHub.

⸻

📜 License

This project is licensed under the MIT License.

You are free to use, modify, and distribute this project for educational purposes.

⸻

<p align="center">
⭐ If you like this project, don't forget to star the repository! ⭐
</p>
<p align="center">
Made with ❤️ using Python
</p>

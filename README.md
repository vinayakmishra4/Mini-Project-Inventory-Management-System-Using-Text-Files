# 📦 Mini Project - Inventory Management System With Files

---

## 📌 Overview

The **Inventory Management System With Files** is a Python-based application designed to manage small to medium-sized product inventories using simple text files for storage.  
This project is implemented in **Jupyter Notebook** and demonstrates **file handling, structured data management, and basic business logic** in Python.

The system can:
- Store product information (ID, Name, Price, Quantity).
- Track available stock levels.
- Process retail and wholesale purchases.
- Log all wholesale transactions with customer details.
- Update and refill inventory in real-time.

This project is ideal for beginners learning **Python file I/O** and **inventory-based problem solving**.

---

## 🚀 Features

1. **Add Products**  
   - Add new products by entering Product ID, Name, Price, and Quantity.  
   - Stores data in `Inventory-of-gadgets.txt` in CSV format.

2. **View Inventory**  
   - Displays all available products in a table format.  
   - Shows Product ID, Name, Price, and Quantity.

3. **Search Product**  
   - Search by **Product ID** and display details instantly.

4. **Buy Product (Retail)**  
   - Purchase items by specifying name and quantity.  
   - Generates a bill based on product price and quantity.  
   - Handles insufficient stock by offering available quantity.

5. **Update Inventory**  
   - Automatically updates the product quantity after a sale.

6. **Refill Stock**  
   - Add more units to an existing product’s quantity.

7. **Wholesale Sales**  
   - Accepts **customer details** (Name, Phone, Email).  
   - Processes bulk purchases and updates inventory.  
   - Saves a record of every wholesale sale in `sales.txt` with a timestamp.

8. **Sales Logging**  
   - Logs wholesale transactions with customer details for record keeping.

---

## 🛠️ Technologies Used

- Python 3  
- Jupyter Notebook  
- File I/O (text files)  
- CSV Format for structured data

---

## 📂 File Structure

Inventory-Management-System.ipynb   # Main Jupyter Notebook containing code
Inventory-of-gadgets.txt            # Product inventory file (CSV format)
sales.txt                           # Wholesale sales log file
README.md                           # Project documentation

---

## ⚙️ How It Works

- On first run, the system checks if `Inventory-of-gadgets.txt` exists; if not, it creates it.
- Products are stored as comma-separated lines in the format:  
  `ProductID,ProductName,Price,Quantity`
- Inventory can be viewed, searched, and updated with purchases.
- Wholesale sales capture customer info and log transactions with timestamps.

---

## 📖 Usage Instructions

1. Open the project in **Jupyter Notebook**.  
2. Run the "Make inventory file" cell to initialize the data file.  
3. Use the functions provided to:  
   - Add new products  
   - View current inventory  
   - Search products by ID  
   - Buy products (retail or wholesale)  
   - Refill stock  
4. Review `sales.txt` for wholesale transaction records.

---

## ⚠️ Limitations

- Uses plain text files — not suitable for large-scale or multi-user systems.  
- Minimal input validation; improper input can cause errors.  
- Command-line/Jupyter only; no graphical interface.  
- Duplicate Product IDs are possible (no uniqueness enforced).

---

## 📌 Future Improvements

- Implement a **main menu** for easier navigation.  
- Use Python’s `csv` module for safer file operations.  
- Add robust **error handling** and input validation.  
- Replace text files with an **SQLite database** backend.  
- Develop a **GUI** using Tkinter or PyQt.  
- Enforce **unique Product IDs** to prevent duplicates.

---

## 🔗 Source Code

View the complete Jupyter Notebook on GitHub:  
[Inventory-Management-System.ipynb](https://github.com/vinayakmishra4/Mini-Project-Inventory-Management-System-Using-Text-Files/blob/main/Inventory-Management-System.ipynb)

---

👨‍💻 *Author:* Vinayak  
📅 *Created:* 2025
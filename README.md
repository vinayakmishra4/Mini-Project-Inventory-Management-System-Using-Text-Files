# 📦 Mini Project - Inventory Management System With Files

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
### 1. **Add Products**
   - Add new products by entering Product ID, Name, Price, and Quantity.
   - Stores data in `Inventory-of-gadgets.txt` in CSV format.

### 2. **View Inventory**
   - Displays all available products in a table format.
   - Shows Product ID, Name, Price, and Quantity.

### 3. **Search Product**
   - Search by **Product ID** and display details instantly.

### 4. **Buy Product (Retail)**
   - Purchase an item by specifying its name and quantity.
   - Generates a **bill** based on product price and quantity.
   - Handles insufficient stock gracefully by offering available quantity.

### 5. **Update Inventory**
   - Automatically updates the product quantity after a sale.

### 6. **Refill Stock**
   - Add more units to an existing product’s quantity.

### 7. **Wholesale Sales**
   - Accepts **customer details** (Name, Phone, Email).
   - Processes bulk purchases and updates inventory.
   - Saves a record of every wholesale sale in `sales.txt` with a timestamp.

### 8. **Sales Logging**
   - Logs wholesale transactions with customer details for record keeping.

---

## 🛠️ Technologies Used
- **Python 3** — Core programming language.
- **Jupyter Notebook** — Development and execution environment.
- **File I/O** — For reading and writing data to `.txt` files.
- **CSV Format** — Used for simple structured data storage.

---

## 📂 File Structure
```
Inventory-Management-System.ipynb   # Main Jupyter Notebook containing code
Inventory-of-gadgets.txt            # Product inventory file (CSV format)
sales.txt                           # Wholesale sales log file
README.md                           # Project documentation
```

---

## ⚙️ How It Works
1. **Initialization**
   - On first run, the notebook checks if `Inventory-of-gadgets.txt` exists.
   - If not found, it creates the file.

2. **Adding Products**
   - Each product is stored as:
     ```
     ProductID,ProductName,Price,Quantity
     ```
   - Example:
     ```
     101,Mouse,500,20
     ```

3. **Viewing & Searching**
   - Inventory is displayed in columns with proper alignment.
   - Searching filters by Product ID.

4. **Buying Process**
   - Checks stock availability.
   - Calculates total cost.
   - Updates inventory immediately after purchase.

5. **Wholesale Process**
   - Similar to buying but also records **customer information**.
   - Logs sale into `sales.txt` with date and time.

---

## 📖 Usage
1. **Open** the project in Jupyter Notebook.
2. **Run the "Make inventory file" cell** to initialize data storage.
3. Use:
   - **Add Product** to insert new items.
   - **Read Inventory** to display all items.
   - **Search Product** to find specific products.
   - **Buy Product** to process retail sales.
   - **Refill Stock** to add inventory for existing products.
   - **Wholesale Sales** for bulk purchases with logging.
4. Check `sales.txt` for wholesale transaction records.

---

## ⚠️ Limitations
- **No database** — uses plain text files, which are not suitable for large-scale systems.
- **Minimal validation** — incorrect inputs (like letters for quantity) may cause errors.
- **Command-line/Jupyter only** — no graphical user interface.
- **Duplicate product IDs** can be entered (no unique ID enforcement).

---

## 📌 Future Improvements
- Implement a **main menu** for easy navigation.
- Use Python's `csv` module to handle file operations more reliably.
- Add **error handling** for invalid inputs.
- Replace text files with an **SQLite database**.
- Build a **Tkinter or PyQt GUI**.
- Enforce **unique Product IDs**.

---

## 📜 Source Code
You can view the complete Jupyter Notebook here:  
[**Inventory-Management-System.ipynb**](https://github.com/vinayakmishra4/Mini-Project-Inventory-Management-System-Using-Text-Files/blob/main/Inventory-Management-System.ipynb)

---
💡 *Author:* Vinayak 
📅 *Created:* 2025  

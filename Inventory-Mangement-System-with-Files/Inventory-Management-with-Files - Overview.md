# 📦 Inventory Management System Using Text Files

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Status](https://img.shields.io/badge/status-complete-brightgreen)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

## 📖 Overview

This is a beginner-friendly **Inventory Management System** built with Python using simple text files for data storage. It's perfect for those new to programming or anyone looking to understand basic file handling without using databases.

---

## 🧩 Key Features

- Add, view, and count inventory items
- Track essential details: Product ID, Name, Price, Quantity
- File creation and data persistence using plain text files
- Beginner-friendly with readable code and markdown instructions

---

## 🗂️ Project Structure

```
📁 Inventory-Management-System
├── 📄 README.md
├── 📓 Inventory Management with Files - Overview.ipynb
└── 📄 inventory.txt
```

---

## ⚙️ Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Inventory-Management-System.git
   cd Inventory-Management-System
   ```

2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook "Inventory Management with Files - Overview.ipynb"
   ```

3. Follow the instructions in the notebook to interact with the inventory system.

---

## ✅ Requirements

- Python 3.7+
- Jupyter Notebook

Install Jupyter via pip:
```bash
pip install notebook
```

---

## 📌 Future Improvements

- Switch to CSV or JSON for better structure
- Add a search/update/delete feature
- Implement a GUI using Tkinter or PyQt
- Upgrade to use SQLite or MongoDB

---

## 📝 License

This project is licensed under the MIT License.

---

# 📦✨ Inventory Management System Using Text Files in Python

Welcome to this simple **Inventory Management System** project! This guide will walk you through building a basic inventory tracker using plain text files and Python — no complex databases required.

---

## ❓ What is an Inventory Management System?

An **Inventory Management System** is software designed to help businesses track products, stock levels, sales, and transactions. It ensures you always know:

* How many products you have  
* Product prices  
* Total sales  
* Customer details  

This system is crucial for shops and businesses that want to automate and streamline their inventory tracking process.

---

## 🧩 Key Components of the Inventory System

Each product in the system includes:

| Component         | Description                        |
| ----------------- | ---------------------------------- |
| **Product ID**    | Unique identifier for each product |
| **Product Name**  | Name of the product                |
| **Product Price** | Cost of the product                |
| **Quantity**      | Number of units currently in stock |

You can expand the system by adding more details like manufacturing date, expiry date, and product category.

---

## 💾 Why Use Text Files?

Instead of databases like MySQL, MongoDB, or even JSON files, this beginner-friendly approach uses simple text files to:

* Learn how data storage works fundamentally  
* Understand how to read, write, and process data  
* Prepare for more advanced systems later  

---

## 🚀 Getting Started: Create Your Inventory File

```python
# Create inventory.txt and add initial products
with open("inventory.txt", "w") as file:
    file.write("1, Chocolate, 5, 100\n")
    file.write("2, Milky Bar, 10, 50\n")
    file.write("3, Cake, 300, 5\n")
    file.write("4, Candy, 1, 200\n")
```

Each line represents a product with **Product ID, Name, Price, and Quantity**, separated by commas.

---

## 📖 Reading Inventory Data

```python
with open("inventory.txt", "r") as file:
    data = file.read()

print(data)
```

Output:

```
1, Chocolate, 5, 100
2, Milky Bar, 10, 50
3, Cake, 300, 5
4, Candy, 1, 200
```

---

## 🔢 Counting Unique Products

```python
products = data.splitlines()
unique_products = len(products)
print(f"Total unique products: {unique_products}")
```

Output:

```
Total unique products: 4
```

---

## ✅ Best Practices When Using Text Files

* **No empty lines:** Avoid extra new lines after the last entry.  
* **Consistent format:** Always use the same format for easy parsing later.  
* **Data validation:** Ensure data types like price and quantity are correct before saving.  

---

## 🏷️ Understanding Product IDs and Barcodes

* **Product ID:** A unique number identifying each product.  
* **Barcodes:** Businesses often use barcodes to scan product IDs quickly.  
* **Efficiency:** Scanning barcodes speeds up sales and inventory updates.  

### Barcode Example

```
| || | || || | | || ||  |
```

Each barcode corresponds to a unique product ID, enabling fast and error-free transactions.

---

## 🔜 What’s Next?

After mastering this text-file-based system, you can upgrade to:

* Using **CSV** or **JSON** for better data handling  
* Implementing **databases** like SQLite or MongoDB  
* Adding a user interface for easier management  
* Integrating barcode scanning hardware  

---

# 🎉 Thank You for Exploring This Project!

Building this basic Inventory Management System is a great first step to mastering inventory tracking software. 💡 Feel free to experiment, have fun, and make this project your own!
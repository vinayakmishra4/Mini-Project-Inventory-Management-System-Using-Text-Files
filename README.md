<div align="center">

# 📦 Inventory Management System
### *Using Text Files*

**A lightweight, dependency-free console inventory & billing system built in pure Python.**

No database. No frameworks. Just `.txt` files and clean file I/O.

![Python](https://img.shields.io/badge/Python-3-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Mini%20Project-blue?style=for-the-badge)

</div>

---

## 🧠 Overview

This is a mini project that simulates a basic inventory and billing system for a small shop. Instead of using a database, it stores all product and sales records in plain `.txt` files (`Inventory-of-gadgets.txt` and `sales.txt`), making it a great hands-on introduction to file handling, CRUD operations, and CSV-style data parsing in Python. The entire system is implemented step-by-step inside a Jupyter Notebook, with each core feature (add, read, search, sell, restock) broken into its own labeled section — so anyone reading it can follow the logic feature by feature.

> 💡 **Why text files?** It strips away the complexity of databases and ORMs so the focus stays entirely on core Python skills: reading/writing files, parsing structured strings, and managing state without a framework doing the work for you.

## ✨ Features

| Feature | Description |
|---|---|
| ➕ **Add Product** | Add new products with ID, name, price, and quantity to the inventory file |
| 📋 **Read Inventory** | View all products currently in stock in a clean tabular format |
| 🔍 **Search Product** | Look up a product by its ID |
| 🧾 **Buy & Generate Bill** | Process a sale, calculate the total, and print a bill |
| 🔁 **Update Inventory** | Automatically deduct sold quantity from stock after a purchase |
| 📥 **Refill Stock** | Restock existing products by adding to their current quantity |
| 🧑‍🤝‍🧑 **Customer Billing** | Capture customer name, phone, and email for each sale, logged to `sales.txt` |

## 🛠️ Tech Stack

<div align="center">

| Layer | Technology |
|---|---|
| Language | Python 3 |
| Environment | Jupyter Notebook |
| Libraries | `os`, `datetime` *(standard library only — zero external dependencies)* |
| Storage | Plain `.txt` files used as a flat-file database |

</div>

## 🔄 How It Works

```
                ┌─────────────────────┐
                │  Inventory-of-       │
                │  gadgets.txt         │◄──────────────┐
                └─────────┬────────────┘                │
                          │                              │
        ┌─────────────────┼─────────────────┐            │
        ▼                 ▼                 ▼            │
   ➕ Add Product    📋 Read Inventory   🔍 Search       │
                                                          │
                          │                              │
                          ▼                              │
                 🧾 Buy Product & Bill                    │
                          │                               │
                          ▼                               │
                 🔁 Update Inventory  ─────────────────────┘
                          │
                          ▼
                ┌─────────────────────┐
                │   sales.txt          │
                │  (billing records)   │
                └─────────────────────┘
```

## 🚀 Installation

No dependencies to install — this project only uses Python's standard library.

```bash
# Clone the repository
git clone https://github.com/vinayakmishra4/Mini-Project-Inventory-Management-System-Using-Text-Files.git

# Move into the project folder
cd Mini-Project-Inventory-Management-System-Using-Text-Files

# Launch Jupyter Notebook
jupyter notebook
```

## ▶️ Usage

📓 **[View the full notebook source code here →](https://github.com/vinayakmishra4/Mini-Project-Inventory-Management-System-Using-Text-Files/blob/main/Inventory-Management-System.ipynb)**

Open `Inventory-Management-System.ipynb` in Jupyter and run the cells **in order, from top to bottom**. Each section is labeled with a markdown header describing the feature it implements:

```text
1. Making inventory file   → creates Inventory-of-gadgets.txt if it doesn't exist
2. Add Product Details     → prompts for ID, name, price, quantity and saves it
3. Read the Inventory File → displays all current stock in a table
4. Search the Product      → look up a product by ID
5. Buy Product & Bill      → sell a product and generate a bill
6. Update Inventory        → updates stock quantity after a sale
7. Refill Stock            → add more quantity to an existing product
8. Whole Sales             → full checkout flow with customer name, phone, email
```

Example of adding a product (run via the "Add Product" cell):

```text
Enter the Product ID: 3
Enter the Product Name: iPad Air
Enter the Product Price: 55000
Enter the Product Quantity: 15
Product Added Successfully with Product ID: 3
```

This appends a new line to `Inventory-of-gadgets.txt` in the format:

```text
3,iPad Air,55000,15
```

## 📂 Project Structure

```
Mini-Project-Inventory-Management-System-Using-Text-Files/
├── [Inventory-Management-System.ipynb](https://github.com/vinayakmishra4/Mini-Project-Inventory-Management-System-Using-Text-Files/blob/main/Inventory-Management-System.ipynb)   # Main notebook with all features
├── Inventory-of-gadgets.txt            # Product inventory data (id, name, price, quantity)
├── sales.txt                           # Sales/billing records (timestamp, id, name, qty, total, customer info)
├── LICENSE                             # MIT License
└── README.md                           # Project documentation
```

## 🗃️ Dataset / Data Source

Both data files are plain CSV-style `.txt` files generated and updated by the notebook itself — there's no external dataset.

**`Inventory-of-gadgets.txt`** — one row per product:
```
product_id,product_name,product_price,product_quantity
```

**`sales.txt`** — one row per completed sale:
```
timestamp,product_id,product_name,quantity_sold,total_amount,customer_name,customer_phone,customer_email
```

## 🧭 Future Improvements

- Refactor notebook cells into a single reusable `.py` module with proper functions and a menu-driven CLI loop
- Replace flat `.txt` storage with SQLite for safer concurrent reads/writes and data integrity
- Add input validation (e.g. reject negative prices/quantities, handle duplicate product IDs)

## 👤 Author

<div align="center">

**Vinayak Mishra**

[![GitHub](https://img.shields.io/badge/GitHub-vinayakmishra4-181717?style=for-the-badge&logo=github)](https://github.com/vinayakmishra4)

</div>

## 📄 License

This project is licensed under the [MIT License](LICENSE) — free to use, modify, and learn from.

---

<div align="center">

⭐ *If this project helped you understand file-based data handling in Python, consider giving it a star!*

</div>

# 📦 Inventory Management System (File-Based)

*A Mini Project by Vinayak Mishra*

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Status](https://img.shields.io/badge/Status-Educational-lightgrey)
![License](https://img.shields.io/badge/License-MIT-green)

## 📑 Table of Contents

- [Overview](#-overview)
- [What Can It Do?](#-what-can-it-do)
- [Key Features](#-key-features)
- [Technologies Used](#️-technologies-used)
- [Prerequisites](#-prerequisites)
- [Installation](#️-installation)
- [Project Structure](#️-project-structure)
- [How It Works](#-how-it-works)
- [Example Usage](#-example-usage)
- [Known Limitations](#️-known-limitations)
- [Future Enhancements](#-future-enhancements)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🚀 Overview

Welcome to the **Inventory Management System (File-Based)** — a simple yet powerful Python application designed to help you manage small to medium-sized inventories using plain text files!

Perfect for beginners, this project teaches you essential **file handling**, **structured data management**, and **basic business logic** concepts in Python, all within a clean, easy-to-understand Jupyter Notebook environment.

## 🔍 What Can It Do?

- **Add new products** with unique ID, name, price, and stock quantity.
- **View the entire inventory** in a neat, tabulated format.
- **Search products** instantly by Product ID.
- **Handle retail purchases** smoothly with live stock updates.
- **Manage wholesale sales** by recording customer details and bulk orders.
- **Automatically update stock levels** and maintain accurate inventory.
- **Keep detailed sales logs** with timestamps for transparency and tracking.

## ✨ Key Features

| Feature | Description |
|---|---|
| **Add Products** | Add new items quickly with ID, name, price, and quantity |
| **View Inventory** | See all products in a clean table format |
| **Search Product** | Find any product by its unique ID |
| **Buy Product (Retail)** | Purchase by name and quantity with live stock check |
| **Update Inventory** | Inventory updates instantly after every sale |
| **Refill Stock** | Easily restock existing products |
| **Wholesale Sales** | Process bulk orders with customer info and save transaction logs |
| **Sales Logging** | Detailed logs for all wholesale transactions with timestamps |

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook
- File I/O (Text Files & CSV Format)
- Timestamp Logging (`datetime` module)

## 📋 Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- No external libraries required — uses only Python's built-in `os` and `datetime` modules

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/vinayakmishra4/Mini-Project-Inventory-Management-System-Using-Text-Files.git
   cd Mini-Project-Inventory-Management-System-Using-Text-Files
   ```

2. Install Jupyter if you don't already have it:
   ```bash
   pip install notebook
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook Inventory-Management-System.ipynb
   ```

4. Run all cells from top to bottom. The first cell checks for `Inventory-of-gadgets.txt` and creates it automatically if it doesn't exist yet.

## 🗂️ Project Structure

| File Name | Purpose |
|---|---|
| `Inventory-Management-System.ipynb` | Main Jupyter Notebook with all the code |
| `Inventory-of-gadgets.txt` | Stores product inventory in CSV format |
| `sales.txt` | Logs wholesale sales and customer transactions |
| `README.md` | Project documentation |

## 🎯 How It Works

- Checks if `Inventory-of-gadgets.txt` exists on startup; creates it if missing.
- Stores products as comma-separated values:
  `ProductID,ProductName,Price,Quantity`
- Enables quick viewing, searching, buying, and restocking of products.
- Captures customer details for wholesale sales and records transactions with timestamps in `sales.txt`.

## 💡 Example Usage

Once the notebook is running, use the provided functions directly in a cell:

```python
# Add a new product
add_product("101", "Wireless Mouse", 499, 25)

# View current inventory
view_inventory()
# Output:
# ProductID   ProductName       Price   Quantity
# 101         Wireless Mouse    499     25

# Search for a product by ID
search_product("101")
# Output: Found -> Wireless Mouse | Price: 499 | Stock: 25

# Process a retail purchase
buy_product("Wireless Mouse", 2)
# Output: Sale successful. Wireless Mouse stock updated to 23.

# Refill stock
refill_stock("101", 50)
# Output: Stock refilled. Wireless Mouse now has 73 units.
```

Wholesale transactions additionally prompt for customer details and are appended to `sales.txt` with a timestamp.

## ⚠️ Known Limitations

- Uses plain text files — not optimized for large or multi-user environments.
- Minimal input validation — incorrect inputs may cause errors.
- Command-line/Jupyter interface only — no GUI yet.
- No enforcement of unique Product IDs (duplicates possible).

## 🚀 Future Enhancements

- Build a **main menu** for easier navigation.
- Switch to Python's built-in `csv` module for safer file handling.
- Add robust **input validation and error handling**.
- Migrate from text files to an **SQLite database** backend.
- Create a **GUI interface** using Tkinter or PyQt.
- Enforce **unique Product IDs** to avoid duplicates.

## 🤝 Contributing

This is a learning project, but suggestions and pull requests are always welcome! Feel free to fork the repo, experiment, and submit improvements.

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

## 📬 Contact

**Vinayak Mishra**
- GitHub: [@vinayakmishra4](https://github.com/vinayakmishra4)
- Project Repo: [Mini-Project-Inventory-Management-System-Using-Text-Files](https://github.com/vinayakmishra4/Mini-Project-Inventory-Management-System-Using-Text-Files)
- Feel free to open an issue on the repo for questions, bugs, or suggestions.

---

**Author:** Vinayak Mishra · **Created:** 2025

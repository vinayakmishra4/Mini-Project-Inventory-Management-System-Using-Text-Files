# 📦 Inventory Management with Files – Updating Inventory

Welcome to the **Inventory Management** system that helps you keep your stock accurate and up-to-date! This lightweight, file-based solution allows you to manage product inventory efficiently by updating stock levels right after each purchase.

---

## 🔍 Overview

Maintaining accurate inventory is **critical** for any business to avoid overselling, streamline operations, and boost customer satisfaction. This project demonstrates how to update product quantities stored in a simple text file (`inventory.txt`) after every purchase.

---

## 🗂️ Inventory File Format

The inventory is stored in a plain text file with each product represented by a line:

```
ProductID,ProductName,ProductPrice,Quantity
```

**Sample inventory:**

```
1,Chocolate,5,100
2,Milky Bar,10,50
3,Cake,300,5
4,Candy,1,200
```

---

## ⚙️ How It Works

### Step 1: Load Inventory  
Read the current product details from the file into memory.

### Step 2: Input Purchase Details  
Prompt the user for the Product ID and purchase quantity.

### Step 3: Update Stock  
- Find the product by Product ID.  
- Subtract the purchased quantity from the current stock.  
- Calculate and display the billing amount.

### Step 4: Save Updates  
Write the updated inventory back to the file, reflecting the new stock levels.

---

## 🎯 Why Update Inventory?

- Prevent overselling by tracking stock in real-time.  
- Improve inventory accuracy and customer experience.  
- Provide clear billing and transaction transparency.  
- Lay a foundation for more advanced inventory features.

---

## 💡 Features

- Simple, human-readable file-based storage  
- Clear, step-by-step inventory update flow  
- Automatic billing calculation  
- Easy to extend and customize  
- Great for small to medium-sized inventories

---

## 🛠️ Getting Started

1. Clone the repo:  
   ```bash
   git clone https://github.com/your-repo/inventory-management-update.git
   ```

2. Make sure you have `inventory.txt` formatted as described.

3. Run the program and follow the prompts to update your inventory.

---

## 📂 Sample Output

```
Enter product ID: 1
Enter product Quantity: 3
-----------------------------
Product Name     : Chocolate
Price            : 5
Quantity Purchased: 3
-----------------------------
Billing Amount   : 15
-----------------------------
```

---

## 🔗 Code & Resources

Explore the full source code and examples here:  
**[Inventory Management with Files - Updating Inventory Code](https://github.com/your-repo/inventory-management-update)**

---

## 🙌 Contributing

Feel free to open issues or submit pull requests to improve the system! Suggestions for features like error handling, GUI integration, and database support are welcome.

---

## 📄 License

This project is licensed under the MIT License.

---

Thanks for stopping by! Keep your inventory sharp and your customers happy. 🚀

# 🛒 Online Shopping Cart

## 📌 Project Overview

The **Online Shopping Cart** is a Python-based console application that allows users to manage products in a shopping cart and calculate the final bill.

The project is developed using **Object-Oriented Programming (OOP)** concepts in Python. It provides a simple menu-driven interface where users can add products, remove products, display the cart, and calculate the final purchase amount.

---

## 🎯 Objectives

The main objectives of this project are:

* To create a simple online shopping cart system using Python.
* To practice Object-Oriented Programming concepts.
* To add products to a shopping cart.
* To remove products from the cart.
* To display the products and their quantities.
* To calculate the subtotal of products.
* To apply a discount when the purchase amount exceeds ₹5,000.
* To calculate 18% GST.
* To display the final bill.
* To practice Python classes, methods, loops, conditions, lists, and dictionaries.

---

## 🛠️ Technologies Used

* **Python**
* Object-Oriented Programming (OOP)
* Lists
* Dictionaries
* Functions/Methods
* Conditional Statements
* Loops
* User Input

---

## 🗄️ Project Structure

```text
Online-Shopping-Cart/
│
├── shopping_cart.py
└── README.md
```

---

## ⚙️ Features

### 1. Add Product

The user can enter:

* Product name
* Product price
* Product quantity

The product is then added to the shopping cart.

### 2. Remove Product

The user can enter the product name and remove it from the cart.

### 3. Display Cart

The application displays:

* Product name
* Product price
* Product quantity

### 4. Calculate Bill

The application calculates the total cost of all products.

The calculation includes:

```text
Subtotal
    ↓
10% Discount (if subtotal > ₹5,000)
    ↓
18% GST
    ↓
Final Amount
```

### 5. Exit

The user can exit the application by selecting the Exit option.

---

## 💰 Billing Logic

The project uses the following billing rules:

### Subtotal

```text
Subtotal = Price × Quantity
```

for every product in the cart.

### Discount

If the subtotal is greater than ₹5,000:

```text
Discount = Subtotal × 10%
```

Otherwise:

```text
Discount = ₹0
```

### GST

After applying the discount:

```text
GST = Amount After Discount × 18%
```

### Final Amount

```text
Final Amount = Amount After Discount + GST
```

These rules are implemented in the `calculate_bill()` method.

---

## 🧱 Class Used

### `ShoppingCart`

The project contains a `ShoppingCart` class.

```python
class ShoppingCart:
```

The class stores products in a cart using a list.

### Main Methods

| Method             | Purpose                                             |
| ------------------ | --------------------------------------------------- |
| `add_product()`    | Adds a product to the cart                          |
| `remove_product()` | Removes a product                                   |
| `display_cart()`   | Displays cart contents                              |
| `calculate_bill()` | Calculates subtotal, discount, GST and final amount |

These methods are defined inside the `ShoppingCart` class.

---

## 🧠 Python Concepts Used

### Classes and Objects

The project creates a `ShoppingCart` class and an object:

```python
cart = ShoppingCart()
```

### Lists

A list is used to store products:

```python
self.cart = []
```

### Dictionaries

Each product is stored as a dictionary containing:

```python
{
    "name": name,
    "price": price,
    "quantity": quantity
}
```

### Loops

A `while` loop keeps the shopping-cart menu running until the user chooses Exit.

### Conditional Statements

`if`, `elif`, and `else` are used to process menu choices and calculate discounts.

### User Input

The `input()` function is used to collect product and menu information from the user.

---

## ▶️ How to Run the Project

### Step 1: Install Python

Make sure Python is installed on your computer.

Check the installation:

```bash
python --version
```

### Step 2: Save the Code

Save the Python program as:

```text
shopping_cart.py
```

### Step 3: Open Terminal

Navigate to the folder containing the Python file.

### Step 4: Run the Program

```bash
python shopping_cart.py
```

### Step 5: Use the Menu

The program provides the following options:

```text
===== ONLINE SHOPPING CART =====
1. Add Product
2. Remove Product
3. Display Cart
4. Calculate Bill
5. Exit
```

The menu and these operations are implemented in the project code.

---

## 📊 Example Workflow

```text
Add Product
     ↓
Enter Product Name
     ↓
Enter Price
     ↓
Enter Quantity
     ↓
Product Added
     ↓
Display Cart
     ↓
Calculate Bill
     ↓
Discount
     ↓
GST
     ↓
Final Amount
```

---

## 🎓 Learning Outcome

After completing this project, the developer gains practical experience in:

* Python programming
* Object-Oriented Programming
* Classes and objects
* Lists and dictionaries
* Loops and conditions
* User input handling
* Basic billing calculations
* Building a menu-driven application

---

## 👨‍💻 Author

**Muhammed Abnas**

Data Science Student

---

## 📜 License

This project is created for **educational and learning purposes**.# Online-Shopping-Car

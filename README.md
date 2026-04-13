# 📊 Portfolio Calculator (Python)

A simple Python-based portfolio calculator that computes the total value of your investments and provides a breakdown of individual holdings.

---

## 🚀 Project Overview

This project demonstrates basic portfolio value calculation using Python. It includes:

* A **static example** with predefined stock prices and shares
* An **interactive version** where users input values manually
* Calculation of **individual stock value + total portfolio value**

This is a beginner-friendly project focused on **loops, lists, and user input handling in Python**.

---

## ✨ Features

* 📌 Calculate total portfolio value
* 📌 Input stock prices and quantities manually
* 📌 View per-stock breakdown
* 📌 Simple and easy-to-understand logic

---

## 🧠 How It Works

### 1. Static Portfolio Calculation

The notebook first demonstrates a hardcoded example:

```python
shares = 10, 2
prices = 150.25, 800.50
```

It loops through both tuples, calculates individual values, and sums them:

```
value = shares[i] * prices[i]
```

---

### 2. User Input Version

The second part allows dynamic input:

* User enters price and shares for 3 stocks
* Values are stored in lists
* Loop calculates each stock’s value

Example output:

```
---portfolio breakdown---
share1 * ₹150 = ₹1500
share2 * ₹200 = ₹4000

total portfolio value: ₹5500
```

---

## 🛠️ Technologies Used

* Python 3
* Jupyter Notebook

---

## 📂 Project Structure

```
Portfolio_calculator.ipynb   # Main notebook with all logic
```

---

## ▶️ How to Run

### Option 1: Jupyter Notebook

1. Open:

   ```
   Portfolio_calculator.ipynb
   ```
2. Run all cells
3. Enter inputs when prompted

### Option 2: Python Script

You can convert the notebook into a `.py` file and run:

```bash
python portfolio.py
```

---

## ⚠️ Current Limitations

* Fixed number of stocks (3 in input version)
* No real-time stock price integration
* No data persistence (everything resets each run)
* No validation for incorrect input

---

## 🔮 Future Improvements (Based on Current Code)

These are **natural next steps from your current implementation**:

* Allow unlimited stocks using a `while` loop
* Add percentage allocation calculation
* Store data using dictionaries (`{stock: shares}`)
* Add input validation
* Integrate real-time prices using APIs like:

  * Yahoo Finance (via `yfinance`)
* Export results to CSV

---


# Coffee Shop Order System

A C++ console application that simulates a coffee shop point-of-sale system. This program handles menu selection, input validation, membership discounts, and tax calculations to generate a formatted customer receipt.

## 📋 Features

- **Interactive Menu:** Choose from Espresso, Latte, Cappuccino, or Mocha.
- **Input Validation:** Ensures the number of cups is a positive integer and membership status is correctly formatted (Y/N).
- **Dynamic Calculations:** 
  - Calculates subtotal based on item price.
  - Applies a **5% membership discount** for loyal customers.
  - Calculates a **6% sales tax**.
- **Formatted Receipt:** Displays a clean breakdown of costs using `iomanip`.
- **Persistent Loop:** Process multiple orders in one session until the user chooses to exit.

## ☕ Menu Prices


| Item | Price |
| :--- | :--- |
| Espresso | $2.50 |
| Latte | $3.75 |
| Cappuccino | $3.25 |
| Mocha | $4.00 |

## 🛠️ Technical Details

- **Language:** C++
- **Concepts Used:** 
  - Pass-by-reference functions for calculations.
  - Value-returning functions for input validation.
  - `do-while` loops and `switch` statements for program flow.
  - Fixed-point formatting for currency.

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com

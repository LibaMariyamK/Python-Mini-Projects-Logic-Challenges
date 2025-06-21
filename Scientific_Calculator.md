# 🧮 Python Scientific Calculator with History Tracking

A fully functional **Menu-Driven Scientific Calculator** written in Python that supports basic and scientific operations, input validation, session tracking, and file I/O features. Bonus functionalities include error logging, exporting history, and timestamped logs.

---

## 📌 Features

### ✅ Core Functionalities
- **Basic Operations**:
  - Addition, Subtraction, Multiplication, Division, Modulus, Power

- **Scientific Operations** (via `math` module):
  - Square Root, Cube Root
  - Factorial (non-negative integers only)
  - Trigonometric Functions: `sin`, `cos`, `tan` (input in degrees)
  - Logarithmic Functions: `math.log` (natural), `math.log10`
  - Exponential and Power: `math.exp`, `math.pow`

- **Menu-Driven Interface**:
  - Easy-to-navigate menu allowing repeated calculations
  - Option to exit gracefully

- **Error Handling**:
  - Handles invalid inputs (non-numeric, divide by zero, etc.)
  - Validates domain errors like log of negative numbers or factorial of negative/decimal numbers
  - Uses `try-except` for safe execution

- **Session History**:
  - Keeps a list of all calculations in the current session
  - Option to **view** or **clear** the session history

- **File Handling**:
  - Stores all calculations in `calculator_history.txt`
  - Displays the **last 5 calculations** from file at program start
  - Uses `with` statement for safe file I/O

---

## 🌟 Bonus Features

- ✅ **Timestamps**:
  - Appends date and time to each log entry using `datetime.now()`

- ✅ **Error Logging**:
  - Records all exceptions to `error_log.txt`

- ✅ **Export Session History**:
  - Exports current session history to a user-defined file (e.g., `my_calc_1.txt`)

- ✅ **Clear File History**:
  - Option to delete or clear all contents from `calculator_history.txt`

---

## 🧪 Sample Menu (Console UI)
```

\=== PYTHON SCIENTIFIC CALCULATOR ===

1. Addition              2. Subtraction
2. Multiplication        4. Division
3. Modulus               6. Power
4. Square Root           8. Cube Root
5. Factorial            10. Sin (°)
6. Cos (°)             12. Tan (°)
7. Natural Log         14. Log Base 10
8. Exponential         16. View Session History
9. Clear Session History
10. View Last 5 Calculations from File
11. Export Session History (Bonus)
12. Exit

```

---

## 📂 Example Log Entries

### In `calculator_history.txt`:
```

Addition: 15 + 25 = 40.0
Factorial: 5! = 120
Sin: sin(30°) = 0.50

```

### With Timestamp (Bonus):
```

2025-06-21 10:35:15 | sin(30°) = 0.50

````

---


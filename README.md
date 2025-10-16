# CalculatorApp (Java Swing)

A simple GUI-based calculator built using Java Swing.  
It performs basic arithmetic operations such as addition, subtraction, multiplication, and division.

---

## Features

- Basic arithmetic operations: +, -, *, /
- Handles both integer and decimal inputs
- Displays an error message for division by zero
- Simple, clean, and user-friendly interface
- Built completely with Java Swing (no external libraries)

---

## Interface Overview


---

## How It Works

1. Enter numbers using the digit buttons (0–9) or the decimal point.
2. Choose an operator (+, -, *, /).
3. Press `=` to perform the calculation.
4. If you divide by zero, the display shows "Error".

---

## Project Structure


**Main components:**
- `JFrame`: Main application window  
- `JTextField`: Display area for input and output  
- `JButton`: Calculator buttons for digits and operations  
- `JPanel` (GridLayout): Organizes buttons into a grid  
- `ActionListener`: Handles button click events

---

## How to Run

### Option 1: Using Command Line
```bash
javac CalculatorApp.java
java CalculatorApp

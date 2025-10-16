# Calculator
# 🧮 CalculatorApp (Java Swing)

A simple **GUI-based Calculator** built using **Java Swing** that performs basic arithmetic operations — addition, subtraction, multiplication, and division.

---

## 📋 Features

- ➕ Addition  
- ➖ Subtraction  
- ✖️ Multiplication  
- ➗ Division  
- 💬 Error handling for division by zero  
- 🔢 Works with integers and decimals  
- 🖱️ User-friendly GUI  
- 💡 Built entirely with **Swing** (no external libraries)

---

## 🖥️ Interface Preview


---

## ⚙️ How It Works

1. **Enter Numbers:** Click on number buttons (`0–9`) or `.` to type your input.  
2. **Select an Operator:** Choose one of the arithmetic operators (`+`, `-`, `*`, `/`).  
3. **Perform Calculation:** Press `=` to get the result.  
4. **Error Handling:** Dividing by zero displays `"Error"`.

---

## 🧱 Project Structure


### 🧩 Key Components

| Component | Description |
|------------|--------------|
| `JFrame` | Main application window |
| `JTextField` | Displays current input or result |
| `JButton` | Used for digits and operators |
| `JPanel (GridLayout)` | Holds calculator buttons |
| `ActionListener` | Handles button click events |

---

## 🚀 How to Run

### **Option 1: Using Command Line**

```bash
# Compile
javac CalculatorApp.java

# Run
java CalculatorApp

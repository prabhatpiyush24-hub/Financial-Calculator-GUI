# Financial-Calculator-GUI
A Python Tkinter based financial calculator for EMI, SIP, CAGR and XIRR
# 📊 Financial Calculator GUI (Python – Tkinter)

An interactive **Financial Calculator GUI application** built using **Python and Tkinter**.  
This project allows users to calculate commonly used financial metrics through a simple graphical interface without using the terminal.

The application is especially useful for students and beginners in **Finance, Investments, and Banking**.

---

## 🚀 Features

The calculator supports the following financial computations:

- **EMI Calculator**
  - Monthly EMI
  - Total payment
  - Total interest paid

- **Simple Return Calculator**
  - Absolute return
  - Return percentage

- **CAGR Calculator**
  - Compound Annual Growth Rate

- **SIP Future Value Calculator**
  - Total invested amount
  - Future value of SIP
  - Wealth gain through compounding

- **XIRR Calculator**
  - Handles **irregular cashflows**
  - Dynamic input of multiple cashflows with dates
  - Uses numerical methods to estimate accurate XIRR

---

## 🖥️ Technologies Used

- **Python 3**
- **Tkinter** – GUI framework
- **datetime module** – date handling
- **Mathematical finance formulas**
- **Bisection method** for XIRR calculation

---

## 📂 Project Structure

```text
Financial-Calculator-GUI/
│
├── financial_calculator_gui.ipynb   # Jupyter notebook (cell-by-cell execution)
├── financial_calculator_gui.py      # Optional standalone Python script
├── README.md                        # Project documentation
▶️ How to Run the Project
Option 1: Run using Jupyter Notebook (Recommended for learning)

Open Jupyter Notebook

Load financial_calculator_gui.ipynb

Run all cells sequentially

Execute the final cell to launch the GUI

Option 2: Run as a Python Script
python financial_calculator_gui.py


Make sure Python is installed and added to PATH.

📌 Input Notes

Interest rates should be entered in percentage (%)

Use negative values for investments and positive values for returns in XIRR

Date format for XIRR must be: YYYY-MM-DD

🎯 Learning Outcomes

Through this project, I learned:

Translating financial formulas into Python logic

Building interactive GUI applications using Tkinter

Implementing numerical methods for financial calculations

Structuring a real-world Python finance project

Handling user input validation and error management

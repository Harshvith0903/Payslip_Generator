# Payslip Generator

## Overview
This project is a **Payslip Generator** that automates the creation of employee payslips using Python. It reads employee data from an Excel file, processes salary details, and generates payslips.

---

## Features
- Reads employee data from an **Excel file**.
- Calculates salary breakdown including **basic pay, allowances, and deductions**.
- Generates **payslips** for multiple employees.
- Saves the output in a structured format.

---

## Installation
### **1. Clone the Repository**
```bash
git clone https://github.com/yourusername/Payslip_Generator.git
cd Payslip_Generator-main
```

### **2. Install Required Dependencies**
Ensure you have Python installed, then install the necessary libraries:
```bash
pip install pandas openpyxl
```

---

## Usage
### **1. Prepare Employee Data**
Update the `employee_data.xlsx` file with relevant salary details for employees.

### **2. Run the Payslip Generator**
```bash
python payslip.py
```

### **3. View the Generated Payslips**
Payslips will be generated and saved automatically in the output directory.

---

## Expected Output
After running the script, the generated payslips will contain:
```
Employee Name: John Doe
Basic Pay: $4000
Allowances: $500
Deductions: $200
Net Salary: $4300
```

---

## Contributing
If you'd like to contribute:
1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Commit your changes and push.
4. Open a Pull Request.

---

## License
This project is licensed under the MIT License. You are free to modify and use it for any purpose.

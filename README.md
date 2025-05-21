# Income Tax Calculator (FY 2024-25)

This is a console-based Python application that helps users compare income tax deductions under the **Old** and **New** tax regimes in India for the financial year 2024-25. It calculates tax based on user-provided CTC and Bonus, and suggests the better regime.

## 🔧 Features

- Calculates tax under:
  - Old Regime (with standard and 80C deductions)
  - New Regime (with flat slab rates, no deductions)
- Compares and suggests the more tax-saving regime
- Simple text-based user interface

## 🧮 Tax Calculation Logic

- **Old Regime**:
  - Standard Deduction: ₹50,000
  - 80C Deduction: ₹1,00,000
  - Slab rates applied post-deductions

- **New Regime (FY 2024-25)**:
  - ₹50,000 standard deduction
  - No additional deductions (like 80C)
  - Revised slab rates used

## ▶️ How to Run

1. Make sure Python is installed (Python 3.6 or above).
2. Clone or download this repository.
3. Open terminal/command prompt in the project directory.
4. Run the script:

```bash
python tax_calculator.py

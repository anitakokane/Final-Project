Expense Tracker – Python Project

This project is a Python-based Expense Tracker that helps users record, analyze, filter, and visualize their daily expenses. It uses OOP, NumPy, Pandas, Matplotlib, and Seaborn to provide a complete financial analysis tool.

📌 Features and Functionalities
1. Expense Input and Validation (Control Structures + Arrays)

Accepts user input: date, amount, category, description

Validates:

Amount must be positive

Category must be from a predefined list

Date format is checked

Stores expenses internally like an array (list of dictionaries)

2. ExpenseTracker Class (OOP Concepts)
✔ add_expense(date, amount, category, description)

Adds a new expense entry after validation.

✔ get_summary()

Returns:

Total expenses

Average expense

Total expenses per category

✔ filter_expenses(condition)

Filters expenses based on:

Category

Date range

Minimum or maximum amount

✔ generate_report()

Generates a complete summary:

Total spent

Highest & lowest spending categories

Monthly spending report

3. Expense Analysis (NumPy + Pandas)
Using NumPy

Total spending

Average spending

Numerical operations like max/min expenses

Using Pandas

Load and clean expense data

Remove duplicates

Handle missing values

Grouping:

By category

By month

Detect:

Most expensive month

Highest spending category

4. Data Visualization (Matplotlib + Seaborn)

Includes 5 major visualizations:

📊 1. Bar Chart – Total Expenses by Category

(Using Matplotlib)

📈 2. Line Graph – Spending Trend Over Time

(Using Matplotlib)

🥧 3. Pie Chart – Category-wise Expense Share

(Using Matplotlib)

📉 4. Histogram – Expense Amount Distribution

(Using Matplotlib)

🔵 5. Seaborn Plot – Category Spending Count (countplot)

(Using Seaborn)

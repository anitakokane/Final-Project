
# 💰 Expense Tracker – Python Project

A Python-based application for recording, analyzing, filtering, and visualizing **daily expenses**, built using **OOP**, **NumPy**, **Pandas**, **Matplotlib**, and **Seaborn**.

---

## 🚀 Objective

Develop an Expense Tracker system that enables users to:

* Add and validate expense entries
* Perform data cleaning and analysis
* Calculate financial summaries
* Filter expenses based on custom conditions
* Visualize financial insights using charts

---

## 🛠️ Features & Requirements

### 🔹 Class and Object Structure

* A class **`ExpenseTracker`** encapsulates all methods for managing and analyzing expenses.
* Uses OOP concepts like constructors, instance methods, and modular design.

---

### 🔹 Expense Input & Validation

* Accepts **date, amount, category, description**
* Validates:

  * Amount must be positive
  * Category must be valid
  * Date format verification
* Stores expenses internally using lists (array-like structure)

---

### 🔹 Expense Management

* **Add Expenses:** Insert new entries into the dataset
* **Clean Data:**

  * Handle missing values
  * Remove duplicate entries
* **Filter Expenses:**

  * By category
  * By date range
  * By amount (min/max)
  * Custom lambda-based conditions

---

### 🔹 Mathematical & Statistical Computations (NumPy)

* Total spending
* Average spending
* Min & Max expenses
* Category-wise calculations
* Uses NumPy arrays for fast numeric computation

---

### 🔹 Data Analysis (Pandas)

* Load and manage expense dataset
* Group data:

  * By category
  * By month
* Generate summary statistics
* Identify highest/lowest spending categories
* Monthly and category grouping

---

### 🔹 Data Visualization (Matplotlib & Seaborn)

Provides clear, meaningful financial insights through graphs:

* **Bar Chart:** Total expenses per category
* **Line Plot:** Expense trends over time
* **Pie Chart:** Category-wise spending share
* **Histogram:** Distribution of expense amounts
* **Seaborn Countplot:** Expense frequency per category

---

## 👨‍💻 Object-Oriented Approach

* **Constructor** initializes dataset
* **Instance methods** handle expense operations
* **Encapsulation** keeps data & logic structured
* Uses helper functions for repeated logic
* Follows clean and modular OOP architecture

---

## 🧑‍💻 User Interface

A **menu-driven console application** that allows users to:

* Add new expenses
* Filter by various conditions
* View summary reports
* Generate visual charts
* Exit anytime

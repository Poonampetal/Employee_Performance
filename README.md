# 📊 Employee Performance Analysis (SQL Project)

This project focuses on building and managing a structured **Employee Performance Database** using SQL. It covers key HR metrics such as employee records, performance reviews, training completion, and feedback—enabling comprehensive analysis of workforce performance.

## 🔧 Features

- **Database Creation**: Initializes a relational database named `Employee` with structured tables.
- **Data Validation**: Uses `SELECT` statements to inspect the contents of key tables.
- **Schema Management**:
  - Alters table structures to apply appropriate data types (e.g., converting text to `DATE` format).
  - Implements primary and foreign key constraints to ensure data integrity.
- **Relational Design**:
  - Establishes relationships between tables (e.g., linking `feedback_data` and `performance_metrics` to `employee_data`).

## 🗃️ Tables Involved

- `employee_data`: Core employee information.
- `feedback_data`: Employee feedback with timestamps.
- `performance_metrics`: Records of periodic performance evaluations.
- `training_data`: Information about employee training sessions.

## 🛠️ Technologies Used

- SQL (MySQL dialect preferred)
- Structured Query Language for schema definition and manipulation

## 📈 Use Case

Ideal for HR teams or data analysts seeking to:
- Monitor employee growth and productivity
- Identify training needs
- Gather insights from feedback loops

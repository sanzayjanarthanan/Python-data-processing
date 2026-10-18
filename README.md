# Python Data Processing

Process structured records and generate summary statistics using Python. Built as Task 9 of the AI & ML Internship at Veda Technology.

## Problem
Process a collection of structured records and generate a summary containing useful statistics.

## Objective
Combine Python concepts (lists, dictionaries, functions, loops) to perform basic data processing.

## Approach
1. Stored employee records as a list of dictionaries (name, dept, salary, age).
2. Created reusable functions:
   - `get_values()`: extract one field from all records
   - `summary()`: total, average, highest, lowest
   - `group_by()`: group records by a field
   - `process_record()`: add `level` and `annual_salary`
3. Calculated summary statistics for salary and age.
4. Calculated the department-wise average salary.
5. Processed all records using a list comprehension.

## Sample Output
```
Salary summary: {'total': 272000, 'average': 45333.33, 'highest': 60000, 'lowest': 36000}
Age summary   : {'total': 172, 'average': 28.67, 'highest': 35, 'lowest': 24}

Department-wise average salary:
  IT: 52333.33 (3 employees)
  HR: 37000.00 (2 employees)
  Finance: 41000.00 (1 employees)

Processed records (examples):
{'name': 'Arun', 'dept': 'IT', 'salary': 45000, 'age': 24, 'level': 'Junior', 'annual_salary': 540000}
```

## Files
- `Python_Data_Processing.ipynb`: notebook with the complete program
- `README.md`: project explanation

## How to Run
1. Open the notebook in Jupyter Notebook or Google Colab.
2. Run all cells from top to bottom.

## Tools Used
Python, Jupyter Notebook

## Key Learnings
- Functions avoid repeated code and make logic reusable
- Lists of dictionaries are a simple way to represent structured data
- Grouping and summarizing is the base of data analysis

## Author
J Sanjay
AI & Data Science student

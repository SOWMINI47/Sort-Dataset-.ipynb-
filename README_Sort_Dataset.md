# Sort Dataset Using Pandas

## Project Overview
This project demonstrates how to sort dataset records using Python and Pandas. It uses a sample employee dataset to show ascending sorting, descending sorting, categorical sorting, and sorting by multiple columns.

## Objective
Understand how sorting helps organize and analyze datasets.

## Technologies Used
- Python
- Pandas
- Google Colab / Jupyter Notebook

## Dataset
The sample employee dataset contains:
- Employee
- Department
- Age
- Salary

## Operations Performed
1. Sort salary in ascending order.
2. Sort salary in descending order.
3. Sort department names alphabetically.
4. Sort by Department and then Salary.
5. Sort by Age and then Department.

## Key Function
`DataFrame.sort_values()` sorts rows based on one or more columns.

- `ascending=True` sorts in ascending order.
- `ascending=False` sorts in descending order.
- `by=[...]` allows sorting by multiple columns.
- `ascending=[...]` sets the sort direction for each column.

## How to Run
1. Download `Sort_Dataset.ipynb`.
2. Open [Google Colab](https://colab.research.google.com/).
3. Select **File → Upload notebook** and upload the downloaded notebook.
4. Select **Runtime → Run all**.

## Learning Outcomes
- Understand ascending and descending sorting.
- Sort categorical values alphabetically.
- Sort a DataFrame using multiple columns.
- Use Pandas to organize records for analysis.

## Conclusion
This task demonstrates how Pandas `sort_values()` can organize dataset records and make data easier to inspect and analyze.

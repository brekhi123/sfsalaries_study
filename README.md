# San Francisco Employee Salary Analysis

This project performs a detailed case study on the **San Francisco City Employee Salary Dataset**, exploring compensation trends, job title distributions, and salary variations over time. The analysis was conducted using **pandas** and **NumPy** in Python.


## Objective

To investigate and extract insights from city employee compensation records between 2011–2014, including:

* Identifying high-paying job titles and individuals.
* Analyzing trends in base pay and total compensation.
* Examining job categories like “Fire Department” and “Captain.”
* Handling and interpreting missing data.


## Dataset Summary

* **Source**: [Kaggle – SF Salaries Dataset](https://www.kaggle.com/datasets/kaggle/sf-salaries)
* **Format**: CSV
* **Rows**: \~150,000
* **Columns**: 13 (including `EmployeeName`, `JobTitle`, `BasePay`, `OvertimePay`, `TotalPay`, `TotalPayBenefits`, and `Year`)


## Key Steps

1. **Data Loading & Cleaning**

   * Loaded the dataset and created a working copy.
   * Removed non-essential columns (`Id`, `Notes`, `Agency`, `Status`).
   * Converted `BasePay` to numeric, handling `'Not Provided'` as missing.
   * Checked for and analyzed rows with missing values.

2. **Exploratory Analysis**

   * Computed frequency counts of `EmployeeName` and `JobTitle`.
   * Counted unique job titles.
   * Filtered for jobs containing keywords like `"Captain"` or `"Fire Department"`.
   * Identified highest earners by `BasePay` and `TotalPayBenefits`.
   * Analyzed trends in mean base pay by year and job title.


## Selected Findings

* Most common job title: **Transit Operator**
* Unique job titles: **2,159**
* Employees with "Captain" in title: **112**
* Highest total compensation received by: **Albert Pardini**
* Average base pay for **Accountants**: \~\$71,621


## Requirements

* Python 3.x
* pandas
* numpy


## How to Run

1. Download the `Salaries.csv` file and place it in a `./data/` directory.
2. Run the script in a Jupyter notebook or any Python environment.


## License

This project is for educational purposes using publicly available data.
# Banking Risk Analytics Dashboard

## Overview

This project focuses on analyzing banking customer data to support lending risk assessment and financial decision-making. The solution combines Python, MySQL, and Power BI to perform data extraction, data analysis, and dashboard reporting on customer, loan, and deposit information.

## Problem Statement

Banks and financial institutions need to evaluate customer profiles before approving loans. This project analyzes customer demographics, banking relationships, deposits, and loan information to identify patterns that can assist in understanding customer financial behavior.

## Dataset

The dataset contains approximately 3,000 customer records with information such as:

* Customer demographics
* Occupation details
* Estimated income
* Banking relationship type
* Account balances
* Loan information
* Credit card balances
* Deposit information
* Customer joining dates

## Technologies Used

* **Python**

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn

* **Database**

  * MySQL

* **Business Intelligence**

  * Power BI
  * DAX

## Project Workflow

### 1. Data Storage

* Converted raw data into CSV format.
* Imported data into MySQL database.
* Connected MySQL with Python using `mysql-connector-python`.

### 2. Data Analysis

* Performed data cleaning and preprocessing.
* Checked missing values and data types.
* Conducted exploratory data analysis (EDA).
* Analyzed customer demographics, income bands, deposits, loans, and credit card information.
* Generated correlation analysis and distribution visualizations.

### 3. Feature Engineering

Created business-related metrics including:

* Engagement Days
* Engagement Timeframe
* Income Band
* Processing Fees
* Total Loan
* Total Deposit

### 4. Dashboard Development

Built interactive Power BI dashboards for:

* Loan Analysis
* Deposit Analysis
* Customer Analysis
* Banking Summary

## Key Performance Indicators (KPIs)

* Total Clients
* Total Loan
* Total Deposit
* Bank Loan
* Business Lending
* Credit Card Balance
* Total Fees
* Savings Account Balance
* Checking Account Balance
* Foreign Currency Account Balance

## Dashboard Features

* Interactive filters and slicers
* Customer segmentation
* Loan and deposit analysis
* Income band comparison
* Nationality-based analysis
* Banking relationship analysis
* Financial KPI monitoring

## Key Insights

* Loan amounts vary across customer income groups.
* Deposit balances show strong relationships with savings and checking accounts.
* Customer demographics influence banking product usage.
* Financial metrics help understand customer banking behavior and lending exposure.

## Project Structure

```text
├── Banking.csv
├── clients.csv
├── Banking.xlsx
├── BankEDA.ipynb
├── Banking Dashboard.pbix
├── Banking Dashboard (2025).pbix
├── Banking Report.docx
├── Banking.pptx
└── README.md
```

## How to Run

1. Import the dataset into MySQL.
2. Update database credentials in the Jupyter Notebook.
3. Run the EDA notebook to perform analysis.
4. Open the Power BI (.pbix) file.
5. Refresh data connections if required.
6. Explore dashboard pages and visualizations.

## Skills Demonstrated

* SQL Querying
* Database Management
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Power BI Dashboard Development
* DAX Calculations
* Banking Data Analysis

## Author

Riya Bisht

## License

This project is intended for educational and portfolio purposes.

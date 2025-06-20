# Loan Risk Assessment Dashboard

## Project Overview

This project presents a comprehensive **Loan Risk Assessment Dashboard** developed using **Power BI**, aimed at analyzing and visualizing key metrics related to loan disbursement, deposit trends, client demographics, and banking relationships. The goal is to support strategic decision-making in financial institutions by identifying risk patterns, client behavior, and business performance across multiple dimensions.



## Dashboard Features

The dashboard includes three main analysis modules:

### 1. **Loan Analysis**
- Total loan value and breakdown
- Bank loan distribution by:
  - Banking Relationship (BR)
  - Occupation
  - Nationality
- Business lending value
- Credit card (CC) balance analysis

### 2. **Deposit Analysis**
- Total deposits and component breakdown:
  - Checking accounts
  - Savings accounts
  - Bank deposits
- Deposit distributions by:
  - Banking Relationship
  - Occupation
  - Nationality

### 3. **Summary and Filters**
- Key client and financial statistics:
  - Total Clients
  - Total Loans and Deposits
- Slicers for dynamic filtering:
  - Joining Year
  - Gender
  - Banking Relationship
  - Institution Advisor



## Insights Uncovered

- Loans exceed total deposits, indicating credit-deposit imbalance.
- Private bank clients dominate both lending and deposit segments.
- European and Asian clients form the bulk of both loans and deposits.
- Occupation-wise, loan and deposit portfolios are well diversified.
- Business lending forms a large part of the credit portfolio, suggesting commercial lending focus.



## Python-Based Analysis

In addition to Power BI visualization, various **data preprocessing and exploratory analyses** were conducted using **Python** to enrich the dashboard’s insights. Tasks performed include:

- Data Cleaning (missing value handling, type conversion)
- Feature Engineering for categorical segmentation
- Statistical Analysis on credit and deposit ratios
- Group-wise aggregations using `pandas`
- Visualization previews using `matplotlib` and `seaborn`
- Exporting transformed datasets to CSV for Power BI integration


## Tools & Technologies

- **Power BI**: Data modeling, dashboard design, DAX calculations
- **Python (pandas, numpy, seaborn, matplotlib)**: Data analysis and preprocessing
- **Excel / CSV**: Initial data source formatting and imports




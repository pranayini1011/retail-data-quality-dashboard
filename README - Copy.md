Retail Transaction Data Quality and Validation Dashboard

## 1. Project Overview

The Retail Transaction Data Quality and Validation Dashboard is an Excel-based project designed to identify errors and inconsistencies in retail transaction records.

The project uses Microsoft Excel formulas and data validation techniques to identify missing values, duplicate transaction IDs, invalid dates, incorrect quantities, invalid prices and unexpected categories or payment methods.

A dashboard presents the validation results through key performance indicators and charts.

## 2. Project Objective

The main objectives of this project are:

- Identify missing and duplicate transaction records.
- Validate transaction dates, quantities and prices.
- Identify incorrect product categories and payment methods.
- Classify records as PASS or FAIL based on validation rules.
- Monitor data quality through an interactive Excel dashboard.
- Present validation results using charts and summary reports.

## 3. Tools and Technologies Used

- Microsoft Excel
- Excel Formulas
- Conditional Formatting
- Excel Tables
- Pivot Tables (if implemented)
- Excel Charts
- Data Validation

## 4. Dataset Description

The project uses a synthetic retail transaction dataset containing 100 sample records.

The dataset includes:

- Transaction ID
- Transaction Date
- Store ID
- Product ID
- Product Category
- Quantity
- Unit Price
- Payment Method

The dataset contains deliberately introduced errors for testing data validation techniques.

## 5. Methodology

The project was completed through the following stages:

### Stage 1: Data Preparation
- Imported the retail transaction dataset.
- Structured the dataset using Excel Tables.
- Preserved the original raw data.

### Stage 2: Missing Value Detection
- Identified missing store IDs, product IDs, product categories and payment methods.
- Used COUNTBLANK and IF functions to identify incomplete records.

### Stage 3: Duplicate Detection
- Used COUNTIF to identify repeated transaction IDs.
- Classified records as Duplicate or Unique.

### Stage 4: Data Validation
- Validated transaction dates using ISNUMBER.
- Checked quantities using ISNUMBER, AND and MOD.
- Identified zero and negative prices.
- Checked permitted product categories and payment methods.

### Stage 5: Overall Status Calculation
- Combined all validation results using IF and AND.
- Classified transactions as PASS or FAIL.

### Stage 6: Dashboard Development
- Created KPI cards.
- Calculated total, valid and invalid transactions.
- Calculated data quality percentage.
- Created an error summary table.
- Developed PASS vs FAIL and error distribution charts.

## 6. Data Validation Rules

| Validation | Rule |
|---|---|
| Missing Values | Mandatory fields must not be blank |
| Duplicate IDs | Transaction IDs must be unique |
| Date Validation | Transaction dates must be valid Excel dates |
| Quantity Validation | Quantity must be a positive whole number |
| Price Validation | Unit price must be greater than zero |
| Category Validation | Category must belong to the permitted list |
| Payment Validation | Payment method must belong to the permitted list |

## 7. Dashboard Metrics and Results

The dashboard provides the following results:

| Metric | Result |
|---|---:|
| Total Transactions | 100 |
| Valid Transactions | 88 |
| Invalid Transactions | 12 |
| Data Quality Percentage | 88% |

### Error Summary

| Error Type | Error Occurrences |
|---|---:|
| Missing Data | 3 |
| Duplicate IDs | 4 |
| Invalid Dates | 1 |
| Invalid Quantities | 2 |
| Invalid Prices | 2 |
| Invalid Categories | 1 |
| Invalid Payments | 1 |

*Error occurrences may overlap when a transaction contains multiple errors.*

## 8. Key Learnings

Through this project, I gained practical experience in:

- Data validation and quality checking.
- Identifying missing and duplicate records.
- Using Excel formulas for automated error detection.
- Organising and analysing structured datasets.
- Creating KPI dashboards and visual reports.
- Interpreting data quality metrics.
- Improving accuracy through systematic validation rules.

## 9. Conclusion

This project demonstrates how Microsoft Excel can be used to validate retail transaction data, identify inconsistencies and monitor data quality through a dashboard.

It helped me develop practical skills in data handling, validation, analytical thinking and reporting.

## 10. Project Files

- Retail_Data_Quality_Project.xlsx – Main Excel workbook containing raw data, validation results and dashboard.
- README.md – Project documentation.
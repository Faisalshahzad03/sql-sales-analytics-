# SQL Sales Analytics Portfolio – Business Reporting & Fiscal Year Analysis

## Author
**Faisal Shahzad**  
Email: faisal843210@gmail.com  
LinkedIn: https://www.linkedin.com/in/faisal-analyst/

---

## Overview

This repository contains a collection of SQL-based sales analytics and business reporting projects built using MySQL.

The projects focus on real-world business reporting requirements, including fiscal year handling, product-wise sales analysis, pricing alignment, and revenue calculations.  
All reports are designed to be analysis-ready and exported to Excel for business consumption.

---

## Tools & Technologies

- MySQL  
- SQL (Joins, Functions, Aggregations)  
- Fiscal Year & Time-Based Analysis  
- Sales & Revenue Reporting  
- Excel (Final Output & Analysis)

---

## Projects Included

---

## 1. Product-Wise Sales Report (Fiscal Year 2021)

**Domain:** Sales Analytics & Revenue Reporting  

### Objective
To build a product-level sales report for a given fiscal year that accurately aligns sales data with pricing data, ensuring correct revenue calculations.

A key challenge in this task was handling fiscal year logic (Apr–Mar) instead of calendar years.

### Key Features
- Custom fiscal year function for accurate date-to-FY mapping  
- Product-wise and variant-wise sales analysis  
- Sold quantity and gross price per unit  
- Total gross revenue calculation  
- Correct pricing alignment using fiscal year logic  
- Clean, reusable, and scalable SQL design  

### SQL Concepts Used
- User-defined SQL functions  
- Inner joins across fact and dimension tables  
- Fiscal year–based filtering and joins  
- Calculated columns for revenue  
- Sorting and reporting logic  

### Project Files
- Excel Report  
  https://github.com/Faisalshahzad03/sql-sales-analytics-/blob/main/Product_Wise_Sales_Report_FY2021.xlsx

- SQL Case Study PDF  
  https://github.com/Faisalshahzad03/sql-sales-analytics-/blob/main/Product_Wise_Sales_Report_FY2021_SQL_Case_Study.pdf

---

## 2. Gross Monthly Sales Report Using SQL

**Domain:** Revenue & Monthly Sales Analytics  

### Objective
To calculate total gross sales per date by accurately aligning sales data with fiscal year-based pricing.

This project reuses the custom `get_fiscal_year()` function built in Project 1 to ensure correct pricing alignment.

### Key Features
- Revenue calculation using quantity × price  
- Fiscal year-aligned price mapping  
- Aggregated gross sales at date level  
- Reusable SQL logic across reports  
- Excel-ready output for business analysis  

### SQL Concepts Used
- Aggregation using SUM()  
- GROUP BY for monthly/date-level reporting  
- Reuse of user-defined function  
- Revenue calculation with rounding  

### Project Files
- Excel Report  
  https://github.com/Faisalshahzad03/sql-sales-analytics-/blob/main/monthly_gross_sales_report_FY2021.csv

- SQL Case Study PDF  
https://github.com/Faisalshahzad03/sql-sales-analytics-/blob/main/monthly_gross_sales_report_SQL_explanation.pdf
---

## Key Takeaways

- Demonstrates real-world SQL reporting skills  
- Highlights importance of fiscal year alignment in analytics  
- Shows clean and reusable SQL design practices  
- Bridges SQL outputs with Excel-based business analysis  
- Built with scalability in mind for future reports  

---
## 3. Yearly Sales Report Using SQL

**Domain:** Sales Performance & Yearly Revenue Analysis  

### Objective
To generate a yearly sales report that summarizes total sales performance over time, supporting high-level business and management analysis.

This report focuses on aggregating sales data at a yearly level to identify overall trends and performance.

### Key Features
- Yearly sales aggregation  
- Total revenue calculation  
- Clean and simple reporting structure  
- Business-ready output for summary analysis  
- Exported to CSV for further use  

### SQL Concepts Used
- Aggregation using SUM()  
- GROUP BY for yearly reporting  
- Revenue calculation logic  
- Ordering and result formatting  

### Project Files
- CSV Report  
  https://github.com/Faisalshahzad03/sql-sales-analytics-/blob/main/monthly_gross_sales_report_SQL_explanation.pdf

- SQL Case Study PDF  
 https://github.com/Faisalshahzad03/sql-sales-analytics-/blob/main/yearly_sales_SQL_case_study.pdf

---
## Future Enhancements

Planned additions to this repository:
- Monthly aggregated sales trends  
- Customer performance analysis  
- Market-wise and region-wise reports  
- Advanced revenue and pricing analytics  

---

## Contact

For collaboration, feedback, or analytics opportunities:

Email: faisal843210@gmail.com  
LinkedIn: https://www.linkedin.com/in/faisal-analyst/

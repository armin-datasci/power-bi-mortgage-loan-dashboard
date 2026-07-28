# power-bi-mortgage-loan-dashboard
End-to-end Power BI project for mortgage loan applications, credit risk, approval performance, and underwriter analysis.
# Mortgage Loan Analytics Dashboard

## Project Overview

This project presents an end-to-end Power BI solution for analyzing mortgage loan applications.

The dashboard was designed to help management evaluate application volume, approval and rejection rates, applicant credit risk, loan products, property characteristics, and underwriter performance.

## Business Objectives

- Monitor mortgage loan application trends
- Analyze approval, rejection, and pending rates
- Identify high-risk loan applications
- Evaluate applicants based on credit score and payment history
- Analyze Loan-to-Value (LTV) ratios
- Compare loan product performance
- Evaluate underwriter workload and approval performance
- Identify data quality issues

## Data Sources

The project uses multiple related datasets containing:

- Loan applications
- Applicant information
- Credit history
- Loan products
- Property information
- Underwriter information

## Tools and Technologies

- Power BI
- Power Query
- DAX
- Data Modeling
- Star Schema
- Data Cleaning
- Data Visualization
- Business Intelligence

## Data Preparation

The data preparation process included:

- Importing and combining multiple source files
- Correcting data types
- Cleaning text fields
- Handling duplicate and missing values
- Merging applicant and credit history data
- Validating primary and foreign keys
- Creating a dedicated date table

## Data Model

A star schema was designed with the loan applications table as the central fact table.

![Data Model](model/star-schema.png)

## Key Metrics

- Total Applications
- Unique Applicants
- Total Requested Amount
- Average Loan Amount
- Approval Rate
- Rejection Rate
- Pending Rate
- Average LTV
- High-Risk Application Rate
- Average Credit Score
- Applications per Applicant

## Dashboard Pages

### Executive Overview

![Executive Overview](dashboard/executive-overview.png)

### Risk Analysis

![Risk Analysis](dashboard/risk-analysis.png)

### Applicant Analysis

![Applicant Analysis](dashboard/applicant-analysis.png)

### Underwriter Performance

![Underwriter Performance](dashboard/underwriter-performance.png)

### Data Quality

![Data Quality](dashboard/data-quality.png)

## Dashboard Features

- Interactive slicers and filters
- Drillthrough analysis
- Custom tooltips
- Page navigation
- Dynamic KPI cards
- Risk-level segmentation
- Credit score segmentation
- Loan-to-Value analysis
- Underwriter performance comparison

## Analytical Questions

The dashboard investigates questions such as:

- Which loan products have the highest approval rates?
- What percentage of applications have an LTV above 100%?
- How does credit score relate to approval rate?
- Which underwriters process the highest number of applications?
- Which applicant segments represent the highest credit risk?
- Are high-risk applications associated with lower approval rates?

## Repository Structure

- `dashboard/`: Dashboard screenshots
- `model/`: Power BI data model
- `powerbi/`: PBIX project file
- `report/`: Analytical report
- `documentation/`: DAX measures and data documentation

## Author

**Armin Khosravi Karchi**

- GitHub: [armin-datasci](https://github.com/armin-datasci)
- Email: thisisarminks@gmail.com

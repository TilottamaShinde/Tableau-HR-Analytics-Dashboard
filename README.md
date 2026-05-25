# HR Analytics Dashboard (Tableau)


## Overview

The HR Analytics Dashboard is an interactive Tableau project built using the IBM HR dataset.
It helps visualize key workforce metrics such as employee attrition, demographics, income distribution, and job satisfaction.

This project demonstrates how raw HR data can be transformed into business-ready insights for decision-making.

## Objective
Analyze employee attrition patterns
Identify key factors affecting retention
Build interactive KPI dashboards in Tableau
Provide actionable HR insights for management

## Dataset Information
### Source: IBM HR Analytics Employee Attrition Dataset
Structure: Single-table dataset
Records: Employees with HR attributes
Key Columns:
Employee Number
Age
Gender
Department
Job Role
Attrition
Monthly Income
Education Field
Job Satisfaction

## Dashboard Features
Total Employees KPI
Attrition Count KPI
Attrition Rate
Age Distribution Analysis
Income Distribution Insights
Department-wise Attrition
Gender-based Attrition Analysis

## Tools & Technologies
Tableau Desktop
Microsoft Excel / CSV
IBM HR Dataset

### Key Calculations (Tableau)
Total Employees

COUNT(Employee Number)

### Attrition Count

SUM(IF Attrition = 'Yes' THEN 1 ELSE 0 END)

### Attrition Rate

SUM(IF Attrition = 'Yes' THEN 1 ELSE 0 END)
/ COUNT(Employee Number)


## Author

### Tilottama Shinde
Aspiring Data Analyst | Tableau | SQL | Python

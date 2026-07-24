# HR Employee Attrition Analysis — Excel Dashboard

## Project Overview

This project explores employee attrition using Microsoft Excel to identify the workforce characteristics associated with higher turnover. Using PivotTables, PivotCharts, and interactive slicers, the analysis examines how attrition varies across departments, salary bands, tenure groups, performance ratings, and demographic factors.

The objective was to transform raw HR data into an interactive dashboard that enables HR teams to quickly identify attrition trends and make more informed retention decisions.

**Author:** Patricia Fagbola | Data Analyst | 2026

**Tools:** Microsoft Excel (PivotTables, PivotCharts, Slicers)

---

## Dashboard Preview

![Dashboard Preview](images/dashboard_preview.png)

---

# Dataset

The dataset contains HR information for **1,470 employees** with **35 attributes** describing employee demographics, job characteristics, compensation, performance, and employment history.

Key fields include:

- Department
- Job Role
- Monthly Income
- Performance Rating
- Job Satisfaction
- Marital Status
- Years at Company
- Attrition (Yes/No)

The target variable analysed throughout the project is **Employee Attrition**.

---

# Business Problem

Employee turnover creates recruitment costs, reduces productivity, and affects organisational performance. However, attrition rarely occurs evenly across an organisation.

This project investigates which employee groups experience higher attrition and identifies patterns that can help HR teams prioritise retention efforts instead of applying broad organisation-wide interventions.

---

# Analysis Process

The analysis was completed entirely in Microsoft Excel.

The workflow included:

- Reviewing the dataset for consistency before analysis.
- Building PivotTables to summarise employee metrics across multiple dimensions.
- Creating tenure groups (New, Mid, Experienced) for comparison.
- Designing PivotCharts to communicate trends visually.
- Combining charts with slicers into an interactive dashboard.
- Documenting business insights and recommendations based on the analysis.

---

# Key Metrics

- **1,470** employees analysed
- **237** employees left the company
- Overall attrition rate: **16.1%**
- Sales recorded the highest employee attrition
- Research & Development demonstrated the strongest employee retention

---

# Key Insights

## 1. Sales experiences the highest employee attrition

Sales consistently records the largest proportion of employee departures, suggesting department-specific challenges affecting retention.

## 2. Lower salary bands experience higher turnover

Employees within lower salary bands are more likely to leave the organisation, indicating compensation may contribute to attrition.

## 3. Higher pay alone does not guarantee retention

Although Sales records the highest average monthly income, it also has the highest attrition, suggesting additional factors beyond salary may influence employee decisions.

## 4. Tenure influences both income and attrition

Employees with longer tenure generally earn higher salaries, while newer employees appear more vulnerable to leaving the organisation.

## 5. Marital status shows little relationship with performance

Performance ratings remain relatively consistent across marital status categories, indicating this variable contributes little to explaining performance differences.

---

# Recommendations

Based on these findings, the following actions could improve employee retention:

1. Investigate department-specific causes of attrition within Sales, including workload, management practices, and career progression.
2. Review compensation strategies for lower salary bands.
3. Study retention practices within Research & Development and evaluate whether they can be adapted by other departments.
4. Strengthen onboarding and engagement programmes for newer employees.
5. Consider reviewing compensation policies to ensure salary progression reflects both tenure and performance.

---

# Skills Demonstrated

- Microsoft Excel
- PivotTables
- PivotCharts
- Interactive Dashboards
- Slicers
- HR Analytics
- Exploratory Data Analysis (EDA)
- Business Insight Generation
- Data Storytelling

---

# Repository Structure

```text
HR-Attrition-Analysis/
├── README.md
├── images/
│   └── dashboard_preview.png
└── data/
    └── HR-Employee-Attrition.xlsx
```

---

# How to Use

Open `HR-Employee-Attrition.xlsx` in Microsoft Excel.

The workbook contains:

- **HR-Employee-Attrition** – Raw employee dataset
- **Pivot Analysis** – Supporting PivotTables
- **Dashboard** – Interactive dashboard with slicers
- **Insights** – Summary of key findings
- **Working Sheet** – Supporting calculations

---

# Business Value

This analysis demonstrates how Excel can be used to transform HR data into actionable insights. By identifying high-risk employee groups and the factors associated with attrition, the dashboard can help HR teams prioritise retention initiatives, monitor workforce trends, and support evidence-based decision-making.


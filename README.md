# HR Employee Attrition Analysis — Excel Dashboard

An Excel-based analysis of employee attrition drivers department, salary band, performance, and tenure — built with PivotTables, slicers, and a dashboard.

**Author:** Patricia Fagbola | Data Analyst | 2026
**Tools:** Microsoft Excel (PivotTables, PivotCharts, Slicers)

---

![Dashboard preview](images/dashboard_preview.png)

## Dataset

- **1,470** employees
- **35** attributes per employee, including Department, Job Role, Monthly Income, Performance Rating, Job Satisfaction, Marital Status, and Tenure fields
- Target variable: **Attrition** (Yes/No)

## Business Problem

Employee turnover is costly, but not evenly distributed across the business. This analysis breaks down attrition by department, compensation band, and performance to identify where the business is losing people and why — so retention efforts can be targeted rather than blanket.

## Headline Numbers

- **1,470** total employees
- **237** left the company — a **16.1%** attrition rate
- **Sales** — highest attrition among departments
- **Research & Development** — lowest attrition, strongest retention

## Key Insights

- **Sales has the highest attrition rate**, while Research & Development shows the lowest — indicating notably stronger employee retention within R&D
- **Lower salary band employees churn more** — attrition is consistently higher in the lower compensation band, suggesting pay is a meaningful driver of turnover
- **Sales also pays the most on average** — despite the highest attrition, Sales has the highest average monthly income of any department, pointing to attrition drivers beyond pay alone (e.g. role pressure, targets, work-life balance)
- **Lower performers earn more than expected** — employees with lower performance ratings have slightly higher average income than average/high performers; this is largely explained by tenure, since longer-serving employees earn more regardless of current performance
- **Marital status doesn't move performance** — performance ratings are consistent across Married, Single, and Divorced employees, ruling it out as a meaningful factor
- **Tenure band affects both pay and attrition risk** — "New" employees earn the least and pivot data shows meaningfully different attrition distribution across New/Mid/Experienced tenure groups

## Recommendations

1. **Investigate Sales attrition specifically** — since pay isn't the gap, look at workload, quota pressure, management, or role fit within Sales
2. **Review compensation at the lower salary band** — the clearest quantifiable link to attrition in the data; targeted raises or better lower-band benefits could reduce churn
3. **Protect R&D's retention practices** — understand what R&D does well (culture, stability, career paths) and see if it transfers to Sales and HR
4. **Build a tenure-based retention plan** — new employees appear to be the most flight-risk group; a stronger onboarding and early-tenure engagement plan could help
5. **Don't rely on performance ratings alone for pay equity reviews** — since income is more tied to tenure than current performance, a compensation audit may be worthwhile

## Methodology

- **PivotTables** across department, salary band, performance rating, gender, marital status, and tenure grouping (New / Mid / Experienced)
- **PivotCharts** — Salary by Department, Performance vs. Salary, Attrition by Salary Band, Employee Count by Attrition
- **Slicers** for interactive filtering across the dashboard
- **Dashboard sheet** consolidating the four core charts into a single view
- **Insights sheet** documenting the five headline findings directly on the workbook

## Repo Contents

```
HR-Attrition-Analysis/
├── README.md
├── images/
│   └── dashboard_preview.png        # Static preview of the dashboard charts
└── data/
    └── HR-Employee-Attrition.xlsx   # Raw data + PivotTables + Dashboard + Insights
```

## How to View

Open `data/HR-Employee-Attrition.xlsx` in Excel. The workbook has five sheets:
- **HR-Employee-Attriti** — raw employee-level data
- **Pivot Analysis** — underlying PivotTables
- **Dashboard** — interactive charts with slicers
- **Insights** — headline findings
- **working sheet** — supporting calculations

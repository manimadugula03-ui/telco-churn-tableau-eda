# Telco Customer Churn: Exploratory Data Analysis in Tableau

Exploratory data analysis (EDA) of the Telco Customer Churn dataset using Tableau, done as Week 1 of the Virtual Tableau Visualization Internship (Yuva Intern).

## Objective
Find out which customers are leaving the company and what they have in common.

## Dataset
- Source: Kaggle, "Telco Customer Churn" (IBM sample data, by BlastChar)
- 7,043 customers, 21 fields
- Target variable: Churn (Yes / No)

## Dashboard
![Churn Analysis Dashboard](dashboard.png)

## Key Insights
| Finding | Result |
|---|---|
| Overall churn rate | 26.5% (1,869 of 7,043 customers) |
| Month-to-month contract churn | 42.7% (vs 11.3% one-year, 2.8% two-year) |
| Average tenure | 17.98 months (churned) vs 37.57 months (retained) |
| Average monthly charges | 74.44 (churned) vs 61.27 (retained) |
| Fiber optic churn | 41.9% (vs 19.0% DSL, 7.4% no internet) |

## Charts built in Tableau
1. Churn Count
2. Contract vs Churn
3. Tenure vs Churn
4. Monthly Charges vs Churn
5. Internet Service vs Churn

## Files in this repository
- `Telco-Churn-EDA.twb`: Tableau workbook (keep it in the same folder as the CSV to open it)
- `WA_Fn-UseC_-Telco-Customer-Churn.csv`: dataset
- `Telco-Churn-EDA-Report.docx`: full analysis report
- `dashboard.png`: dashboard screenshot

## Tools
Tableau Public Desktop

## Author
Madugula Manikumar# telco-churn-tableau-eda

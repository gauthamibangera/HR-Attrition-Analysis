# HR Attrition Analysis

## Project Overview

An exploratory analysis of an HR employee dataset to identify the factors most strongly linked to attrition — overtime, job satisfaction, work-life balance, promotion history, and income — so retention efforts can be targeted rather than applied company-wide.

## Dataset

`hr_attrition_light_clean.csv` — 1,212 employee records, 23 columns. Raw data required cleaning: duplicate IDs, inconsistent category formatting, and missing values.

- Demographics: Age, Gender, Department, JobRole, EducationField, MaritalStatus
- Compensation: MonthlyIncome, PercentSalaryHike
- Tenure & growth: YearsAtCompany, YearsSinceLastPromotion, TotalWorkingYears, NumCompaniesWorked
- Satisfaction: JobSatisfaction, EnvironmentSatisfaction, WorkLifeBalance, JobInvolvement
- Target: Attrition

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook
  
## Key Insights

Attrition sits at 17% overall, and a few factors stand out as most strongly linked to it:

- **Overtime** — the biggest driver. Employees who work overtime leave almost 5x more often (37.7% vs 7.9%).
- **Job satisfaction & work-life balance** — both show a clear pattern: lower scores mean higher attrition.
- **Promotion history** — employees who left went longer without a promotion (9 years vs 6 years, median).
- **Income** — a smaller factor. Leavers earned somewhat less, but the two groups overlap too much for pay alone to explain attrition.
  
# Conclusion
Workload management (reducing overtime) is the single most actionable lever for retention, followed by improvements to satisfaction and work-life balance. Promotion timelines and pay play a secondary role.

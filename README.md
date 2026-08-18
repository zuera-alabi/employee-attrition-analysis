# Employee Attrition Analysis
## HR Executive Dashboard — Workforce Attrition and Retention Intelligence
![Dashboard Overview](images/01_hr_dashboard_overview.png)
## Project Overview
This project analyses a Human Resources dataset containing 
311 employee records across multiple departments and states 
spanning from 2006 to 2018. Using MySQL for data cleaning 
and analysis and Power BI for visualisation, the goal is 
to uncover meaningful insights about employee attrition, 
performance and satisfaction that support data-driven 
HR decision making.

## Business Problem
The organisation is experiencing a 33.44% employee attrition 
rate — more than double the industry standard of 10-15%. 
HR teams lack visibility into the key drivers behind this 
turnover making it difficult to implement effective 
retention strategies.

The analysis focused on answering the following questions:
- What is the overall employee attrition and retention rate?
- Which department has the highest attrition rate?
- Does salary affect attrition?
- Which recruitment source produces the best performing employees?
- How do performance scores relate to termination?
- Which gender has the higher attrition rate?
- Does employee satisfaction affect attrition?

## Dataset
The dataset contains 311 employee records spanning from 
2006 to 2018 across multiple departments and states.

| Column | Description |
|--------|-------------|
| Employee ID | Unique employee identifier |
| Name | Employee full name |
| Gender | Employee gender |
| Marital Status | Employee marital status |
| Date of Birth | Employee date of birth |
| Position | Job title and role |
| Department | Department employee belongs to |
| Salary | Employee annual salary |
| Hire Date | Date employee joined |
| Termination Date | Date employee left |
| Employment Status | Active or terminated |
| Performance Score | Employee performance rating |
| Engagement Survey | Employee engagement score |
| Employee Satisfaction | Satisfaction rating |
| Recruitment Source | How employee was recruited |
| State | Employee location |

## Tools & Technologies
|Tool | Purpose |
|------|---------|
| MySQL | Data cleaning and exploratory analysis |
| Power BI | Interactive dashboard development |
| DAX | Calculated measures and KPIs |
| GitHub | Version control and documentation |


##  Project Structure
```
employee-attrition-analysis/
│
├── data/
│   ├── raw/          → Original HR dataset
│   └── cleaned/      → Cleaned and processed dataset
│
├── sql/              → SQL analysis queries
├── dashboard/        → Power BI .pbix file
├── images/           → Dashboard screenshots
└── README.md
```
### Overview — Full Workforce View
![Dashboard Overview](images/01_hr_dashboard_overview.png)
At first glance the numbers tell a concerning story — 33.44% 
of employees have left the organisation, more than double 
the industry standard. With an average salary of £69,463 
and a retention rate of just 66.56%, the dashboard immediately 
signals that this is not a minor HR challenge but a serious 
organisational risk requiring urgent strategic intervention.

### Production Department Filter
![Production Department](images/02_hr_dashboard_production.png)
Filtering by Production transforms the picture dramatically — 
this single department accounts for 79.8% of all company 
attritions. With the lowest average salary across all 
departments and the highest voluntary exit rate, Production 
emerges as the organisation's most critical retention 
crisis and the starting point for any meaningful intervention.


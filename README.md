# HR Analytics Dashboard – Power BI

## Project Overview

This project is an **HR Analytics Dashboard built in Microsoft Power BI** to analyze employee workforce data and identify patterns related to employee activity and attrition.

The dashboard provides an interactive view of employee count, active employees, attrition, attrition rate, average employee age, department-wise workforce, education, job roles, gender, age groups, and income.

## Dashboard Preview

![HR Analytics Dashboard](images/HR_Analytics_Dashboard.png)

## Key KPIs

- **Employee Count:** 1,470
- **Active Employees:** 1,233
- **Attrition Count:** 237
- **Attrition Rate:** 16.12%
- **Average Employee Age:** 36.92 years

## Dashboard Analysis

The dashboard includes:

- Employee and attrition analysis by **Department**
- Active employees by **Education**
- Monthly income analysis by **Job Role**
- Performance rating by department
- Active employees and attrition by **Gender**
- Active employees and attrition by **Age Band**
- Job role-wise employee analysis
- Interactive slicers for:
  - Department
  - Job Role
  - Education

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Data Cleaning & Transformation
- Interactive Data Visualization

## Dataset

The project uses an HR employee dataset containing **1,470 employee records and 35 attributes**, including:

- Age
- Attrition
- Department
- Job Role
- Education
- Gender
- Monthly Income
- Job Satisfaction
- Performance Rating
- OverTime
- Total Working Years
- Years at Company
- Years in Current Role
- Years Since Last Promotion
- Years With Current Manager

A cleaned CSV version is included in the `data` folder for reference.

## Project Structure

```text
HR-PowerBI-Analytics/
│
├── data/
│   └── HR_Data.csv
│
├── images/
│   └── HR_Analytics_Dashboard.png
│
├── HR_Analytics.pbix        # Add your Power BI file here
│
└── README.md
```

## Business Questions

This dashboard can help answer questions such as:

1. How many employees are currently active?
2. What is the overall employee attrition rate?
3. Which departments have the highest employee count and attrition?
4. How does attrition vary by gender and age group?
5. Which job roles have higher employee counts?
6. How does monthly income vary across job roles?
7. How are employees distributed across education levels?
8. Which departments show differences in performance ratings?

## Key Insights

- The dataset contains **1,470 employees**, of which **1,233 are active** and **237 have left**.
- The overall attrition rate is approximately **16.1%**.
- Research & Development has the largest employee population, followed by Sales and Human Resources.
- The dashboard allows HR teams to explore attrition patterns across departments, roles, age groups, gender, and education.

## How to Use

1. Open the `.pbix` file in Microsoft Power BI Desktop.
2. Use the slicers to filter the dashboard.
3. Select departments, job roles, or education levels to explore the workforce.
4. Hover over charts to view detailed values.

## Author

**Astha Gupta**

Data Analytics | SQL | Python | Power BI | Excel

---

*Note: Add the final `.pbix` file to this repository before publishing the project on GitHub.*

📊 HR Attrition Analysis – Power BI Dashboard
📌 Project Overview

This project analyzes employee attrition trends using the IBM HR Analytics dataset. The objective was to identify key drivers influencing employee turnover and present insights using interactive Power BI dashboards.

🗂 Dashboard Structure
🔹 Page 1 – Employee Behavior & Satisfaction

Attrition Rate by Gender

Job Satisfaction vs Attrition

Overtime vs Attrition

Work-Life Balance Impact

Education Background vs Attrition

Marital Status Analysis

🔹 Page 2 – Organizational Insights

Attrition by Department

Attrition by Job Role

Attrition by Income Slab

Attrition by Age Group

Attrition Rate & Employee Distribution by Tenure

🔹 Page 3 – Salary & Career Growth Analysis

Income vs Attrition

Average Salary Hike vs Attrition

Monthly Income by Job Role

Promotion vs Attrition

📊 Key Business Findings

Early-career employees (0–2 years) show highest attrition (~30%).

Overtime is one of the strongest attrition drivers.

Lower income groups are more likely to leave.

Salary hike percentage does not significantly impact attrition.

Lack of promotion is associated with higher employee turnover.

🛠 Technical Implementation
Data Preparation

Data cleaning using Power Query

Created Tenure Buckets (0–2, 3–5, 6–10, 10+)

Created Income Slabs

Built calculated columns and DAX measures

Key DAX Measures
Attrition Count =
CALCULATE(
    DISTINCTCOUNT('HR Data'[EmployeeID]),
    'HR Data'[Attrition] = "Yes"
)

Attrition Rate % =
DIVIDE([Attrition Count], [Total Employees], 0)
🎯 Skills Demonstrated

Data Modeling

DAX Calculations

KPI Development

Business Insight Generation

Dashboard Design

Data Storytelling

📎 Tools Used

Power BI

DAX

Power Query

Excel (Data Source)

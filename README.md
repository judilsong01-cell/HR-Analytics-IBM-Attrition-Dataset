# 📊 HR Analytics — IBM Employee Attrition Analysis

**Tools:** Google Sheets · ARRAYFORMULA · Looker Studio
**Dataset:** IBM HR Analytics (1,470 employees)
**Author:** Antonio Augusto · Data Analyst · Angola 🇦🇴

## 🔗 Live Links
| Resource | Link |
|----------|------|
| 📊 Interactive Dashboard (Looker Studio) | [View Dashboard]([COLE_AQUI_SEU_LINK_DO_LOOKER](https://lookerstudio.google.com/s/n5nK_-uvkrE)) |
| 📋 Google Sheet (data + analysis) | [View Sheet]([COLE_AQUI_SEU_LINK_DO_SHEETS](https://docs.google.com/spreadsheets/d/19y0xTwefZ5GdCydT2-Z_B0F8hb-VkRm6V6mMa1f3TYs/edit?usp=sharing)) |

## 🎯 Business Problem
Why are employees leaving? This analysis identifies the key drivers of attrition to help HR leadership take preventive action.

## 📈 Key Findings
- **Overall Attrition:** 16.1%
- **Critical Factor:** Employees doing **Overtime** have a 30.5% attrition rate (3x higher).
- **Age Risk:** The 18-24 age group is the most volatile (39.2%).

## 🔧 ETL Process
1. **Cleaning:** Removed redundant columns (EmployeeCount, Over18).
2. **Feature Engineering:** Created `Age_Band`, `Salary_Band`, and `Tenure_Group` using `ARRAYFORMULA`.
3. **Transformation:** Converted Attrition (Yes/No) to 1/0 for mathematical analysis.
4. **Visualization:** Built an interactive dashboard with real-time filters.

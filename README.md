# 👥 Attrition Intelligence Analysis Dashboard

The dataset includes employee-level data with attributes such as job role, department, income, satisfaction scores, tenure, and more. This dashboard breaks down attrition behavior using KPI cards, visuals, and advanced filters.

-----------------------------------------------------------------------

📌 Overview
This Attrition Intelligence Dashboard analyzes employee attrition patterns to help HR departments improve talent retention and manager effectiveness. It identifies key factors influencing employee turnover, such as job satisfaction, overtime, business travel, income levels, and promotions.

-----------------------------------------------------------------------

🎯 Problem Statement
HR departments need insights into the full employee journey—from hiring to resignation—to understand attrition drivers and implement retention strategies.

-----------------------------------------------------------------------

📊 Key Objectives
✔ Identify top factors affecting attrition (e.g., job satisfaction, income, overtime).
✔ Analyze attrition rates by department, job level, and business travel.
✔ Predict high-risk employees likely to leave.
✔ Provide actionable recommendations to reduce turnover.

-----------------------------------------------------------------------


## 📊 Dashboard Overview

The interactive Power BI dashboard provides rich insights into:

- 🔍 Attrition rates across departments, job roles, and seniority levels
- 📈 Key influencers such as overtime, travel frequency, satisfaction levels
- 📊 Monthly income vs. attrition comparisons
- 📌 Employee segmentation by age group, tenure, and promotion cycles
- 🧠 Risk profiling and predictive indicators like “Emp Leaving Chance”
![Dashboard](https://github.com/user-attachments/assets/53c15a0b-4145-46ef-9716-4e020f87db2d)

-----------------------------------------------------------------------

### ✅ KPIs and Summary Cards

| Metric                     | Value       |
|----------------------------|-------------|
| **Total Employees**        | 1,470       |
| **Attrition Rate**         | 16.12%      |
| **Avg Monthly Income**     | ₹6,503      |
| **High Leaving Chance**    | 0.61%       |
| **Share of High Tenure**   | 62.30%      |
🔍 Key Insights

-----------------------------------------------------------------------

## 🔍 Deep Insights


1️⃣ High Attrition Segments
Sales Department has the highest attrition (105.15%), especially at Job Level 1 (42.11%).

Frequent travelers with overtime show 41.86% attrition (vs. 17.28% without overtime).

2️⃣ Employees at High Risk of Leaving
Employees are more likely to leave if they have:

Low environment/job satisfaction (≤2)

No promotion in ≥3 years

Monthly income below department average

Frequent overtime

3️⃣ Age & Attrition Risk
Middle-aged employees (30-45) have the highest attrition risk.
| Age Group     | High Attrition Risk |
|---------------|---------------------|
| Young (20–30) | ✅ Yes              |
| Middle (31–45)| ⚠️ Low risk        |
| Elder (45+)   | ❌ Very low         |

4️⃣ Salary & Promotions
Higher work experience & promotions lead to higher salaries.

62.3% of long-tenured employees received salary hikes/promotions.

- Employees earning below ₹5K/month have the **highest chance to leave**
- Employees with longer experience earn significantly more (₹15K–₹20K+)
  
5️⃣ Work-Life Balance Impact
Employees with poor work-life balance (rating=1) have 31.25% attrition (vs. 14.22% for rating=3).

-----------------------------------------------------------------------

## 📈 Visualization Highlights

- Bar & column charts
- Heatmaps for department-job level combinations
- Donut charts for satisfaction segmentation
- Slicers by:
  - Department
  - Gender & Marital Status
  - Job Role
  - Experience Group
  - Promotion Group

-----------------------------------------------------------------------


📂 Files Included

Attrition_Analysis.ipynb – Jupyter Notebook with EDA & visualizations.

attrition_data.csv – Dataset used for analysis.

Dashboard_Screenshots/ – Interactive dashboard visuals.

-----------------------------------------------------------------------


🚀 Recommendations
✅ Improve job & environment satisfaction (training, feedback systems).
✅ Review compensation for high-attrition roles (Sales, Job Level 1).
✅ Reduce overtime & frequent travel for at-risk employees.
✅ Expedite promotions for employees waiting >3 years.
✅ Enhance work-life balance policies (flexible hours, remote work).

🛠️ Technologies Used

Power BI (Interactive Dashboard)


📈 Future Enhancements
Predictive modeling to flag high-risk employees.

Department-specific retention strategies.

Real-time HR dashboard integration.

# HR Analytics Dashboard – Employee Attrition Analysis

## 📌Project Objective
The goal of this project is to analyze employee attrition and workforce trends within an organization using Power BI. As an HR Analyst, the objective was to study how attrition varies across departments, age groups, education fields, and salary ranges — and to build an interactive dashboard that surfaces clear, actionable insights into employee turnover and satisfaction levels for HR decision-making.

The project covers the full analytics workflow: importing and cleaning raw HR data, modeling it, creating DAX measures for key HR metrics, and designing a professional, interactive dashboard.

## Dataset Used
- <a href = "https://github.com/venkatakrishnanbalaji/HR_Analytics/blob/main/HR_Analytics.csv"> HR Analytics Dataset </a>

## ❓ Questions (KPIs) and Charts
### KPI
- Total Employee Count - Count of total employees (1,416)
- Attrition Rate - (Employees Left / Total Employees) × 100 → 16.17%
- Attrition Count - Total number of employees who left → 229
- Average Age - Average age of employees → 37
- Average Salary - Average monthly income → 6.5K
- Average Years - Average tenure at the company → 7.04

### Charts & Visuals
- Donut Chart – Attrition Rate by Education Field (Life Sciences 38%, Medical 25%, Marketing 15%, Technical Degree 14%, Other 5%)
- Clustered Column Chart – Attrition by Age Group (26–35 has the highest attrition at 111)
- Horizontal Bar Chart – Attrition by Salary Slab (Upto 5K salary bracket has the highest attrition at 158)
- Matrix Visual – Job Role vs Job Satisfaction Level (1–4 scale), showing attrition counts by role and satisfaction rating
- Line Chart – Years at Company vs Attrition Count (attrition peaks sharply at 1 year, then tapers off)
- Column Chart – Department vs Number of Employees Left (Research & Development: 121, Sales: 84, Human Resources: 11)
- Slicers – Filters for Department (HR, R&D, Sales) and Gender (Female, Male)
- Dashboard Title – "HR Analytics Dashboard" displayed prominently at the top
- Dashboard Interaction <a href = "https://github.com/venkatakrishnanbalaji/HR_Analytics/blob/main/HR_Analytics_Dashboard.png"> View Dashboard </a>

## ⚙️ Process
### Data Preparation
- Imported the HR dataset (Excel file) into Power BI
- Cleaned the data: corrected data types for numeric and categorical fields
- Checked and handled nulls/duplicates
- Renamed columns for readability (e.g., "Monthly_Income" → "MonthlyIncome")

### KPI Creation
- Built DAX measures for Total Employees, Attrition Rate, and Average Monthly Income
- Formatted all KPI cards with consistent font size, background, and text color
- Arranged KPI cards at the top of the dashboard for quick highlights

### Visualization & Dashboard Design
- Designed donut, clustered column, horizontal bar, line, and column charts to cover attrition from multiple angles (education, age, salary, department, tenure)
- Added a matrix visual to cross-analyze job role against job satisfaction
- Added Gender and Department slicers for interactive filtering
- Added a bold dashboard title using a text box
- Arranged all visuals into a clean, professional single-page layout

## Dashboard
<img width="1321" height="736" alt="HR_Analytics_Dashboard" src="https://github.com/user-attachments/assets/093dedaa-82e6-4581-90d3-6f76b0cce9b8" />

## 💡 Project Insights
- Attrition is concentrated among younger employees: the 26–35 age group accounts for the largest share of attrition (111 employees), far ahead of other age brackets.
- Lower salary bands see the most attrition: employees earning up to 5K make up 158 of the attrition cases — significantly higher than higher salary slabs, suggesting compensation is a strong driver of turnover.
- Tenure matters most in the first year: attrition spikes sharply around the 1-year mark and then declines, indicating early-tenure employees are the most flight-risk group — likely tied to onboarding or early job-fit issues.
- Research & Development and Sales drive most attrition: R&D (121) and Sales (84) together account for the vast majority of employees who left, while HR has comparatively low attrition (11).
- Education field shows a skew: employees from Life Sciences (38%) and Medical (25%) backgrounds make up the largest share of attrition, largely reflecting the composition of the workforce itself.
- Role-level detail: the matrix shows Laboratory Technician (60) and Sales Executive (55) roles have the highest attrition counts across satisfaction levels, pointing to these as priority roles for retention efforts.

## ✅ Final Conclusion
The analysis shows that attrition at this organization is not random — it is concentrated among younger, early-tenure, lower-salary employees, primarily within the Research & Development and Sales departments. This points to two clear priority areas for HR: strengthening onboarding and early engagement for employees in their first year, and reviewing compensation structures for lower salary bands where turnover risk is highest. Targeted retention strategies for high-attrition roles like Laboratory Technicians and Sales Executives could meaningfully reduce the overall attrition rate from its current 16.17%. This dashboard equips HR stakeholders with a single, interactive view to monitor these trends on an ongoing basis and measure the impact of retention initiatives over time.

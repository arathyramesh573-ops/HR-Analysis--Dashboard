👥 HR Analysis Dashboard (Power BI)
===================================

📌 Project Overview
-------------------
A Power BI report that analyzes workforce data to give insights into employee attrition, engagement, performance, training, and recruitment across 3 interactive pages.

🛠️ Tools and Technologies
-------------------------
- Power BI Desktop
- Power Query
- DAX
- Excel (data source)
- Git and GitHub

📂 Project Files
----------------
- HR_analysis_1.pbix – Power BI report file
- EmployeeHR Dataset.xlsx – Dataset
- HR_ANALYSIS_PROJECT.pdf – Report page screenshots
- README.md – Project documentation

🗃️ Dataset
----------
- 4 tables with 3,000 records each: employee, engagement survey, training, and recruitment
- Employee start dates from 2018 to 2023
- Covers employee status, department, gender, performance, survey scores, training cost and outcome, and applicant status

🧩 Data Model
-------------
- EmployeeMaster – Employee, survey, and training data combined into one table
- recruitment_data – Applicant data
- Calender – Date table linked to EmployeeMaster with an active Start Date relationship and an inactive Exit Date relationship
- Calculated_table – Stores all DAX measures

📑 Report Pages
---------------
HR Overview
- Total employees, active employees, total attrition, attrition rate, and average tenure
- Monthly leavers trend
- Employees by job role, gender distribution, and employees by department

Employee Engagement and Performance
- Average engagement, satisfaction, and work-life balance
- Average satisfaction and engagement by department
- Employee performance rating distribution and training completion status

Training and Recruitment
- Total applicants, average desired salary, total and average training cost
- Recruitment activity over time and recruitment status overview
- Training cost by program and training program details

✨ Features
-----------
- Year and department slicers
- Page navigation buttons
- Bookmarks and a reset filters button
- Drill-through to training and recruitment details
- Tooltips with extra information

🔍 Power BI Concepts Used
-------------------------
- Data cleaning and merging with Power Query
- Data modeling with active and inactive relationships
- Calendar table for date analysis
- Calculated columns such as attrition flag, attrition type, age, and age group
- DAX measures such as Total Employees, Attrition Rate, Average Tenure, and Average Engagement
- Bookmarks, drill-through, and tooltips
- KPI cards, line, area, bar, column, pie, donut, funnel, treemap, and table visuals

🎯 Project Objectives
---------------------
- Monitor workforce trends and employee attrition
- Analyze engagement, satisfaction, and performance
- Analyze training effectiveness and recruitment outcomes
- Support data-driven HR decisions
- Build a portfolio project for GitHub

📊 Analysis
-----------
- How many employees are active and how many have left
- How attrition changes over time and across departments
- How engagement and satisfaction differ by department
- How employee performance ratings are distributed
- How training programs perform and what they cost
- How many applicants are at each recruitment stage

💡 Key Insights
---------------
- The company has 3,000 employee records, of which 2,458 are active
- Production is the largest department
- Total training cost is about 1.68M
- 3,000 applicants were tracked across 5 recruitment stages

🚀 How to Run the Project
-------------------------
1. Install Power BI Desktop.
2. Clone this repository:

```
git clone https://github.com/arathyramesh573-ops/HR-Analysis-Dashboard.git
```

3. Open HR_analysis_1.pbix in Power BI Desktop.
4. If prompted, update the data source path to EmployeeHR Dataset.xlsx.

📁 Project Structure
--------------------

```
HR-Analysis-Dashboard/
│
├── HR_analysis_1.pbix
├── EmployeeHR Dataset.xlsx
├── HR_ANALYSIS_PROJECT.pdf
└── README.md
```

👩‍💻 Author
-----------
Arathy Ramesh

Aspiring Data Analyst

⭐ Conclusion
-------------

This project helped me strengthen my skills in Power BI, DAX, data modeling, and dashboard design.
It is part of my learning journey toward becoming a Data Analyst.

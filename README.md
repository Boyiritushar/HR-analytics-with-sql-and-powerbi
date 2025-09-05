# HR-analytics-with-sql-and-powerbi
Project Overview

This project focuses on analyzing employee data to uncover key workforce insights such as:

Attrition trends

Salary distribution

Department-wise demographics

Employee tenure analysis

Using SQL for data analysis and Power BI for visualization, the project delivers actionable insights that HR teams can use for better decision-making.

Tools & Technologies

SQL → Data querying, cleaning, and analysis

Power BI → Interactive dashboards & data visualization

Excel/CSV Dataset → HR employee data (~22k+ records).

roject Structure
📦 HR-Analytics-SQL-Project
 ┣ 📂 dataset/                 # Raw dataset used for analysis
 ┣ 📜 HR_Analytics_Script.sql  # SQL queries for analysis
 ┣ 📷 HR_Analytics_Page_1.jpg  # Power BI Dashboard (Page 1)
 ┣ 📷 HR_Analytics_Page_2.jpg  # Power BI Dashboard (Page 2)
 ┣ 📜 README.md                # Project documentation.

 SQL Queries & Analysis

Some of the key SQL tasks performed:

Attrition Rate Analysis → Identified which departments have the highest attrition.

Salary Insights → Compared average salaries across departments and job roles.

Tenure Categorization → Used CASE statements to group employees by years of service.

Top Performers → Applied RANK() and ROW_NUMBER() to identify top earners per department.

Data Cleaning → Removed duplicates, handled NULL values, and standardized formats.

Dashboard Preview
Page 1
Page 2

Key Insights

The Sales Department shows the highest attrition rate.

Most employees leaving the organization have <3 years of service.

The average salary is significantly lower in certain departments, possibly linked to higher attrition.

Gender balance is uneven in leadership roles.

How to Use

Import the dataset from the dataset/ folder into your SQL environment.

Run the queries in HR_Analytics_Script.sql.

Open the Power BI file (HR Analytics.pbix) to explore the dashboard.

# personal_finance

# Project Objective
The objective of this project is to monitor and analyze income performance against predefined monthly targets using interactive Power BI dashboards. The project focuses on comparing actual income with income goals, identifying performance gaps, and tracking achievement levels across different time periods and categories. By integrating transactional data with income targets, the dashboard provides key KPIs such as Total Income, Target Income, Variance, and Achievement Percentage.

# formulas 

- Total Actual Income = SUM('Main Data'[Amount])

- Total Income Target = SUM('Income Goal'[Income Target])

- Income Variance = [Total Income Target] - [Total Actual Income]

- Achievement % = DIVIDE([Total Actual Income], [Total Income Target], 0)

- Over Target = IF( [Total Actual Income] > [Total Income Target], [Total Actual Income] - [Total Income Target], 0 )

- Pending Target = IF( [Total Actual Income] < [Total Income Target], [Total Income Target] - [Total Actual Income], 0 )

# Dashboard
<img width="1320" height="742" alt="personal_finance img" src="https://github.com/user-attachments/assets/1b829e68-c0f6-4493-a4d7-34e197169923" />


# Project Insight
The dashboard highlighted key performance gaps between actual income and targets, identified top-performing categories, and revealed periods of underachievement. These insights help stakeholders monitor progress, optimize targets, and improve overall income performance.

# Final conclusion
The Income Monitoring Dashboard successfully transforms raw financial data into meaningful and actionable insights by clearly comparing actual income against predefined targets. Through interactive KPI cards, trend analysis, and category-level breakdowns, the dashboard enables continuous tracking of income performance and highlights variances that require immediate attention.


# Finance KPI Dashboard

This project is a Sales Performance and KPI Dashboard built using Power BI to track and analyze sales performance against targets across a 14-month period. The dashboard is interactive, KPI-driven, and designed for stakeholders to gain quick and actionable insights into business performance.

🚀 Objective
To create a centralized and dynamic dashboard for:

Monitoring total and YTD sales vs targets

Measuring variance and variance percentage

Evaluating sales performance by individual salesperson and team

Identifying monthly target achievement patterns

Visualizing trends and performance dips/spikes over time

🧠 Key Features
📌 Variance KPI Cards (Actual vs Target in $ and %)

📈 Monthly Trend Chart (Actual vs Target with delta %)

📋 Salesperson-wise Performance Table with:

Actual & Target Sales

Variance %

Trendline Spark visuals

Target status by month

📅 Dynamic commentary text powered by DAX to explain trends and insights

🔀 Team slicers for segmentation

Data Model
4-table star schema:

dimPeople (Salesperson dimension with team & picture)

Calendar (Date, Month, Year)

Actual (Monthly actual sales)

Targets (Monthly target sales)

All relationships are 1:* with Calendar and dimPeople as dimension tables.

🛠 Tools & Technologies

Power BI Desktop

DAX for calculated measures

Interactive visuals: bar charts, cards, matrix, sparklines

Bookmarks and slicers for UX

📌 Insights Delivered

Target met in only 2 out of 14 months

Latest YTD variance: −4.41%

Salesperson performance variance from −6.7% to +3.0%

Clear patterns in monthly underperformance trends

Dynamic narrative text that explains peak or drop periods

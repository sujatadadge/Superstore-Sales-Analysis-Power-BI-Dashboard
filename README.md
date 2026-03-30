Dashboard overview
📊
KPI Cards — Sales, Profit, Orders, Quantity
At-a-glance summary cards showing total sales, total profit, number of orders, and units sold for the selected period.
📈
Sales & Profit Trend
Monthly line/bar chart tracking how revenue and profit have moved over time with year and category slicers.
🏷️
Category & Sub-category Breakdown
Bar chart comparing Furniture, Office Supplies, and Technology across sales and profit margin.
🎛️
Interactive Slicers
Filters for Order Date, Region, Segment, and Category — all synced across the entire report page.

---------------------------------------------------------------------------------------------------------------------------------
DAX measures written

Total Sales:
SUM of sales column across all orders for the selected filter context
Total Profit:
SUM of profit — used in KPI card and trend chart
Profit Margin %:
DIVIDE(Total Profit, Total Sales) formatted as percentage
Total Orders:
DISTINCTCOUNT of Order ID to count unique orders
Avg Order Value


Power Query steps applied
Removed duplicate rows and irrelevant columns from raw data
Changed data types — Order Date and Ship Date to Date format
Extracted Year and Month columns from Order Date for time-based analysis
Trimmed whitespace from text columns (City, State, Product Name)
Replaced null values in Postal Code column with placeholder
Renamed columns to clean, readable names for the data model
Tools & skills demonstrated
Power BI Desktop
DAX
Power Query (M)
KPI Cards
Data Cleaning
Slicers & Filters
Bar & Line Charts
Excel / CSV
DIVIDE(Total Sales, Total Orders) for average revenue per order
YoY Sales Growth %
Compares current year sales vs previous year using SAMEPERIODLASTYEAR



<img width="1430" height="970" alt="Screenshot 2026-03-30 150525" src="https://github.com/user-attachments/assets/025090f1-8145-4ac6-9570-53b4f33e4c7a" />
<img width="1885" height="931" alt="Screenshot 2026-03-30 150624" src="https://github.com/user-attachments/assets/0851281b-a9c7-4bf9-8fab-b0918db3aa9a" />


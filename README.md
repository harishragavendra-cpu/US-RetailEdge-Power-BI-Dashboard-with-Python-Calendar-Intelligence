💼 Sales Insights Dashboard – Power BI + Python Integration

🚀 An interactive Sales Insights Dashboard built using Power BI integrated with Python for dynamic calendar creation and advanced time-based analysis.
This project provides end-to-end insights on sales performance, customer behavior, product trends, and territory performance.

📊 Project Overview

The dashboard is designed to help businesses track key performance metrics and discover actionable insights.

Key Dashboards:

📈 Sales Insights – Total sales, profit, and customer distribution with a global map view.

👥 Customer Insights – Segment-wise profit, customer count, and month/year performance.

📦 Product Insights – Category-based sales, discounts, and profitability trends.

🌍 Territory Insights – Regional, state, and city-level sales mapping.


🐍 Python Integration

Used Python (Pandas) to create a Calendar Lookup Table for time intelligence in Power BI.

Steps:

Imported dataset and extracted the Order Date column.

Found the minimum and maximum order dates using Pandas.

Used pd.date_range() to generate a complete date sequence.

Created a DataFrame calendar table with Year, Month, and Date columns.

Integrated the calendar into Power BI for month-wise and year-wise profit analysis.

🛠️ Tools & Technologies
Tool	Purpose
🟡 Power BI	Data modeling, DAX, and interactive visualizations
🐍 Python (Pandas)	Calendar lookup creation and preprocessing
📘 Excel / CSV	Raw data source
🎨 Data Storytelling	Dashboard design and user experience

💡 Key Insights

📆 Consistent sales growth from 2016–2019.

💰 Technology and Consumer segments drive the highest profit.

🌎 The United States leads in sales, especially in California and New York.

📦 Office Supplies category shows steady year-over-year growth.

🧠 Learnings

Integrating Python with Power BI enhanced automation and accuracy in time-based analysis.
The calendar lookup table generated with Python’s date_range() significantly improved monthly and yearly insights.

📸 Dashboard Pages

💹 Sales Insights Page

👥 Customer Insights Page

📦 Product Insights Page

🌍 Territory Insights Page

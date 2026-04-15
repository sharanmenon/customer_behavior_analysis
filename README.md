# customer_behavior_analysis
📊 E-Commerce Customer Analytics Project
🔍 Overview
This project provides an end-to-end data analytics solution to understand customer purchasing behavior. By combining Python for data cleaning, PostgreSQL for deep-dive querying, and Power BI for visualization, this project transforms raw data into actionable business insights.
📁 Dataset
Source: customer_shopping_behavior.csv
Description: This dataset captures 3,900+ customer transactions, including demographics (Age, Gender), purchase details (Category, Item, Amount), and behavioral metrics (Subscription Status, Shipping Type, Previous Purchases).
🛠️ Tools Used
Data Cleaning & EDA: Python (Pandas)
Database Management: PostgreSQL
Visualization: Power BI (Teal-themed Interactive Dashboard)
Presentation: Gamma AI (PPT)
🛤️ Project Steps
Data Cleaning (Python): Handled data type conversions (e.g., casting ratings to numeric for rounding) and checked for missing values.
SQL Analysis: Imported the cleaned dataset into PostgreSQL to perform advanced queries, including:
Category-wise performance ranking using Window Functions (PARTITION BY).
Calculating discount rates per item using CASE WHEN logic.
Segmenting "Repeat Buyers" to identify subscription conversion opportunities.
Dashboarding (Power BI): Developed a professional, teal-themed dashboard with real-time slicers for Category, Gender, and Shipping.
Reporting: Summarized findings into a stakeholder-ready presentation using Gamma.
📊 Dashboard Highlights
Key Metrics: Total Customers (3.9K), Average Spend ($59.76), and Average Rating (3.75).
Sales vs. Revenue: Visualized "Top Categories" to show where the volume is versus where the profit is.
Customer Segmentation: A donut chart showing the 27% Subscription rate, highlighting a growth opportunity among the 73% non-subscribers.
📈 Key Results
Top Category: Clothing is the primary driver of both sales volume and revenue.
Loyalty Insights: 2,518 frequent buyers (6+ purchases) are not yet subscribers, representing a major target for marketing campaigns.
Product Performance: Jewelry and Blouses emerged as top-ranked items within their respective categories.
🚀 How to Run
Environment: Ensure Python and PostgreSQL are installed.
Database: Create a table in PostgreSQL and import customer_shopping_behavior.csv.
Queries: Run the scripts provided in the SQL_Queries/ folder to generate the analytical views.
Power BI: Open the .pbix file to interact with the visual report.

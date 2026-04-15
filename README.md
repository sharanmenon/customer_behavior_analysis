# 📊 E-Commerce Customer Analytics Project

## 🔍 Overview
This project provides an end-to-end data analytics solution to understand customer purchasing behavior. By combining Python for data cleaning, PostgreSQL for deep-dive querying, and Power BI for visualization, this project transforms raw data into actionable business insights.

## 📂 Dataset
* **Source:** `customer_shopping_behavior.csv`
* **Description:** This dataset captures 3,900+ customer transactions, including demographics (Age, Gender), purchase details (Category, Item, Amount), and behavioral metrics (Subscription Status, Shipping Type, Previous Purchases).

## 🛠️ Tools Used
* **Data Cleaning & EDA:** Python (Pandas)
* **Database Management:** PostgreSQL
* **Visualization:** Power BI (Teal-themed Interactive Dashboard)
* **Presentation:** Gamma AI (PPT)

## 🛤️ Project Steps
1. **Data Cleaning (Python):** Handled data type conversions (e.g., casting ratings to numeric for rounding) and checked for missing values.
2. **SQL Analysis:** Imported the cleaned dataset into PostgreSQL to perform advanced queries including category-wise ranking (`PARTITION BY`) and discount rate calculations.
3. **Dashboarding (Power BI):** Developed a professional dashboard with real-time slicers for Category, Gender, and Shipping.
4. **Reporting:** Summarized findings into a stakeholder-ready presentation using Gamma.

## 📊 Dashboard Highlights
* **Key Metrics:** Total Customers (3.9K), Average Spend ($59.76), and Average Rating (3.75).
* **Sales vs. Revenue:** Visualized "Top Categories" to show volume versus profit.
* **Customer Segmentation:** A donut chart showing a 27% Subscription rate, highlighting growth opportunities.

## 📈 Key Results
* **Top Category:** Clothing is the primary driver of both sales volume and revenue.
* **Loyalty Insights:** 2,518 frequent buyers (6+ purchases) are not yet subscribers, representing a major marketing target.

## 🚀 How to Run

### 1. Clone the Repository
* Open your terminal and run:
`git clone https://github.com/sharanmenon/customer_behavior_analysis.git`

### 2. SQL Database Setup
* Import `customer_shopping_behavior.csv` into **PostgreSQL**.
* Execute the `.sql` scripts to generate the analysis tables.

### 3. Python Environment
* Install necessary libraries: `pip install pandas`.
* Run the cleaning script to view the data transformation.

### 4. Interactive Dashboard
* Open the `.pbix` file in **Power BI Desktop**.
* *Note: Refresh the data source to link it to your local file path.*

### 5. Executive Summary
* View `Presentation.pdf` for final business insights and recommendations.


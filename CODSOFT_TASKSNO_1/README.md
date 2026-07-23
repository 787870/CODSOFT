# 📊 Task 1: Sales Performance Dashboard

**CodSoft Power BI Virtual Internship**  
*Task 1 Repository: Sales Data Analysis and Visualization*

## 📝 Project Overview
This repository contains the files and documentation for **Task 1** of the CodSoft Power BI Virtual Internship. The objective of this project was to develop an interactive Power BI dashboard to analyze retail sales performance across different products, regions, and time periods, ultimately helping stakeholders monitor revenue trends and make informed, data-driven decisions.

## 🎯 Business Problem & Objectives
Retail businesses generate vast amounts of data daily. To maintain profitability, stakeholders need to understand not just total revenue, but also the underlying drivers of profit and loss. This dashboard was designed to answer key business questions:
* What are the overall Total Sales, Total Profit, and Total Orders?
* How does sales performance fluctuate over time (Monthly, Quarterly, Yearly)?
* Which specific product sub-categories are driving profits, and which are operating at a loss?
* What is the geographic distribution of order volumes?

## 🛠️ Key Features & Visualizations
* **Dynamic KPI Cards:** High-level metrics for Total Sales ($2.30M), Total Profit ($286.40K), and Total Orders (5,009) using custom DAX measures.
* **Time-Series Analysis:** A continuous, drillable line chart tracking Total Sales from 2014 through 2017 to identify seasonal spikes (e.g., Q4 holiday peaks).
* **Profitability Analysis:** A clustered bar chart mapping Total Profit by Sub-Category, utilizing custom conditional formatting (Green = Profit, Red = Loss) to instantly highlight underperforming inventory like Tables and Bookcases.
* **Geographic Breakdown:** A donut chart visualizing the percentage distribution of Total Orders across different regions (West, East, Central, South).
* **Interactive Slicers:** Dropdown filters for `Region` and `Category`, allowing users to slice the entire dashboard dynamically for targeted insights.

## 💻 Technical Stack & Processes
* **Tool:** Power BI Desktop
* **Data Source:** `Sample - Superstore.csv` (21 Columns, 9,994 Rows)
* **ETL & Data Cleaning:** 
  * Utilized Power Query Editor to clean the raw data.
  * Applied Locale translation (`en-US` to `en-IN`) to accurately parse and format date columns without data loss.
  * Validated and corrected data types for critical financial columns (Decimal Number / Currency).
* **Data Modeling (DAX):** Created explicit measures for aggregations:
  * `Total Sales = SUM('Sample - Superstore'[Sales])`
  * `Total Profit = SUM('Sample - Superstore'[Profit])`
  * `Total Orders = DISTINCTCOUNT('Sample - Superstore'[Order ID])`

## 📂 Repository Contents
* `Sample - Superstore.csv`: The raw dataset used for this project.
* `Task1_Sales_Dashboard.pbix`: The fully interactive Power BI dashboard file.

## 🚀 How to Use
1. Download the `Task1_Sales_Dashboard.pbix` file.
2. Open the file using **Power BI Desktop**.
3. Use the Region and Category slicers in the top right corner to interact with the data and uncover specific insights.

---
*Check out the live video demonstration of this dashboard on my LinkedIn: [(https://www.linkedin.com/posts/mohammed-aslam-a-363568298_codsoft-cip-powerbi-activity-7480825570281287680-m2sZ?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEf8WfsBpelwj07-q2VSFslYYAiwlYpd4uw)]*

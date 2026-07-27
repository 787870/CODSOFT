# Apple Financial Health Dashboard 🍏📊

## Project Overview
This repository contains a comprehensive Power BI dashboard designed to analyze and predict the financial health of Apple. Built as Task 5 for the **CodSoft Data Analyst Internship**, this project leverages historical financial datasets to visualize key performance indicators, track revenue trends over time, and generate predictive financial forecasts.

## 🛠️ Tools & Technologies Used
* **Power BI Desktop:** Data modeling, visualization, and forecasting.
* **DAX (Data Analysis Expressions):** Custom measure creation (e.g., Profit Margins).
* **Power Query:** Data cleaning and timeline transformations.

## 🎯 Key Features

### 1. Key Performance Indicators (KPIs)
* Dynamic KPI cards displaying **Total Revenue**, **Total Operating Expenses**, **Net Income**, and a custom-calculated **Profit Margin**.

### 2. Time-Series Trend Analysis
* Interactive line charts mapping historical revenue and expenses.
* Built-in slicers for granular filtering by specific **Years** and **Quarters**.

### 3. Predictive Analytics (Forecasting)
* Integrated Power BI forecasting models to estimate future revenue and expense trajectories based on adjusted, evenly-spaced timeline parameters. Includes visible upper and lower confidence bounds.

### 4. Interactive Drill-Through Details
* **Deep-Dive Navigation:** Users can right-click any specific data point on the trend timeline to drill through to a hidden `Balance Sheet Details` page.
* **Granular Breakdown:** The drill-through page automatically filters a detailed matrix and visual breakdown of Assets, Liabilities, and Shareholder Equity for that specific time period.

## 🚀 How to Use the Dashboard
1. Clone this repository to your local machine.
2. Open the `.pbix` file using **Power BI Desktop**.
3. Use the **Year** and **Quarter** slicers on the main page to filter the dashboard.
4. Hover over the grey shaded areas at the end of the line charts to view the calculated forecasts.
5. **Right-click** on any peak or valley on the main line chart, hover over **Drill through**, and select **Balance Sheet Details** to view the underlying financial breakdown for that exact quarter.

## Acknowledgments
* Developed as part of the Data Analyst Internship program at **CodSoft**.

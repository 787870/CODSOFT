# Task 4: Customer Sales & Analytics Dashboard

## 📌 Project Overview
This project is part of my Data Analyst Internship tasks. The objective of this project is to build an interactive Power BI dashboard that analyzes customer purchasing behavior, regional sales distribution, demographic segmentation, and top revenue-generating customers to support strategic business growth.

---

## 🛠️ Tools & Technologies Used
* **Power BI Desktop:** Core tool for data modeling, interactive visual design, and DAX calculations.
* **Power Query Editor:** Utilized for data transformation, cleaning, and unpivoting product spending metrics.
* **Dataset:** Customer analytics and purchasing dataset (`customer_data.csv`).

---

## 🔑 Key Features & Dashboard Components
* **Dynamic KPI Summary Cards:** Tracks real-time metrics including total unique customers (10,000) and total revenue (~14.48M).
* **Product Category Distribution Chart:** A clustered column chart visualizing sales performance across multiple product spending categories (Wine, Meat, Gold, Fish, Sweets, Fruits).
* **Top Customers & Regional Table:** Displays individual high-value customer IDs, their respective countries/regions, and total spending amounts, sorted in descending order.
* **Interactive Cross-Filtering Slicers:** Synchronized filters for **Country** (Region), **Product Category** (Attribute), and **Customer Age** to allow dynamic deep-dive analysis.

---

## 📊 Data Transformation & Modeling
1. **Unpivoting Columns:** Transformed multi-column product spending metrics (`Spent_Wine`, `Spent_Meat`, etc.) into structured **Attribute** and **Value** pairs using Power Query to enable clean categorical aggregation.
2. **Data Aggregation:** Configured distinct counts for customer IDs and proper sum aggregations for monetary values to prevent row-multiplier distortion across relationships.

---

## 🚀 How to View
1. Clone or download this repository.
2. Open the `.pbix` file using **Power BI Desktop**.
3. Explore the interactive slicers and cross-highlighting features across the report canvas.

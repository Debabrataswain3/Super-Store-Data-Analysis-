
# 🏪 Super Store Data Analysis Dashboard (Power BI)

## 📌 Project Overview

This project focuses on building an **interactive Power BI dashboard** to analyze **Superstore Sales Data**.
The goal is to uncover meaningful insights into **sales performance**, **profit trends**, and **regional growth opportunities** through clear visual storytelling.

---

## 🎯 Project Objectives

* To analyze **sales and profit performance** across regions, categories, and months.
* To identify **top-performing** and **underperforming** areas in sales.
* To visualize **monthly sales trends** and understand seasonal performance.
* To build an **interactive dashboard** that supports business decision-making.

---

## 🧾 Dataset Used

* **Dataset Name:** Superstore_Sales
* **File Type:** Excel/CSV
* **Dataset Link:** [Superstore Dataset (Kaggle)](https://github.com/Debabrataswain3/Super-Store-Data-Analysis-/blob/main/Superstore.csv)
* **Columns:**

  * Order Date
  * Region
  * Category
  * Sub-Category
  * Sales
  * Profit

---

## ❓ Key Business Questions (KPIs)

1. How do **sales and profit** vary by **month** and **year**?
2. Which **region** contributes the most to total sales and profit?
3. What are the **top-performing product categories**?
4. How do **sales trends** change over time?
5. Which areas can be improved for better profitability?

---

## ⚙️ Process

### 1️⃣ Data Collection

* Downloaded the Superstore dataset from Kaggle.

### 2️⃣ Data Cleaning & Preparation

* Cleaned missing values and checked data types.
* Converted `Order Date` to **Month-Year** format using DAX:

  ```DAX
  MonthYear = FORMAT([Order Date], "MMM yyyy")
  ```

### 3️⃣ Data Modeling

* Built relationships between tables (if multiple sheets used).
* Ensured correct data types for date, numeric, and categorical fields.

### 4️⃣ Dashboard Design (Power BI)

* **Line Chart:** Sales over time (Month-Year)
* **Bar Chart:** Sales by Region
* **Donut Chart:** Sales by Category
* **Cards:** Total Sales, Total Profit, Profit Margin
* **Slicers:** Region and Category filters
* Used color themes to highlight top-performing regions and categories.

### 5️⃣ Insights & Storytelling

* Analyzed key performance patterns and identified actionable insights.

---

## 📊 Dashboard Link

👉 [View Power BI Dashboard (Upload Link or Screenshot)](https://app.powerbi.com/)
*(Add your published Power BI link or GitHub screenshot folder here)*

---

## 💡 Project Insights

1. **West Region** recorded the **highest sales**, indicating strong regional performance.
2. **Technology Category** contributed the **largest share of total sales**, followed by Office Supplies.
3. **Sales trend** increased significantly from **October to December**, suggesting strong holiday demand.
4. Despite high sales, **Furniture** showed a **lower profit margin**, highlighting a potential pricing issue.

---

## 🏁 Final Conclusion

The Power BI dashboard successfully visualizes Superstore sales data, providing valuable insights into business performance.
It helps stakeholders quickly identify:

* Top-performing regions and categories
* Seasonal sales trends
* Profitability opportunities

The analysis can guide **strategic decisions** related to marketing, pricing, and inventory management.

---

## 🧠 Tools & Technologies

* **Power BI** – for dashboard creation
* **Excel / CSV** – for raw data
* **Python (Optional)** – for preprocessing (Pandas, NumPy)
* **GitHub** – for project documentation and sharing

---

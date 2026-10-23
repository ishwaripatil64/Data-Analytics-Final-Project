# 📊 Final Data Analytics Capstone Project - Superstore Sales Analysis

## Project Overview
This project is an end-to-end data analytics capstone project based on the **Superstore Sales Dataset**. The objective is to analyze sales, profit, and customer behavior using Python, create insightful visualizations, build an interactive Power BI dashboard, and present actionable business recommendations.

---

## 🛠️ Tools & Technologies Used
* **Python** (Pandas, NumPy, Matplotlib, Seaborn) - Data Cleaning & EDA
* **Google Colab** - Python Execution Environment
* **Power BI Desktop** - Interactive Dashboard Creation
* **Git & GitHub** - Version Control & Documentation

---

## 🧹 Data Cleaning Process
* Checked and removed missing/null values from key numeric columns (`Sales`, `Profit`, `Quantity`, `Discount`).
* Dropped duplicate records.
* Formatted date columns and extracted the `Year` for yearly trend analysis.
* Saved the processed dataset as `cleaned_superstore.csv`.

---

## 📈 Exploratory Data Analysis (EDA) & Visualizations
The analysis includes descriptive statistics, correlation analysis, and 5 key visualizations:
1. **Sales Trend by Year** (`visual1_sales_trend.png`)
2. **Sales vs Profit by Category** (`visual2_category_performance.png`)
3. **Regional Sales Distribution** (`visual3_region_sales_pie.png`)
4. **Correlation Heatmap** (`visual4_correlation_heatmap.png`)
5. **Profit Outliers by Category** (`visual5_profit_outliers_boxplot.png`)

---

## Power BI Dashboard
An interactive Power BI dashboard was built using `cleaned_superstore.csv`, featuring:
* **3 KPI Cards:** Total Sales ($2.30M), Total Profit ($286.40K), and Total Quantity (38K).
* **4 Visualizations:** Category Sales, Regional Sales Donut Chart, Yearly Sales Trend, and Profit by Sub-Category.
* **Interactive Slicers:** Region and Segment filters.

---

##  Key Business Insights
1. **Technology** is the highest revenue and profit-generating category.
2. **West & East regions** account for the largest share of total sales.
3. **Copiers & Phones** are the top-performing profitable sub-categories.
4. Excessive discounts on certain items lead to negative profit margins.

---

## Business Recommendations
1. **Optimize Discount Strategies:** Review and limit high discounts on low-margin products to prevent losses.
2. **Targeted Investment:** Allocate higher marketing budgets toward high-performing regions (West/East) and profitable categories (Technology).

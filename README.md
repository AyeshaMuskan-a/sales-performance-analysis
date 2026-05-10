# 📊 Sales Performance and Revenue Insights Dashboard

## 🚀 Project Summary

This project presents a comprehensive analysis of sales data to uncover key business insights, monitor performance, and forecast future trends. It integrates SQL, Python, and Power BI to deliver a complete data analytics pipeline from raw data to actionable insights.

---

## 🎯 Objectives

* Analyze sales performance across regions, categories, and products
* Identify top-performing products and high-value customers
* Understand revenue trends and seasonal patterns
* Build an interactive dashboard for business decision-making
* Predict future revenue using machine learning techniques

---

## 🛠️ Tech Stack

* **SQL (MySQL)** → Data cleaning, transformation, querying
* **Python** → Data analysis, visualization, and machine learning

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
  * Scikit-learn
* **Power BI** → Interactive dashboard and visualization

---

## 📂 Project Structure

```
sales-performance-analysis/
│
├── data/
│   └── sales_data.csv
│
├── sql/
│   └── sales_analysis.sql
│
├── python/
│   └── analysis.py
│
├── powerbi/
│   └── dashboard.pbix
│
├── images/
│   └── dashboard.png
│
└── README.md
```
Note: Full dataset is not uploaded due to size limitations. A sample dataset is provided for reference.
---

## 🧹 Data Cleaning & Preparation

* Handled missing values and removed invalid records
* Standardized column names for consistency
* Converted mixed-format date columns into proper datetime format
* Created new features:

  * Year
  * Month
  * Month Name
  * Quarter

---

## 🔍 Exploratory Data Analysis (EDA)

### 📌 Univariate Analysis

* Distribution of revenue and profit
* Detection of outliers

### 📌 Bivariate Analysis

* Revenue by region
* Revenue by category
* Product performance comparison

### 📌 Multivariate Analysis

* Correlation analysis between revenue, profit, and quantity
* Relationship exploration using pair plots

---

## 📊 Key Insights

* Revenue shows strong growth with peak performance in Q4
* West region generates the highest revenue
* A small group of products contributes significantly to total sales
* Technology category dominates overall revenue
* Customer contribution follows a skewed distribution (few customers generate most revenue)

---

## 📈 Dashboard Features (Power BI)

* KPI Cards:

  * Total Revenue
  * Total Orders
  * Total Profit
  * Average Order Value
* Interactive slicers:

  * Region
  * Category
  * Year
  * Month
  * Quarter
* Visualizations:

  * Revenue trend over time
  * Top products by revenue
  * Revenue by region
  * Category contribution
  * Top customers

---

## 🤖 Machine Learning (Forecasting)

* Built a **Linear Regression model** to predict future revenue
* Incorporated seasonality using sine and cosine transformations
* Generated revenue forecasts for upcoming months

---

## 📊 Dashboard Preview

https://github.com/AyeshaMuskan-a/sales-performance-analysis/blob/main/sales_img.png

---

## ⚙️ How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/your-username/sales-performance-analysis.git
cd sales-performance-analysis
```

### 2. Run SQL Queries

* Open MySQL Workbench
* Execute queries from `/sql/sales_analysis.sql`

### 3. Run Python Analysis

```
python python/analysis.py
```

### 4. Open Power BI Dashboard

* Open `/powerbi/dashboard.pbix`

---

## 📌 Business Impact

This project demonstrates how data analytics can:

* Improve decision-making
* Identify growth opportunities
* Optimize product and regional strategies
* Forecast future sales trends

---

## 🚀 Future Enhancements

* Implement advanced time-series models (ARIMA, Prophet)
* Add customer segmentation (RFM analysis)
* Deploy dashboard as a web application
* Automate data pipeline

---

📌 Conclusion

This project demonstrates end-to-end data analysis, visualization, and basic forecasting to support business decision-making.

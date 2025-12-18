
# 🛍️ Zudio Retail Sales Analysis Dashboard | Power BI

## 📌 Project Overview

Zudio, a value-fashion retail brand under the Tata Group (Trent Ltd.), is known for offering trendy apparel at affordable prices across India. With growing transaction volumes and multiple store locations, analyzing sales data is essential for understanding customer behavior, product performance, and regional trends.

This project presents an **Interactive Zudio Sales Analysis Dashboard** developed using **Power BI**, which transforms raw sales data into meaningful business insights. The dashboard supports data-driven decision-making by visualizing sales trends, product category performance, customer purchasing behavior, and regional sales distribution.

---

## 🎯 Project Objectives

The main objectives of this project are to:

* Analyze overall sales performance and revenue trends
* Identify high-performing and underperforming product categories
* Examine time-based sales patterns and seasonality
* Understand customer purchase behavior and repeat buying patterns
* Evaluate region-wise and store-wise sales performance
* Build an interactive and user-friendly Power BI dashboard

---

## 📂 Dataset Information

* **Source:** Kaggle (Public Dataset)
* **Dataset Name:** Zudio Sales Test Dataset
* **Format:** CSV
* **Number of Rows:** 9,974
* **Number of Columns:** 10

🔗 **Dataset Link:**
https://www.kaggle.com/datasets/saketkshirsagar1/zudio-sales-test-dataset

The dataset contains transactional sales data including product categories, quantity sold, sales amount, date information, store/location details, and customer-related attributes.

---

## 🛠️ Tools & Technologies Used

* **Power BI Desktop**
* **Power Query** – Data cleaning & transformation
* **DAX (Data Analysis Expressions)** – KPI calculations
* **Data Modeling (Star Schema)**
* **CSV Dataset**

---

## 🔄 Data Preprocessing & Modeling

Key preprocessing steps performed using **Power Query**:

* Handling missing and null values
* Renaming and standardizing column names
* Converting columns to appropriate data types
* Creating derived columns such as:

  * Sales Amount Category
  * Month, Year, and Day
  * Performance Category

### Data Model

A **Star Schema** was implemented for optimized performance and scalability:

* **Fact_Sales**
* **Dim_Product**
* **Dim_Category**
* **Dim_Time**
* **Dim_Store**
* **Dim_Location**
* **Dim_Customer**

---

## 📊 Dashboard Features & Analysis

### 1️⃣ Product Category–Wise Sales Analysis

* Sales contribution by product category
* Identification of top and low-performing categories

### 2️⃣ Time-Based Sales Trend Analysis

* Monthly and yearly sales trends
* Seasonal demand patterns and peak sales periods

### 3️⃣ Sales Amount & Quantity Analysis

* Transaction value distribution
* Average order value analysis
* High-value vs low-value sales comparison

### 4️⃣ Customer Purchase Behavior Analysis

* Repeat customers and purchase frequency
* High-value customer identification

### 5️⃣ Geographic & Store-Level Analysis

* Region-wise and city-wise sales performance
* Store comparison and benchmarking

---

## 📈 Key KPIs & Metrics

* Total Sales Revenue
* Total Orders
* Quantity Sold
* Average Order Value (AOV)
* Category-wise Sales Contribution (%)

---

## 🎨 Visualizations Used

* Bar & Column Charts
* Line Charts
* Donut Charts
* KPI Cards
* Tables & Pivot Views
* Maps
* Interactive Slicers & Filters

---

## 🚀 Key Insights

* Certain product categories contribute significantly to total revenue
* Sales show seasonal peaks during specific months
* High-value transactions contribute disproportionately to revenue
* Repeat customers play a major role in consistent sales
* Urban regions outperform semi-urban regions in sales volume

---

## 🔮 Future Enhancements

* Real-time sales data integration
* Predictive sales forecasting models
* Customer segmentation using machine learning
* Inventory optimization dashboards
* Automated alerts for low-performing products or stores

---

## 📁 Repository Structure

```
📦 Zudio-Sales-Analysis-PowerBI
 ┣ 📄 README.md
 ┣ 📊 powerBI_CA2_2.pbix
 ┣ 📂 dataset
 ┃ ┗ 📄 zudio_sales_data.csv
```

---

## 📌 Conclusion

This project demonstrates how **Power BI** can be effectively used to analyze retail sales data and generate actionable business insights. By combining structured data preprocessing, efficient data modeling, DAX-based KPIs, and intuitive visualizations, the Zudio Sales Analysis Dashboard supports informed decision-making and strategic planning in the retail domain.

---

## 📚 References

* Kaggle – Zudio Sales Test Dataset
* Microsoft Power BI Documentation
* Retail Analytics & Business Intelligence Resources

---

## 👤 Author

**Nikhil Ummadi**
Lovely Professional University
Program: Computer Science Engineering



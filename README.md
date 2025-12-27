# 📊 Retail Sales Analysis & Customer Segmentation

## 📌 Project Overview
This project presents an end-to-end analysis of retail sales data using the **Kaggle Global Superstore dataset**.  
The goal is to derive actionable insights related to **sales performance, profitability, and customer behavior**, and to present these insights through **machine learning techniques** and an **interactive Power BI dashboard**.

The project follows a real-world analytics workflow commonly used in industry:
**Data Understanding → Exploratory Analysis → Customer Segmentation → Business Visualization**

---

## 🎯 Project Objectives
- Analyze overall **Sales and Profit trends**
- Understand the impact of **discounts on profitability**
- Identify **top-performing product categories**
- Segment customers based on purchasing behavior using **RFM analysis**
- Build an **interactive Power BI dashboard** for business decision-making

---

## 🛠️ Tools & Technologies
- **Python**: Pandas, NumPy, Matplotlib, Scikit-learn  
- **Machine Learning**: RFM Analysis, K-Means Clustering  
- **Visualization**: Power BI Desktop  
- **Environment**: Jupyter Notebook, VS Code  


---

## Dataset Description
The project uses the **Kaggle Global Superstore dataset**, which contains transactional data related to sales and orders across a global retail superstore.

The dataset includes information about:
- Products and categories
- Customers and customer segments
- Orders, shipping details, and regions
- Sales, profit, discounts, and shipping costs
- Time-based attributes such as order date, ship date, year, and week number

This dataset is widely used for **sales analysis, customer behavior analysis, and profitability studies**.

---

## 📘 Notebook Details

### Data Understanding & Exploratory Data Analysis  
**File:** `01_data_understanding.ipynb`

- Loaded and explored **50K+ retail transaction records**
- Cleaned and standardized columns
- Analyzed **Sales and Profit trends over time**
- Studied **category-wise performance**
- Examined the **relationship between discounts and profit**
- Identified **seasonal patterns** in sales
- Engineered derived metrics such as **Profit Margin**

---

### Customer Segmentation (RFM + K-Means)  
**File:** `04_customer_segmentation_rfm.ipynb`

- Constructed **RFM (Recency, Frequency, Monetary)** metrics at the customer level
- Scaled features and applied **K-Means clustering**
- Used the **Elbow Method** to determine the optimal number of clusters
- Segmented customers into **High, Medium, and Low Value groups**
- Merged customer segments back into transaction-level data
- Exported the final dataset for Power BI visualization

---

## Exploratory Data Analysis & Machine Learning Visuals

### Monthly Sales and Profit Trend
This visualization highlights overall sales growth, profit trends, and seasonal fluctuations over time.

![Monthly Sales and Profit Trend](screenshots/monthly%20sales.png)

---

### Discount vs Profit Analysis
This scatter plot shows a clear negative relationship between higher discount levels and profitability, indicating that aggressive discounting often leads to reduced or negative profit.

![Discount vs Profit](screenshots/discount%20vs%20Profit.png)

---

### Elbow Method for K-Means Clustering
The elbow method was used to identify the optimal number of clusters for customer segmentation.

![Elbow Method](screenshots/kmeans.png)

---

## Power BI Dashboard
**File:** `Retail_Sales_Analysis_PowerBI.pbix`

The Power BI dashboard provides an interactive view of sales performance and customer behavior.

### Dashboard Features:
- **KPI Cards**: Total Sales, Total Profit, Total Customers
- **Monthly Sales Trend** (Year–Month level)
- **Sales by Product Category**
- **Customer Segmentation** (High / Medium / Low Value)
- **Interactive Customer Segment Filter**

![Power BI Dashboard](screenshots/PowerBI.png)

---

## Key Insights
- Sales demonstrate **consistent year-over-year growth** with clear seasonal patterns
- High discount levels are frequently associated with **lower or negative profit**
- A **small group of high-value customers contributes a significant share of total revenue**
- Customer segmentation enables **targeted marketing, retention, and pricing strategies**

---

## Project Outcome
This project successfully demonstrates the ability to:
- Perform **end-to-end data analysis** on a real-world dataset
- Apply **machine learning techniques** for customer segmentation
- Translate analytical results into **business-focused insights**
- Build a **professional, interactive Power BI dashboard**


---

## How to Run the Project
1. Open the notebooks using Jupyter Notebook or VS Code
2. Ensure required Python libraries are installed
3. Open the `.pbix` file using **Power BI Desktop**

---

## Author
**Devesh Nahar**

---




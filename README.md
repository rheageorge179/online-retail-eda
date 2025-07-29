# 🛍️ Online Retail Exploratory Data Analysis (EDA)

This project focuses on uncovering insights from a UK-based online retail dataset. It includes transactional data for over 500,000 purchases made between 2010 and 2011 by customers across various countries.

The goal of this exploratory data analysis (EDA) is to identify trends in customer behavior, sales performance, product categories, and purchase patterns to support business decisions and optimize operations.

---

## 📊 Objectives

- Understand sales distribution over time, geography, and products
- Segment customers based on purchasing behavior
- Detect patterns in cancellations, returns, and high-value transactions
- Visualize KPIs like revenue, top countries, and product performance

---

## 📁 Dataset Description

- **Source:** UCI Machine Learning Repository
- **Transactions:** ~540,000
- **Features include:**
  - `InvoiceNo`
  - `StockCode`
  - `Description`
  - `Quantity`
  - `InvoiceDate`
  - `UnitPrice`
  - `CustomerID`
  - `Country`

---

## 🧠 Key Insights and Analysis

### 1. Data Cleaning
- Removed missing values (`CustomerID`)
- Filtered out cancelled transactions (`InvoiceNo` starting with 'C')
- Created `TotalPrice = Quantity × UnitPrice`

### 2. Revenue Trends
- Monthly revenue trends to identify seasonal spikes
- Revenue by country and top-performing countries (excluding UK)

### 3. Product Performance
- Most sold vs. highest revenue-generating products
- Pareto analysis (80/20 rule) to identify key contributing SKUs

### 4. Customer Segmentation
- Calculated RFM (Recency, Frequency, Monetary) scores
- Visualized RFM segments using bar plots and heatmaps

### 5. Time-Based Behavior
- Hourly and daily transaction trends
- Identified peak shopping hours

---

## 📈 Visualizations

📌 Some plots included in this project:

- Monthly revenue trends
- Top countries by sales
- Word clouds of product descriptions
- Heatmaps of RFM scores
- Scatter plots of revenue vs. quantity
- Customer frequency distribution

You can find them in the notebook: [`online_retail.ipynb`](./online_retail.ipynb)

---

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib & Seaborn
- NumPy
- WordCloud
- Jupyter Notebook

---

## 🚀 Future Enhancements

- Build a dashboard (Power BI / Tableau) for interactive exploration
- Use clustering (K-Means) for deeper customer segmentation
- Create a predictive model for customer churn or high-value purchase prediction

---

## 📬 Contact

Made by (https://www.linkedin.com/in/rheageorge99/)  
GitHub: [@rheageorge179](https://github.com/rheageorge179)


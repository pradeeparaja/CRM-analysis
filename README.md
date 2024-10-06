# 🚀 Customer Relationship Management (CRM) Analysis

> **Unlock actionable insights from customer behavior to drive retention, engagement, and revenue growth!**

This project analyzes customer transaction data using **RFM Analysis**, **Churn Analysis**, and **Customer Lifetime Value (CLV)** estimation. The goal is to uncover valuable insights into customer segmentation, engagement, and retention strategies, providing data-driven recommendations for business growth.

---

## 🔍 Project Overview
The aim of this CRM analysis is to **uncover customer behavior trends** and **optimize marketing strategies** through data-driven decisions. By leveraging **RFM segmentation**, I identified high-value customers, and **Churn Analysis** helped pinpoint at-risk customers. The **CLV model** gives a clear picture of the long-term value of each customer.

---

## 🎯 Key Objectives
- **Segment customers** using **RFM** (Recency, Frequency, Monetary) Analysis.
- **Identify churned customers** and provide strategies to re-engage them.
- **Estimate Customer Lifetime Value (CLV)** to focus on high-value customers.
- **Develop insights** for targeted marketing and improving retention.

---

## 🗂 Dataset
- **Rows**: 541,909 transaction records
- **Time Period**: December 1, 2010 – October 9, 2021
- **Key Features**:
  - **InvoiceNo**: Unique 6-digit invoice number (prefix 'C' indicates cancellations).
  - **StockCode**: Product code.
  - **Description**: Name of the product.
  - **Quantity**: Number of units per transaction.
  - **InvoiceDate**: Transaction date and time.
  - **UnitPrice**: Price per unit.
  - **CustomerID**: Unique customer identifier.
  - **Country**: Customer's country.

---

## 🔄 Workflow

### 🧹 1. Data Cleaning
- Handled **missing values** for CustomerID and Description.
- Removed **duplicates** and treated **outliers** in Quantity and UnitPrice.

### 📊 2. Exploratory Data Analysis (EDA)
- **Total Sales**: $9.44M
- **Average Order Value (AOV)**: $364.60
- **30% of revenue** is generated during the holiday season (November-December).
- Identified **top-selling products** accounting for 40% of total sales.

### 🔗 3. RFM Analysis
- Segmented customers into categories such as **Champions**, **Loyal Customers**, and **Potential Loyalists**.
- Provided insights into personalized offers and marketing campaigns.

### 🔥 4. Churn Analysis
- Identified customers who have **stopped purchasing**, especially in the **UK**.
- Recommended **re-engagement strategies** with personalized offers.

### 💰 5. Customer Lifetime Value (CLV)
- Calculated the **CLV** to identify high-value customers.
- Suggested **retention strategies** for maximizing long-term value.

---

## 📈 Key Insights & Results
- **30% of sales** occur during the holiday season, presenting a prime opportunity for targeted promotions.
- **Top 10 products** account for 40% of total sales, highlighting the importance of promoting these bestsellers.
- Identified **high-value customers** for retention efforts and churned customers for re-engagement.

---

## 🚀 Next Steps & Recommendations
1. **Invest in Customer Retention**: Create loyalty programs and offer personalized promotions.
2. **Targeted Marketing**: Focus on high CLV customers and increase value from low CLV customers through upselling.
3. **Churn Reduction**: Use insights from churn analysis to re-engage customers, especially in the UK.

---


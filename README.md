# Brazilian E-Commerce Sales & Customer Analytics

## 📌 Project Overview

This project is an end-to-end analysis of the Brazilian Olist e-commerce dataset.

The goal is to understand business performance across sales, customers, products, sellers, payments, delivery performance, and customer satisfaction.

The project follows a complete data analytics workflow from data cleaning and exploratory analysis to SQL analysis and an interactive Power BI dashboard.

---

## 🎯 Business Objectives

- Analyze overall sales and revenue performance
- Understand customer purchasing behavior
- Identify repeat customers and high-value customers
- Analyze product category and product performance
- Evaluate seller performance
- Understand payment method usage
- Analyze delivery time and delivery delays
- Measure customer satisfaction through review scores
- Identify business trends and actionable insights

---

## 🛠️ Tools & Technologies

- **Python**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
- **SQL**
  - MySQL
  - CTEs
  - Subqueries
  - Window Functions
  - Ranking
  - Date & Aggregation Functions
- **Power BI**
  - Data Modeling
  - DAX
  - Interactive Dashboards
- **Jupyter Notebook**
- **Git & GitHub**

---

## 🔄 Project Workflow
```text
Data Collection
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Bivariate & Multivariate Analysis
      ↓
Feature Engineering
      ↓
Business Insights
      ↓
MySQL Database Integration
      ↓
SQL Analysis
      ↓
Power BI Data Modeling
      ↓
Interactive Dashboard
```
---

## 📊 Power BI Dashboard

The project includes a four-page interactive Power BI dashboard designed to provide a complete view of e-commerce performance.

### 01 — Executive Overview

- Total Orders
- Total Revenue
- Unique Customers
- Average Order Value
- Average Review Score
- Monthly Revenue Trend
- Revenue by Customer State
- Top Product Categories
- Order Status Distribution

### 02 — Sales & Customer Analysis

- Monthly Sales & Orders Trend
- Customer Distribution by State
- New vs Repeat Customers
- Top Customers by Revenue
- Payment Method Analysis
- Repeat Customer Rate

### 03 — Product & Seller Analysis

- Product Category Revenue & Orders
- Top 10 Products by Revenue
- Top 10 Sellers by Revenue
- Category Share by Revenue
- Seller Distribution by State

### 04 — Delivery & Customer Satisfaction

- Monthly Orders & Delivery Performance
- Average Delivery Time
- On-Time Delivery Rate
- Delivery Time Distribution
- Customer Satisfaction by Review Score
- Orders by Delivery Status
- Average Delivery Time by State

---

## 📈 Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Orders | 99,441 |
| Total Revenue | R$16.01M |
| Unique Customers | 96,096 |
| Average Order Value | R$160.99 |
| Repeat Customer Rate | 3.12% |
| Average Delivery Time | 12.50 days |
| On-Time Delivery Rate | 91.89% |
| Average Review Score | 4.09 / 5 |
| Total Reviews | 99K |

---

## 💡 Key Business Insights

### 📈 Sales & Revenue

- The analysis covers **99,441 orders** with approximately **R$16.01M** in total payment value.
- The average order value was approximately **R$160.99**.
- **November 2017** recorded the highest monthly revenue in the analyzed period.

### 👥 Customer Analysis

- The dataset contains **96,096 unique customers**.
- Repeat customers represented approximately **3.12%** of unique customers.
- A relatively small group of customers contributed a significant share of overall customer spending.

### 🛍️ Product & Category Analysis

- **Health & Beauty** recorded the highest product-price sales among the analyzed categories.
- **Watches & Gifts**, **Bed & Bath Table**, and **Sports & Leisure** were also among the higher-revenue categories.
- Category-level analysis helps identify product areas contributing most to sales.

### 🚚 Delivery & Customer Satisfaction

- Average delivery time was approximately **12.50 days** for delivered orders.
- The calculated on-time delivery rate was **91.89%**.
- The average customer review score was **4.09 out of 5**.
- The analysis showed a negative relationship between delivery time and review score, indicating that longer delivery times were generally associated with - lower customer ratings.

---

## 🗄️ SQL Analysis

SQL analysis was performed using **MySQL** to answer business-focused questions across sales, customers, products, sellers, delivery, payments, and customer satisfaction.

The analysis includes:

- Basic business KPIs
- Revenue analysis
- Average Order Value (AOV)
- Revenue by customer state
- Product category sales
- Monthly revenue trends
- Top products by revenue
- Top sellers by revenue
- Customer order frequency
- Repeat customer analysis
- Customer lifetime value
- Seller performance
- Delivery performance by state
- Delivery delay vs review score
- Payment installment analysis
- High-value customer analysis
- Category satisfaction analysis
- Seller ranking using window functions
- Top sellers by state
- Month-over-month revenue growth
- Cumulative revenue analysis
- Category revenue contribution
- Customer spending rankings
- First vs latest purchase analysis
- Repeat customer revenue
- Customer cohort analysis

### SQL Techniques Used

- `SELECT`
- `WHERE`
- `GROUP BY`
- `HAVING`
- `ORDER BY`
- `JOIN`
- `CASE`
- Subqueries
- CTEs
- Aggregate Functions
- Date Functions
- Window Functions
- `RANK()`
- `LAG()`
- Running Totals

The complete SQL work is available in [`SQL_Analysis.ipynb`](./notebooks/SQL_Analysis.ipynb).

---

## 🐍 Python Analysis

Python was used throughout the project for data preparation, exploratory analysis, feature engineering, and business insight generation.

### Data Preparation

- Loaded and inspected the e-commerce datasets
- Checked data types and missing values
- Cleaned and prepared individual datasets
- Converted date and timestamp columns
- Merged related datasets for analysis
- Created analysis-ready features

### Exploratory Data Analysis

- Univariate analysis
- Bivariate analysis
- Multivariate analysis
- Sales and revenue analysis
- Customer behavior analysis
- Product and category analysis
- Seller analysis
- Delivery performance analysis
- Customer review analysis

### Feature Engineering

Features were created to support business analysis, including:

- Delivery days
- Delivery delay
- Delivery status
- Order month
- Order year
- Order year-month
- Order day
- Order hour
- Customer purchase behavior metrics

### Python Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn

  ---

## 📂 Project Structure

```text
Brazilian-E-Commerce-Analysis/
│
├── data/
│   └── Cleaned datasets
│
├── notebooks/
│   ├── clean_data_analysis.ipynb
│   ├── E_commerce_cohort_EDA.ipynb
│   └── SQL_Analysis.ipynb
│
├── powerbi/
│   └── Power BI dashboard
│
├── screenshots/
│   └── Dashboard screenshots
│
└── README.md
```

## 📊 Dashboard Preview

## 01 — Executive Overview
![Executive Overview](screenshots/Screenshot%202026-09-30%20103148.png)

Provides an overall view of revenue, orders, customers, AOV, review score, monthly revenue, customer-state performance, product categories, and order status.

## 02 — Sales & Customer Analysis
![Sales & Customer Analysis](screenshots/Screenshot%202026-09-30%20103217.png)

Analyzes sales trends, customer distribution, repeat customers, high-value customers, and payment methods.

## 03 — Product & Seller Analysis
![Product & Seller Analysis](screenshots/Screenshot%202026-09-30%20103236.png)

Analyzes category revenue, top products, top sellers, category revenue share, and seller distribution.

## 04 — Delivery & Customer Satisfaction
![Delivery & Customer Satisfaction](screenshots/Screenshot%202026-09-30%20103259.png)

Analyzes delivery performance, on-time delivery, delivery time, delivery status, and customer satisfaction.

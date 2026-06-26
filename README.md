# Olist E-Commerce Data Analysis

## 📊 Project Overview

This project analyzes the Olist Brazilian E-Commerce Dataset to understand the key drivers of marketplace performance across customers, products, sellers, logistics operations, and customer satisfaction.

The analysis combines Python, SQL, customer segmentation, funnel analysis, customer lifetime value (CLV), market basket analysis, and revenue forecasting to generate business insights and management recommendations.

---

## 🎯 Business Problem

The objective of this project was to answer several important business questions:

- Which customers generate the highest business value?
- Where are the operational bottlenecks in the fulfillment process?
- What factors influence customer satisfaction?
- Which products and regions drive marketplace growth?
- How can customer retention and profitability be improved?
- Can historical revenue trends be used to forecast future business performance?

---

## 📌 Executive Summary

The purpose of this project was to analyze Olist's e-commerce marketplace and identify opportunities to improve revenue growth, customer retention, operational efficiency, and customer satisfaction.

Throughout the analysis, I investigated customer purchasing behavior, seller performance, delivery operations, customer lifetime value, purchase funnels, market basket relationships, and future revenue trends.

One of the strongest patterns observed was that revenue and customer value were highly concentrated among a relatively small group of customers. Customer segmentation analysis identified high-value customer groups that represent significant retention opportunities.

The funnel analysis revealed that delivery performance has a direct impact on customer satisfaction. While most orders were delivered on time, delayed deliveries resulted in significantly lower review scores, highlighting the importance of operational efficiency.

Market Basket Analysis showed limited category-level cross-selling opportunities, suggesting that future recommendation systems should focus on product-level relationships and personalized recommendations.

Revenue forecasting identified a strong long-term growth trend and projected continued business expansion over the forecast horizon.

Overall, the analysis demonstrates that customer retention, delivery performance, and revenue concentration are among the most important drivers of marketplace success.

---

## 🗂️ Dataset Description

The dataset contains approximately 100,000 e-commerce orders placed between 2016 and 2018 across Brazil.

### Main Tables

- Customers
- Orders
- Order Items
- Payments
- Products
- Reviews
- Sellers
- Geolocation

Source: Olist Brazilian E-Commerce Public Dataset

---

## 🛠️ Tools & Technologies

- Python
- SQL
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Prophet
- Scikit-learn
- Git & GitHub

---

## 📁 Project Structure

```text
olist-ecommerce-analysis/
│
├── data/
├── notebooks/
│   ├── 01_data_cleaning_eda.ipynb
│   ├── 02_sql_analysis.ipynb
│   ├── 03_rfm_analysis.ipynb
│   ├── 04_funnel_analysis.ipynb
│   ├── 05_market_basket_analysis.ipynb
│   ├── 06_customer_lifetime_value.ipynb
│   └── 07_sales_forecasting.ipynb
│
├── images/
├── README.md
└── requirements.txt
```

---

## 🔍 Analysis Performed

### 1. Exploratory Data Analysis (EDA)
- Revenue analysis
- Sales trends
- Product performance
- Regional demand analysis
- Customer behavior exploration

### 2. RFM Customer Segmentation
- Recency, Frequency, Monetary analysis
- Customer segmentation
- High-value customer identification

### 3. Funnel Analysis
- Purchase-to-delivery conversion analysis
- Delivery bottleneck identification
- Customer satisfaction impact assessment

### 4. Market Basket Analysis
- Association rule mining
- Product affinity analysis
- Cross-selling opportunity evaluation

### 5. Customer Lifetime Value (CLV)
- Historical CLV calculation
- Customer value segmentation
- Revenue concentration analysis

### 6. Revenue Forecasting
- Historical revenue validation
- Trend analysis
- Growth analysis
- Prophet forecasting model
- Future revenue projections

---

## 💡 Business Findings

### Customer Value
Customer spending was highly concentrated among a relatively small segment of customers, creating opportunities for targeted retention and loyalty initiatives.

### Operations
Delivery represented the largest portion of the fulfillment process and had the strongest influence on customer satisfaction outcomes.

### Customer Experience
Customers experiencing delivery delays reported significantly lower review scores, demonstrating a direct relationship between operational performance and customer experience.

### Revenue Growth
Historical revenue trends indicated strong marketplace growth and supported positive future revenue projections.

### Cross-Selling
Category-level purchasing behavior showed limited association strength, suggesting that personalized recommendations may provide greater business value than broad category-level promotions.

---

## 📈 Management Recommendations

1. Prioritize retention strategies for high-value customers.
2. Improve logistics performance in regions with higher delivery delays.
3. Monitor delivery performance as a key customer satisfaction KPI.
4. Personalize marketing campaigns using customer segmentation insights.
5. Develop product-level recommendation strategies rather than broad category promotions.
6. Use forecasting outputs to support budgeting, staffing, and operational planning.
7. Continuously monitor actual performance against forecasted revenue trends.

---

## 🔮 Future Enhancements

- Build an interactive Power BI dashboard
- Develop predictive CLV models
- Automate forecasting updates
- Deploy dashboards with Streamlit
- Automate ETL pipelines

---

## 👤 Author

**Abdulmajeed Abdulraheem**

Data Analyst | Business Consultant | Python | SQL

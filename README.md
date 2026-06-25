# Olist E-Commerce Data Analysis

## 📊 Project Overview

This project analyzes the Olist Brazilian E-Commerce Dataset to uncover insights into customer behavior, sales performance, delivery efficiency, and customer satisfaction.

The analysis combines SQL, Python, exploratory data analysis (EDA), customer segmentation, and business intelligence techniques to generate actionable business recommendations.

---

## 🎯 Business Objectives

- Analyze sales trends and revenue performance
- Identify top-performing product categories
- Evaluate delivery efficiency and delays
- Understand customer satisfaction drivers
- Explore regional purchasing patterns
- Segment customers using RFM Analysis
- Calculate Customer Lifetime Value (CLV)
- Discover cross-selling opportunities through Market Basket Analysis

---

## 🗂️ Dataset Description

The dataset contains approximately 100,000 e-commerce orders placed between 2016 and 2018 across Brazil.

### Main Tables

- customers
- orders
- order_items
- payments
- products
- reviews
- sellers
- geolocation

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
│   └── 06_customer_lifetime_value.ipynb
│
├── images/
├── README.md
└── requirements.txt
```

---

## 🔍 Analysis Performed

### 1. Data Cleaning & Preparation
- Handled missing values
- Converted timestamp columns
- Standardized data types
- Removed duplicates
- Validated data quality

### 2. Exploratory Data Analysis (EDA)
- Revenue analysis
- Order trends
- Customer distribution by state and city
- Product category performance
- Payment method analysis

### 3. RFM Customer Segmentation
- Recency, Frequency, and Monetary analysis
- Customer segmentation
- High-value customer identification

### 4. Funnel Analysis
- Purchase-to-delivery conversion analysis
- Delivery performance evaluation
- Delivery delay analysis
- State and product category delivery performance
- Customer satisfaction impact

### 5. Market Basket Analysis
- Association rule mining
- Product affinity analysis
- Cross-selling opportunities

### 6. Customer Lifetime Value (CLV)
- Historical CLV calculation
- Customer value segmentation
- Revenue contribution analysis

---

## 💡 Key Insights

- São Paulo generated the highest number of orders.
- Purchase-to-delivery conversion rate reached 97.02%.
- 93.15% of orders were delivered on time or early.
- Late deliveries significantly reduced review scores (2.27 vs. 4.29).
- A small group of customers generated a significant share of total revenue.
- Product purchasing patterns revealed cross-selling opportunities.
- Most customers placed only one order during the analysis period.

---

## 📈 Business Recommendations

- Improve logistics performance in high-delay regions.
- Optimize warehouse operations between approval and shipment.
- Prioritize retention campaigns for high-value customers.
- Personalize marketing using RFM segments.
- Create product bundles based on market basket analysis.
- Monitor delivery performance by state and product category.

---

## 🔮 Future Enhancements

- Build an interactive Power BI dashboard
- Develop predictive CLV models
- Create sales forecasting models
- Deploy dashboards with Streamlit
- Automate ETL pipelines

---

## 👤 Author

**Abdulmajeed Abdulraheem**

**Data Analyst | Business Consultant | Python | SQL**

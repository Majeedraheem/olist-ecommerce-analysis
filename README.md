# Olist E-Commerce Data Analysis

## 📊 Project Overview

This project analyzes the **Olist Brazilian E-Commerce Dataset** to uncover insights into customer behavior, sales performance, delivery efficiency, and customer satisfaction.

The analysis combines **SQL, Python, exploratory data analysis (EDA), customer segmentation, and business intelligence techniques** to generate actionable business recommendations.

---

## 🎯 Business Objectives

* Analyze sales trends and revenue performance
* Identify top-performing product categories
* Evaluate delivery efficiency and delays
* Understand customer satisfaction drivers
* Explore regional purchasing patterns
* Segment customers using **RFM Analysis**
* Discover cross-selling opportunities through **Market Basket Analysis**

---

## 🗂️ Dataset Description

The dataset contains information on approximately **100,000 e-commerce orders** placed between **2016 and 2018** across multiple marketplaces in Brazil.

### Main Tables

* `customers`
* `orders`
* `order_items`
* `payments`
* `products`
* `reviews`
* `sellers`
* `geolocation`

**Source:** Olist Brazilian E-Commerce Public Dataset

---

## 🛠️ Tools & Technologies

* **Python**
* **SQL**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Plotly**
* **Scikit-learn**
* **Git & GitHub**

---

## 📁 Project Structure
olist-ecommerce-analysis/
│
├── data/
├── notebooks/
│   ├── 01_data_cleaning_eda.ipynb
│   ├── 02_sql_analysis.ipynb
│   ├── 03_rfm_analysis.ipynb
│   └── 04_market_basket_analysis.ipynb
│
├── images/
├── README.md
└── requirements.txt

---

## 🔍 Analysis Performed

### 1. Data Cleaning & Preparation

* Handled missing values
* Converted timestamp columns
* Standardized data types
* Removed duplicates
* Validated data quality

### 2. Exploratory Data Analysis (EDA)

* Order volume trends
* Revenue analysis
* Payment methods
* Customer distribution by state and city
* Product category performance

### 3. Delivery Performance Analysis

* Delivery lead time analysis
* Estimated vs. actual delivery comparison
* Delayed order identification
* Regional shipping performance

### 4. Customer Satisfaction Analysis

* Review score distribution
* Delivery impact on ratings
* Negative review analysis

### 5. RFM Customer Segmentation

Customers were segmented based on:

* **Recency**
* **Frequency**
* **Monetary Value**

Key segments identified:

* Loyal customers
* High-value customers
* At-risk customers
* Inactive customers
### 5. RFM Customer Segmentation

Customers were segmented using the RFM framework:

- **Recency (R):** Days since the customer's last purchase
- **Frequency (F):** Total number of completed orders
- **Monetary (M):** Total customer spending

RFM scores were calculated using quartile-based ranking and combined to create customer segments.

Key segments identified:

- Champions
- Loyal Customers
- Potential Loyalists
- At Risk
- Lost Customers

Business applications:

- Loyalty campaigns for high-value customers
- Win-back campaigns for inactive customers
- Personalized promotions based on customer behavior

### 6. Market Basket Analysis

Association rule mining was used to identify products frequently purchased together to support:

* Cross-selling strategies
* Product bundling
* Personalized recommendations

---

## 💡 Key Insights

* **São Paulo** generated the highest number of orders.
* Delivery delays negatively impacted customer review scores.
* A small group of customers generated a significant share of total revenue.
* Customer purchasing behavior varied across regions.
* Several product combinations showed strong cross-selling potential.

---

## 📈 Business Recommendations

* Improve logistics performance in high-delay regions.
* Prioritize retention campaigns for high-value customers.
* Personalize marketing using RFM segments.
* Create product bundles based on market basket analysis.
* Optimize inventory for top-performing categories.

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone git@github.com:Majeedraheem/olist-ecommerce-analysis.git
```

### Navigate to the Project Folder

```bash
cd olist-ecommerce-analysis
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## 🔮 Future Enhancements

* Build an interactive Power BI dashboard
* Develop customer lifetime value (CLV) models
* Create sales forecasting models
* Deploy dashboards with Streamlit
* Automate ETL pipelines

---

## 👤 Author

**Abdulmajeed Abdulraheem**

**Data Analyst | Business Consultant | Python | SQL | Tableau**

* GitHub: https://github.com/Majeedraheem
* LinkedIn: *Add your LinkedIn profile URL here*
# olist-ecommerce-analysis

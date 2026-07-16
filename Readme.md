# Supply Chain Delivery Delay Analytics

## Project Overview

This project analyzes a real-world supply chain dataset to identify delivery delays, clean operational data, perform feature engineering, and generate business insights through exploratory data analysis.

The project follows an end-to-end analytics workflow, starting from raw data preprocessing to business-oriented visualizations and recommendations.

---

## Business Problem

An e-commerce company is experiencing inconsistent delivery performance across different shipping modes, product categories, and markets.

The objective of this project is to identify the major factors affecting delivery delays and provide actionable recommendations to improve logistics efficiency.

---

## Dataset

**Dataset:** DataCo Smart Supply Chain Dataset

The dataset contains information about:

- Orders
- Customers
- Products
- Shipping
- Sales
- Delivery Status
- Markets
- Customer Segments

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Project Workflow

### 1. Data Understanding

- Dataset inspection
- Data types
- Summary statistics
- Missing value analysis
- Duplicate analysis

---

### 2. Data Cleaning

- Removed irrelevant columns
- Converted date columns to datetime
- Validated numerical features
- Outlier detection
- Business validation of outliers

---

### 3. Feature Engineering

Created new business features including:

- Order Month
- Order Day
- Order Year
- Shipping Month
- Shipping Day
- Delay Days
- Delivery Performance

---

### 4. Exploratory Data Analysis

Business questions answered include:

- Which Shipping Mode has the highest delivery delay?
- Which Product Categories experience the highest delays?
- Which Customer Segment experiences the highest delays?
- Which Market has the highest delays?
- Delivery Status Distribution
- Correlation between numerical variables

---

## Key Insights

- Standard Class shipping experienced the highest average delivery delay.
- High-value products showed higher delivery delays but represented valid business transactions.
- Customer segments and markets showed different delivery performances.
- No significant data quality issues were found after preprocessing.

---

## Business Recommendations

- Improve logistics efficiency for Standard Class shipping.
- Monitor high-delay product categories.
- Optimize warehouse operations during peak demand periods.
- Continuously monitor delivery performance across markets.

---

## 📁 Repository Structure

```
Supply-Chain-Delivery-Analytics/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_Data_Understanding.ipynb
│   ├── 02_Data_Cleaning.ipynb
│   └── 03_Exploratory_Data_Analysis.ipynb
│
├── images/
│
├── README.md
│
└── requirements.txt
```

---

##  Future Improvements

- Build Machine Learning models for delivery delay prediction.
- Develop an interactive Power BI dashboard.
- Deploy the project as a Streamlit application.

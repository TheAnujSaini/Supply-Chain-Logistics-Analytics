# Supply Chain & Logistics Analytics

## Project Overview

This project focuses on analyzing supply chain operations to identify delivery delays, evaluate profitability, uncover operational inefficiencies, and predict late delivery risks using machine learning.

The analysis transforms raw logistics data into actionable business insights that can support operational decision-making and improve supply chain performance.

---

## Business Problem

Supply chain organizations often face challenges such as:

* Late deliveries
* Increased transportation costs
* Reduced customer satisfaction
* Operational inefficiencies
* Profitability losses

The objective of this project is to identify the key factors affecting delivery performance and develop a predictive solution for delivery risk management.

---

## Project Objectives

* Analyze delivery performance across regions and shipping modes.
* Identify major drivers of delayed deliveries.
* Evaluate profitability trends.
* Study temporal patterns in delivery delays.
* Build a machine learning model to predict late delivery risk.
* Generate business recommendations based on analytical findings.

---

## Dataset Information

The dataset contains information related to:

* Orders
* Products
* Customers
* Shipping Operations
* Regional Logistics Performance
* Profitability Metrics

Key attributes include:

* Order Region
* Shipping Mode
* Customer Segment
* Department Name
* Category Name
* Order Profit Per Order
* Days for Shipment (Scheduled)
* Delivery Risk Indicators

---

## Tools & Technologies

### Programming

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Imbalanced-Learn (SMOTE)

### Development Environment

* Jupyter Notebook
* Google Colab

---

## Project Workflow

### 1. Data Cleaning

* Missing value analysis
* Duplicate record handling
* Feature selection
* Data validation

### 2. Feature Engineering

Created new business-focused features including:

* Order Processing Time
* Delivery Delay
* Delay Indicator
* Profitability Flag
* Order Month
* Order Day
* Order Hour

### 3. Exploratory Data Analysis

Performed analysis on:

* Profitability Distribution
* Delivery Delay Distribution
* Regional Performance
* Shipping Mode Performance
* Customer Segment Analysis
* Temporal Delay Trends

### 4. Business KPI Development

Generated key operational metrics:

* Total Orders
* On-Time Delivery Rate
* Late Delivery Rate
* Average Delay
* Total Profit
* Loss Impact of Delays

### 5. Machine Learning Modeling

Objective:

Predict whether an order is at risk of delayed delivery.

Techniques Used:

* Frequency Encoding
* Train-Test Split
* SMOTE Balancing
* Random Forest Classification

Evaluation Metrics:

* Accuracy
* Precision
* Recall
* F1 Score

---

## Key Findings

### Profitability Analysis

* Most orders generated positive profit.
* A smaller percentage of orders contributed to losses.
* Delivery performance directly influenced profitability.

### Delivery Delay Analysis

* Delay rates varied across shipping modes and regions.
* Certain operational segments experienced significantly higher delays.

### Regional Analysis

* Several regions consistently showed elevated delivery risk.
* Geographic performance differences highlighted optimization opportunities.

### Root Cause Analysis

Major contributors to late deliveries included:

* Shipping Mode
* Customer Segment
* Department Name
* Order Status
* Product Category

---

## Machine Learning Results

A Random Forest Classifier was trained to predict late delivery risk.

The model successfully identified patterns associated with delayed shipments and demonstrated strong predictive capability for operational risk management.

### Business Value

* Early identification of high-risk orders
* Improved logistics planning
* Reduced delivery delays
* Better customer satisfaction
* Data-driven decision making

---

## Project Structure

```text
Supply-Chain-Analytics/
│
├── data/
│   └── supply_chain_dataset.csv
│
├── notebooks/
│   └── Supply_Chain_Analytics.ipynb
│
├── reports/
│   └── Supply_Chain_Analytics_Report.pdf
```

---

## Sample Visualizations

The project includes visual analysis of:

* Profitability Distribution
* Delivery Delay Distribution
* Profit Impact of Delays
* Regional Performance Analysis
* Delay Drivers Analysis
* Monthly Delay Trends
* Weekly Delay Trends
* Hourly Delay Trends
* Machine Learning Evaluation

---

## Business Recommendations

1. Improve performance of high-risk shipping methods.
2. Optimize operations in regions with elevated delay rates.
3. Deploy predictive monitoring for delivery risk management.
4. Strengthen planning during peak operational periods.
5. Investigate recurring loss-generating transactions.

---

## Conclusion

This project demonstrates how data analytics and machine learning can be applied to improve supply chain performance. Through detailed exploratory analysis, root cause identification, and predictive modeling, the solution provides actionable insights that support operational efficiency, profitability improvement, and proactive logistics management.

---

## Author

**Anuj Saini**

B.Tech Computer Science Engineering

Aspiring Data Analyst | Business Analyst | Machine Learning Enthusiast

### Connect With Me

* LinkedIn: https://www.linkedin.com/in/anuj-saini-12464a24a/
* Email: sainianuj1235@gmail.com

⭐ If you found this project useful, consider giving it a star.

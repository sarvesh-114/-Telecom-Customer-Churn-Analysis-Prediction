# 📉 Telecom Customer Churn Analysis & Prediction

This end-to-end data analytics and machine learning project focuses on analyzing customer churn behavior in a telecom company using **Power BI** for visual analytics and **Random Forest** for predictive modeling. It includes two complete dashboard solutions — one for **exploratory analysis** and another for **post-prediction insights** to assist with customer retention strategies.

---

## 📌 Project Overview

- **Domain:** Telecom | **Focus:** Customer Retention
- **Tools Used:** Power BI, Python, Pandas, Scikit-learn, DAX
- **ML Algorithm:** Random Forest Classifier
- **Dataset Size:** 6,420 customer records

---

## 🧠 Problem Statement

Telecom companies suffer major revenue loss due to high churn rates. The objective of this project is to:
- Analyze customer behavior leading to churn
- Predict future churners using machine learning
- Visualize current and predicted churn metrics in Power BI
- Enable proactive decision-making based on data

---

## 🔍 Dataset Overview

| Metric               | Value         |
|----------------------|---------------|
| Total Customers      | 6,420         |
| New Customers Joined | 411           |
| Customers Churned    | 1,730         |
| Predicted Churners   | 385 (via ML)  |

---

## 📊 Power BI Dashboards (2-Part Visual Analysis)

### 1️⃣ **Exploratory Dashboard**
- Customer segmentation by gender, tenure, services, and contract
- Churn distribution based on payment methods and monthly charges
- Revenue loss estimation due to churners
- New vs churned vs retained customers over time

### 2️⃣ **Predicted Churn Dashboard**
- Displays 385 customers flagged by the Random Forest model
- Filters to explore churn risk by contract type, seniority, and geography
- Actionable tables highlighting high-risk customers for retention campaigns
- KPIs such as predicted churn rate, risk segments, and service breakdown

👉 _Both dashboards are included in the `/powerbi/` folder with screenshots in `/screenshots`_

---

## 🧪 Machine Learning Workflow

- **Preprocessing:**
  - Cleaned and encoded categorical variables
  - Addressed class imbalance
- **Model Used:** Random Forest Classifier
- **Target Variable:** `Churn` (Yes/No)
- **Features Included:** Tenure, Monthly Charges, Internet Service, Contract Type, etc.
- **Outcome:** Identified **385 customers** with a high probability of future churn

---

## ✅ Key Insights

- Customers with **month-to-month contracts**, **short tenure**, and **electronic check payments** have higher churn probability.
- Post-prediction dashboard visualized these high-risk groups with actionable metrics.
- Provided stakeholders with an integrated business intelligence + machine learning solution.

---

## 📈 Business Impact

- Reduced churn risk through proactive identification of high-risk customers.
- Enabled **targeted retention strategies** through predicted customer risk analysis.
- Supported data-driven decisions with a two-layer Power BI dashboard approach.




# 📊 End-to-End Customer Analytics & Revenue Forecasting

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Scikit-Learn](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 🚀 Project Overview

Businesses generate massive amounts of customer data every day, but turning that data into actionable insights is a challenge.

This project focuses on analyzing customer demographics, subscription behavior, engagement patterns, and revenue generation to help a subscription-based company:

✅ Understand customer behavior

✅ Identify revenue-driving factors

✅ Detect churn patterns

✅ Predict future customer revenue using Machine Learning

---

## 🎯 Business Problem

A subscription-based digital service company wants to:

- Increase customer retention
- Improve revenue forecasting
- Identify high-value customers
- Understand the impact of plans, discounts, and engagement on revenue

The company collects customer, subscription, marketing, and usage data but lacks a data-driven decision-making framework.

---

## 📂 Dataset Information

### Customer Information
- Customer ID
- Age
- Gender
- City

### Subscription Details
- Plan Type
- Monthly Fee
- Tenure Months

### Usage & Support
- Average Session Time
- Support Tickets

### Marketing Information
- Marketing Channel
- Discount Percentage

### Target Variables
- Churn Status
- Total Revenue

---

## 🧹 Data Cleaning & Preprocessing

### Data Quality Checks

✔ Missing Value Treatment

✔ Duplicate Removal

✔ Invalid Age Detection

✔ Date Validation

✔ Logical Consistency Checks

✔ Data Type Conversion

---

## ⚙️ Feature Engineering

Created multiple business-driven features:

| Feature | Description |
|----------|-------------|
| customer_tenure_years | Tenure converted into years |
| revenue_per_month | Revenue generated per month |
| churn_flag | Binary churn indicator |
| age_group | Young / Middle / Senior |
| high_value_customer | Revenue above median |
| days_active | Customer activity duration |
| session_usage_category | Low / Medium / High |
| discount_category | Discount segmentation |
| signup_month | Signup month extracted |
| signup_year | Signup year extracted |
| support_intensity | High / Low support usage |
| revenue_category | Revenue segmentation |
| plan_rank | Numeric plan encoding |
| engagement_score | Customer engagement metric |

### Engagement Score Formula

```python
engagement_score = avg_session_time / (support_tickets + 1)
```

This score rewards active customers while penalizing customers requiring frequent support.

---

## 📈 Exploratory Data Analysis (EDA)

### Data Distribution Analysis

- Age Distribution
- Monthly Fee Distribution
- Revenue Distribution
- Session Time Analysis

### Customer Segmentation

- Revenue by Plan Type
- Churn Rate by Plan
- Revenue by Marketing Channel
- Revenue by City

### Behavioral Analysis

- Revenue vs Tenure
- Engagement Score vs Revenue
- Signup Trends
- Revenue Trends

---

## 📊 Visualizations

### Revenue by Plan Type
Identify the most profitable subscription plans.

### Churn Analysis
Discover plans with the highest churn risk.

### Customer Engagement Analysis
Understand how user activity influences revenue.

### Correlation Heatmap
Analyze relationships between variables.

### Actual vs Predicted Revenue
Evaluate machine learning model performance.

---

## 🤖 Machine Learning Model

### Model Used

🔹 Linear Regression

### Workflow

```text
Data Collection
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
EDA & Visualization
      ↓
Train-Test Split
      ↓
Linear Regression
      ↓
Model Evaluation
```

---

## 📏 Evaluation Metrics

- R² Score
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 💡 Key Business Insights

📌 Customer tenure strongly impacts revenue.

📌 Premium plan users generate significantly higher revenue.

📌 Highly engaged users contribute more revenue.

📌 Excessive discounts may reduce profitability.

📌 Support ticket frequency can indicate churn risk.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## 📁 Project Structure

```text
Customer-Analytics-Revenue-Forecasting/
│
├── data/
│   └── customer_subscription_data.csv
│
├── notebooks/
│   └── subscription_churn_prediction.ipynb
│
├── images/
│   └── visualizations
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 📌 Future Enhancements

- Random Forest Regression
- XGBoost Implementation
- Power BI Dashboard
- Customer Lifetime Value Prediction
- Churn Prediction Classification Model

---

## 👨‍💻 Author

**Yogesh Dhruw**

📧 Email: Your Email

🔗 LinkedIn: Your LinkedIn Profile

💻 GitHub: https://github.com/yogesh-021-code

---

⭐ If you found this project useful, don't forget to give it a Star!
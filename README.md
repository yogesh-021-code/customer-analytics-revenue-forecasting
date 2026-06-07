<div align="center">

# 📊 End-to-End Customer Analytics & Revenue Forecasting

### Transforming Customer Data into Business Insights using Python & Machine Learning

[![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)](https://pandas.pydata.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikitlearn)](https://scikit-learn.org/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-success?style=for-the-badge&logo=github)](https://github.com/yogesh-021-code)

</div>

---

## 👨‍💻 About The Project

This project analyzes customer subscription behavior, engagement patterns, churn trends, and revenue generation for a subscription-based business.

The objective is to uncover business insights and build a machine learning model capable of forecasting customer revenue.

### Key Goals

✅ Customer Segmentation

✅ Revenue Forecasting

✅ Churn Analysis

✅ Feature Engineering

✅ Business Intelligence

✅ Machine Learning

---

# 📌 Business Problem

A subscription-based company wants to:

- Increase customer retention
- Reduce churn
- Improve revenue forecasting
- Identify high-value customers
- Understand customer engagement behavior

This project provides a complete data-driven solution using Python and Machine Learning.

---

# 📂 Dataset Overview

| Category | Features |
|----------|-----------|
| Customer Information | Age, Gender, City |
| Subscription Data | Plan Type, Monthly Fee, Tenure |
| Usage Metrics | Session Time, Support Tickets |
| Marketing Data | Channel, Discounts |
| Target Variable | Total Revenue |

---

# ⚙️ Feature Engineering

Created several business-focused features:

- Customer Tenure Years
- Revenue Per Month
- Churn Flag
- High Value Customer Flag
- Revenue Category
- Age Group
- Support Intensity
- Engagement Score
- Plan Rank
- Session Usage Category

### Engagement Score Formula

```python
engagement_score = avg_session_time / (support_tickets + 1)
```

---

# 📈 Key Visualizations

## Revenue by Subscription Plan

![Revenue by Plan](images/revenue-by-plan.png)

---

## Revenue vs Customer Tenure

![Revenue vs Tenure](images/revenue-vs-tenure.png)

---

## Top Revenue Generating Cities

![Top Cities](images/top-cities-revenue.png)

---

## Customer Signup Trend

![Signup Trend](images/signup-trend.png)

---

## Monthly Revenue Trend

![Revenue Trend](images/revenue-trend.png)

---

## Engagement Score vs Revenue

![Engagement Score](images/engagement-score.png)

---

## Correlation Analysis

![Heatmap](images/correlation-heatmap.png)

### Top Revenue Drivers

| Feature | Correlation |
|----------|------------|
| Tenure Months | 0.78 |
| Monthly Fee | 0.53 |
| Engagement Score | Positive Impact |
| Churn Flag | Negative Impact |

---

# 🤖 Machine Learning Model

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
EDA
      ↓
Train-Test Split
      ↓
Linear Regression
      ↓
Revenue Prediction
```

---

## Model Performance

![Actual vs Predicted Revenue](images/actual-vs-predicted.png)

### Performance Metrics

| Metric | Score |
|----------|----------|
| R² Score | 0.918 |
| Revenue Prediction Accuracy | 91.8% |

### Key Insight

The model successfully explains approximately **91.8% of customer revenue variation**, making it highly effective for revenue forecasting.

---

# 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

# 📁 Project Structure

```text
Customer-Analytics-Revenue-Forecasting/
│
├── images/
├── subscription_revenue_prediction.ipynb
├── subscription_data.csv
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 🚀 Future Improvements

- Random Forest Regression
- XGBoost Regression
- Churn Prediction Model
- Power BI Dashboard
- Customer Lifetime Value Prediction

---

# 📬 Connect With Me

<p align="center">

<a href="mailto:yogeshdhruwy@gmail.com">
<img src="https://img.shields.io/badge/Gmail-yogeshdhruwy%40gmail.com-red?style=for-the-badge&logo=gmail">
</a>

<a href="https://www.linkedin.com/in/yogesh-dhruw-031ba8321/">
<img src="https://img.shields.io/badge/LinkedIn-Yogesh%20Dhruw-blue?style=for-the-badge&logo=linkedin">
</a>

<a href="https://github.com/yogesh-021-code">
<img src="https://img.shields.io/badge/GitHub-yogesh--021--code-black?style=for-the-badge&logo=github">
</a>

</p>

---

<div align="center">

⭐ If you found this project useful, please consider giving it a star!

</div>
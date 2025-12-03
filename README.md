# Customer Churn Prediction Dashboard

## Project Overview

This project analyzes and predicts customer churn for a telecommunications company. The goal is to identify key factors driving customer attrition and provide actionable insights to help the business improve retention strategies.

An interactive Power BI dashboard and a Random Forest machine learning model were used to analyze customer behavior and predict high-risk customers.

---

## Tools & Technologies

* **Data Analysis & Modeling:** Python (Pandas, NumPy, Scikit-learn)
* **Visualization & Reporting:** Power BI Desktop
* **Deliverables:** Power BI Dashboard (.pbix), Cleaned dataset, Jupyter Notebook

---

## Key Insights

### 1. Contract Type

Customers on **month-to-month contracts** showed a significantly higher churn rate than those on yearly or two-year plans, indicating lower commitment and higher risk.

### 2. Charges vs Tenure

* Churned customers had **higher average monthly charges**
* **Shorter-tenure customers** were far more likely to leave than long-term subscribers

---

## Machine Learning Model – Random Forest

A Random Forest Classifier was used to predict customer churn (Yes/No).

**Model Performance:**

* **Accuracy:** 78.46%
* **Recall (Churn Detection):** 45%
* **Precision (Churn Prediction):** 63%

The model performed strongly in identifying non-churn customers and moderately in detecting churn patterns, offering valuable segmentation for retention efforts.

---

## Most Important Features (Ranked)

1. **Contract Type** – Month-to-month customers churn most frequently
2. **Tenure** – Early-stage customers have a higher churn risk
3. **Monthly Charges** – Higher costs increase dissatisfaction
4. **Total Charges** – Total spend correlates with customer behavior
5. **Internet Service Type** – Fiber optic users display higher churn

---

## Power BI Dashboard

The interactive dashboard provides clear business insights, with filters for:

* Gender
* Internet Service
* Payment Method
* Contract Type

**Included KPIs:**

* Total Customers
* Churn Rate (%)
* Average Monthly Charges

Open the `.pbix` file in **Power BI Desktop** to explore the dashboard.

---


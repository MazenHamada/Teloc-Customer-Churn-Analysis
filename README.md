# 📊 Telco Customer Churn Analysis

This repository contains a data analysis project on customer churn for a fictional telecommunications company. The project identifies key drivers of churn, builds a predictive model, and provides actionable recommendations.

## 🔗 Project Links

  * **[Google Colab Notebook](https://colab.research.google.com/drive/1Ja09j1ByvQrdFRf-6BJhhUBBTlO76AYK?usp=sharing)**
  * **[Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYTgwMmU3MTktYTJkNi00ODk4LTk0ODAtMzU0MzBhN2E4NmJkIiwidCI6IjAyNjU5ODhhLWU0MDQtNGRkYy1hMmEwLTY2MjUwNWMzYjc4ZiIsImMiOjh9&pageName=e924d61512c6925a6cb7)**
  * **[Dataset](https://www.kaggle.com/datasets/ylchang/telco-customer-churn-1113/data)**

-----

## Project Methodology

1.  **Data Preparation:** Loaded and merged six `.xlsx` files using Python (pandas) into a master dataset of **7,043 unique customers**. Cleaned data by handling missing values and standardizing formats.
2.  **Exploratory & Diagnostic Analysis:** Visualized the data to understand *why* and *when* customers leave.
3.  **Predictive Modeling:** Built a Random Forest Classifier (Scikit-learn) with **93% accuracy** to identify at-risk customers.
4.  **Prescriptive Recommendations:** Developed a strategic action plan based on the key findings.

-----

## Key Insights & Visualizations

### 1\. Contract Flexibility is the Biggest Risk Factor

Customers on **Month-to-Month contracts** are far more likely to churn than those on long-term contracts.

<img width="1605" height="1085" alt="image" src="https://github.com/user-attachments/assets/bb65d199-bdce-4fdd-9346-16d5db2104a2" />

### 2\. New Customers are Most Likely to Leave

Churn is highest among customers with low tenure. Loyalty increases significantly over time.

<img width="1336" height="739" alt="image" src="https://github.com/user-attachments/assets/2067a179-28de-4cda-bb6d-5db732767257" />

### 3\. Senior Citizens are a High-Risk Demographic

The churn rate spikes for customers aged 65 and older, making them a key group for retention efforts.

<img width="1246" height="693" alt="image" src="https://github.com/user-attachments/assets/bf604aa6-df8d-4548-973e-ae43530bf952" />

-----

## Recommendations

  * **Incentivize Long-Term Contracts:** Proactively offer deals to month-to-month customers to switch to yearly plans.
  * **Launch a Loyalty Program:** Reward new customers for milestones in their first year.
  * **Develop a Competitive Retention Strategy:** Empower support teams to match competitor offers for high-value, at-risk customers.

-----

## 🔧 Tools and Libraries

  * **Python:** For data manipulation and modeling.
  * **Pandas:** For data loading, cleaning, and transformation.
  * **Scikit-learn:** For building and evaluating the Random Forest predictive model.
  * **Matplotlib & Seaborn:** For static data visualizations in the notebook.
  * **Streamlit & Plotly:** For creating the interactive web dashboard.
  * **Power BI:** For creating business-focused dashboards and reports.

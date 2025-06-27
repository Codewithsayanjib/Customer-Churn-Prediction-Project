# 📊 Telco Customer Churn Analysis (EDA)

This project explores and analyzes customer churn behavior for a telecommunications company using **Exploratory Data Analysis (EDA)** techniques. The objective is to uncover trends and patterns that help in understanding why customers leave (churn) and how the company can improve customer retention.

## 🧠 Objective

- Analyze customer data to identify factors associated with churn.
- Visualize relationships between churn and features like contract type, payment method, tenure, etc.
- Generate actionable insights to reduce churn and improve customer satisfaction.

## 📁 Dataset

The dataset is publicly available from IBM Sample Data for Telco Customer Churn and contains:

- **Rows**: 7,043 customer records
- **Columns**: 21 customer attributes including:
  - `gender`, `SeniorCitizen`, `Partner`, `Dependents`
  - `tenure`, `PhoneService`, `InternetService`, etc.
  - `MonthlyCharges`, `TotalCharges`
  - `Churn` (target variable)

> 📌 You can download the dataset from:  
[Telco Customer Churn Dataset - IBM Sample Data](https://www.ibm.com/communities/analytics/watson-analytics-blog/)

## 🔧 Tech Stack

- **Language**: Python  
- **Libraries**: 
  - `Pandas` for data manipulation
  - `NumPy` for numerical operations
  - `Seaborn` and `Matplotlib` for data visualization

## 📌 Key Steps

1. **Data Cleaning**
   - Handled missing values and incorrect datatypes
   - Converted `TotalCharges` to numeric and dealt with blank entries

2. **Univariate Analysis**
   - Explored churn rates by individual features such as gender, contract type, and payment method

3. **Bivariate & Correlation Analysis**
   - Compared tenure vs. churn
   - Cross-tabbed categorical variables with churn
   - Visualized distributions using bar plots, histograms, and heatmaps

4. **Insight Generation**
   - Identified high churn risk groups:
     - Month-to-month contracts: 42% churn
     - Electronic check payments: 45% churn
     - Customers within first year: 50% churn
   - Noted low churn in:
     - Two-year contracts: 3%
     - Credit card auto-pay: 15%
     - Loyal customers (3+ years): ~15%

## 📈 Visualizations

- Churn rate by contract type and tenure
- Payment method vs. churn
- Demographics (gender, age group) vs. churn
- Heatmaps for feature correlations



## 💡 Insights

- Focus retention efforts on:
  - New users (<12 months)
  - Users paying via electronic check
  - Senior citizens with fiber optic internet

- Offer incentives for long-term contracts and secure payment methods (credit card, bank transfer)

## 🚀 Future Work

- Model churn prediction using classification algorithms
- Build a dashboard using Power BI or Streamlit
- Perform cohort and CLV analysis



# Customer Churn Analysis | Python EDA

## Project Overview
This project performs Exploratory Data Analysis (EDA) on a Customer Churn dataset to identify patterns, trends, and factors contributing to customer churn.

The analysis focuses on customer behavior, payment methods, contract types, tenure, and demographic information to uncover insights that can help improve customer retention strategies.

---

# Business Problem
Customer churn is one of the major challenges faced by subscription-based businesses. Losing customers negatively impacts revenue growth and increases customer acquisition costs.

This project aims to identify:
- Which customers are more likely to churn
- Which services are associated with higher churn
- How payment methods and contract types impact customer retention
- How customer tenure influences churn behavior

---

# Objectives
- Perform data cleaning and preprocessing
- Conduct exploratory data analysis (EDA)
- Visualize customer churn patterns
- Generate business insights and recommendations

---

# Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# Dataset Information
The dataset contains:
- Customer demographic information
- Service subscription details
- Contract information
- Payment methods
- Customer tenure
- Monthly and total charges
- Churn status

Target Variable:
- Churn (Yes/No)

---

# Exploratory Data Analysis
The analysis includes:
- Missing value analysis
- Churn distribution analysis
- Contract type analysis
- Payment method analysis
- Customer tenure analysis
- Internet service analysis
- Correlation analysis

---

# Key Insights

## Contract Type & Churn
- Customers with month-to-month contracts showed the highest churn rate (~42%).
- Customers with one-year and two-year contracts had significantly lower churn rates (~11% and ~3%).

## Payment Methods & Churn
- Electronic check users had the highest churn rate (~45%).
- Customers using credit cards or bank transfers showed lower churn rates (~15–18%).

## Customer Tenure
- Customers with less than one year of tenure had the highest churn rate (~50%).
- Churn probability decreased as customer tenure increased.

## Internet Service Analysis
- Fiber optic users experienced higher churn rates compared to DSL users.

---

# Business Recommendations
- Promote long-term contracts through discounts and loyalty programs.
- Improve customer onboarding during the first year.
- Encourage customers to use automated payment methods.
- Develop targeted retention strategies for high-risk customer groups.

---

# Visualizations
The project includes:
- Churn distribution plots
- Correlation heatmaps
- Contract type analysis charts
- Payment method comparison graphs
- Tenure vs churn visualizations
  <img width="1480" height="1190" alt="Bar_chart" src="https://github.com/user-attachments/assets/656e01c9-5f97-4419-a5cd-e2a3e93fef06" />


---

# Project Structure

customer-churn-analysis-python/
│
├── README.md
├── requirements.txt
├── Customer_Churn_EDA.ipynb
│
├── data/
│   └── Customer Churn.csv
│
├── docs/
│   └── Customer_Churn_EDA_Report.pdf
│
└── screenshots/
    ├── churn-distribution.png
    ├── correlation-heatmap.png
    ├── contract-analysis.png
    └── tenure-analysis.png

---

# Future Improvements
- Customer churn prediction using Machine Learning
- Interactive dashboard integration
- Real-time churn monitoring
- Customer segmentation analysis

---

# Author
Salman Rafi

Aspiring Data Analyst | AI & Cloud Computing Enthusiast

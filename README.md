# Bank Customer Churn Analysis

## Project Overview

This project analyzes bank customer data using Python to understand customer churn behavior, identify customer characteristics, and discover patterns that may help improve customer retention.

## Business Questions

1. What characteristics are more common among customers who churn?
2. What are the overall demographics of bank customers?
3. Do customers in Germany, France, and Spain behave differently?
4. Can customers be divided into meaningful segments?

## Dataset Information

- Total Customers: 10,000
- Total Columns: 13
- Target Variable: `Exited`
  - `0` = Customer stayed
  - `1` = Customer churned

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Cleaning

- Checked missing values.
- Checked duplicate records.
- Reviewed dataset structure and data types.
- Explored unique values.

## Exploratory Data Analysis (EDA)

### 1. Customer Churn

- Retained customers: 79.63%
- Churned customers: 20.37%

### 2. Customer Demographics

- Average customer age: 38.92 years.
- Male customers: 54.57%.
- Female customers: 45.43%.
- France has the largest customer population: 50.14%.

### 3. Geographic Analysis

| Country | Churn Rate |
|---|---:|
| France | 16% |
| Germany | 32% |
| Spain | 17% |

Germany has the highest customer churn rate.

### 4. Customer Segmentation

**Age Groups**

- 18–30: 7.52% churn rate
- 31–40: 12.09%
- 41–50: 33.97%
- 51–60: 56.21%
- 60+: 24.78%

**Balance Groups**

- Zero: 13.82%
- Low: 34.67%
- Medium: 19.88%
- High: 25.77%
- Very High: 23.04%

## Key Business Insights

- Germany has a significantly higher churn rate than France and Spain.
- Customers aged 51–60 have the highest churn rate.
- Inactive members are more likely to churn than active members.
- Customer age and account balance groups show different churn patterns.

## Business Recommendations

- Investigate the reasons behind high churn in Germany.
- Develop customer retention strategies for inactive members.
- Investigate the needs of customers in higher-churn age groups.
- Monitor customer behavior to identify potential churn risks.

## Project Structure

```text
Bank-Customer-Churn-Analysis/
├── data/
├── notebooks/
├── images/
├── README.md
└── requirements.txt
```

## Conclusion

This project demonstrates how Python can be used for data cleaning, exploratory data analysis, customer segmentation, and business insight generation.

## Author

Computer Science Student | Aspiring Data Analyst
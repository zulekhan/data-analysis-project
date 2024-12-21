# **Customer Churn Analysis for Online Retail**

## **Project Overview**

The goal of this project is to analyze factors contributing to customer churn in an online retail business. The analysis identifies key trends and patterns, such as customer demographics, spending habits, and engagement with promotions, to help predict and prevent churn.

**Objective**: 
- Analyze customer data to predict churn.
- Identify key factors affecting customer retention.

## **Data Source**

**Dataset Name**: Online Retail Customer Churn Dataset  
**Source**: [Kaggle - Online Retail Customer Churn Dataset](https://www.kaggle.com/datasets/hassaneskikri/online-retail-customer-churn-dataset/data)

The dataset contains customer transaction history, demographics, and churn status, which allows us to explore factors that influence churn.

## **Steps Involved**

1. **Data Collection**:
   - Loaded the customer data from a CSV file and performed an initial data check (e.g., missing values, data structure).

2. **Data Cleaning and Preparation**:
   - Encoded categorical features like gender and promotion response.
   - Engineered a new feature: **Customer Lifetime Value**.
   - Created a **Recency Score** to categorize customer engagement.

3. **Exploratory Data Analysis (EDA)**:
   - Summarized the numerical data using descriptive statistics.
   - Visualized key relationships and trends, including distribution of total spend and churn rates.

4. **Findings & Insights**:
   - Identified that customers with higher spending, recent purchases, and higher satisfaction scores are less likely to churn.
   - Customers who engage with promotions are also less likely to churn.

5. **Conclusion & Recommendations**:
   - Focus on re-engaging old customers and improving satisfaction.
   - Provide promotions to increase customer retention.

## **Technologies Used**
- Python
- Pandas
- Matplotlib

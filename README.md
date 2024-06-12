# Predictive Credit Risk Modeling: Leveraging Decision Trees, XGBoost, and Random Forests

**Author:** Zulfikar Azaria Rahman, ID/X Partners (Rakamin Academy)

**LinkedIn:** [Zulfikar Azaria Rahman](https://www.linkedin.com/in/zulfikar-azaria-rahman/)

---

## Overview
This project focuses on enhancing credit risk prediction through the use of advanced machine learning techniques, specifically Decision Trees, XGBoost, and Random Forests. The goal is to improve financial decision-making by providing valuable insights through rigorous data analysis and strategic considerations.

---

## Table of Contents
1. Business & Data Understanding
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Modeling
5. Model Performance Summary
6. Business Recommendations

---

## 1. Business & Data Understanding

### Credit Risk Definition
Credit risk is the probability that a borrower will default on loan obligations, potentially causing financial loss to the lender. Effective management of credit risk is crucial for the financial health and stability of lending institutions.

### Dataset
- Contains information about borrowers, including profile data, credit history, and loan status.
- Two datasets with 36 and 75 columns, and 438,679 and 466,285 rows respectively.
- Includes 22 categorical columns and 53 numerical columns.
- 40 columns have missing values, and no duplicated data.

---

## 2. Exploratory Data Analysis (EDA)
Key findings include:
- Distribution of loan statuses.
- Home ownership status.
- Geographic distribution (top 10 states with most loan applications).
- Top 10 purposes for loans.
- Distribution of delinquencies in the last 2 years.

---

## 3. Data Preprocessing
Steps include:
- Changing data types and removing unnecessary columns.
- Handling missing values.
- Standardizing data and splitting into training and testing sets.
- Addressing data imbalance.
- Studying multicollinearity.

---

## 4. Modeling
Three models were applied:
- **XGBoost**
- **Decision Tree**
- **Random Forest**

### Performance Metrics
- **XGBoost:** Accuracy: 98.88%, Precision: 99.42%, Recall: 90.02%, F1 Score: 94.49%
- **Decision Tree:** Accuracy: 96.81%, Precision: 82.00%, Recall: 89.63%, F1 Score: 85.64%
- **Random Forest:** Accuracy: 98.20%, Precision: 98.96%, Recall: 83.95%, F1 Score: 90.84%

---

## 5. Model Performance Summary
- **XGBoost**: Best overall performance with high precision and recall, indicating good generalization with slight room for improvement in recall.
- **Decision Tree**: Lower overall performance, suggesting possible underperformance compared to other models.
- **Random Forest**: Strong generalization with no significant overfitting or underfitting, but slightly lower recall than XGBoost.

---

## 6. Business Recommendations
### Personalized Product Offers
- Segment customers by risk profile.
- Offer aggressive credit products to low-risk customers and stricter terms to high-risk customers.

### Credit Approval Process Optimization
- Use XGBoost for quicker and more accurate credit approvals.
- Decline high-risk applications and impose stricter terms on medium-risk applicants.

### Credit Portfolio Management
- Regularly assess risk in the existing credit portfolio and take early action on changing risk profiles.
- Develop proactive policies for managing increasing risk, such as loan restructuring programs.

### Customer Relationship Management (CRM)
- Retain low-risk customers with incentives.
- Manage customers showing signs of financial distress with solutions like loan restructuring or financial counseling.

### New Product Development
- Create new credit products for different risk segments.
- Offer credit insurance to high-risk customers to mitigate bank risk.

---

Thank you for your attention!

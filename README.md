# Customer-Churn-Prediction

## Overview
Customer churn is a major challenge in the banking industry, as losing existing customers leads to reduced revenue and increased customer acquisition costs. This project develops a machine learning model to predict whether a customer is likely to churn based on demographic, account, and transaction-related features. The prediction enables banks to proactively implement customer retention strategies.

---

## Business Problem
Banks need to identify customers who are at risk of leaving so that they can take preventive actions such as personalized offers, improved customer service, and loyalty programs. This project uses customer data to build a predictive model for customer churn.

---

## Objective
- Predict whether a customer will churn.
- Analyze the factors influencing customer churn.
- Compare multiple machine learning models.
- Select the best-performing model for deployment.
- Support data-driven customer retention strategies.

---

## Dataset Information

- **Dataset Size:** 10,127 customer records
- **Target Variable:** `Attrition_Flag`
  - Existing Customer
  - Attrited Customer

### Feature Categories
- Customer Demographics
- Banking Relationship Information
- Credit Card Details
- Transaction History
- Customer Engagement Metrics

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---


## Machine Learning Models

- Decision Tree
- Random Forest
- Gradient Boosting

### Final Model
**Gradient Boosting**

Gradient Boosting achieved the best balance between training and testing performance and demonstrated superior generalization on unseen data.

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---
---

## Conclusion

This project successfully developed a machine learning-based customer churn prediction system for the banking sector. By analyzing customer demographics, banking relationships, and transaction behavior, the models were able to identify customers who are likely to churn.

Among the evaluated models, **Gradient Boosting** achieved the best overall performance, demonstrating strong predictive accuracy and better generalization on unseen data. The model enables banks to proactively identify at-risk customers and implement targeted retention strategies, such as personalized offers, improved customer support, and loyalty programs.

Overall, this project demonstrates how machine learning can support data-driven decision-making, helping financial institutions reduce customer churn, improve customer satisfaction, and achieve sustainable business growth.


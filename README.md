# Customer Churn Prediction Using Artificial Neural Networks (ANN)

## Table of Contents
- [Project Overview](#project-overview)
- [Objective](#objective)
- [Dataset](#dataset)
- [Features](#features)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusion](#conclusion)
- [References](#references)

---

## Project Overview
Customer churn is a critical issue for subscription-based businesses, as losing customers directly impacts revenue. This project uses an **Artificial Neural Network (ANN)** to predict customer churn based on historical customer data, helping businesses identify at-risk customers and implement retention strategies.

---

## Objective
- Predict whether a customer will **churn** (Yes/No) using an ANN model.  
- Analyze the **importance of customer features** in churn prediction.  
- Provide actionable insights for businesses to **retain high-risk customers**.

---

## Dataset
The dataset contains customer information including demographics, account details, and service usage. Key columns include:  

- `CustomerID`: Unique identifier for each customer  
- `Gender`: Male or Female  
- `SeniorCitizen`: 0 or 1  
- `Tenure`: Number of months the customer has stayed  
- `MonthlyCharges`: Monthly subscription fee  
- `TotalCharges`: Total subscription fee  
- `Churn`: Target variable (Yes/No)  

*Source:* [Kaggle – Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)

---

## Features
- **Numerical Features:** `MonthlyCharges`, `TotalCharges`, `Tenure`  
- **Categorical Features:** `Gender`, `Partner`, `Dependents`, `PhoneService`, etc.  
- **Target Variable:** `Churn` (1 = Yes, 0 = No)  

---

## Methodology
1. **Data Preprocessing**  
   - Handle missing values  
   - Encode categorical variables  
   - Normalize numerical features  

2. **Model Development**  
   - Build an **Artificial Neural Network** with input, hidden, and output layers  
   - Use activation functions suitable for binary classification  

3. **Evaluation**  
   - Split dataset into training and testing sets  
   - Evaluate the model using accuracy, confusion matrix, and ROC-AUC  
   - Visualize feature distributions and model performance  

---

## Results
- The ANN model predicts customer churn with **high accuracy**.  
- Customers with **high monthly charges** and **short tenure** are more likely to churn.  
- Confusion matrix and evaluation metrics demonstrate the model’s effectiveness in identifying at-risk customers.  

---

## Conclusion
The project successfully demonstrates how an ANN can predict customer churn using historical data. Businesses can leverage this model to:  
- Retain high-risk customers  
- Optimize marketing and retention strategies  
- Increase overall customer satisfaction and revenue  

---

## References
- [Kaggle – Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)  
- Géron, A. (2019). *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow*  
- Chollet, F. (2017). *Deep Learning with Python*  

**Author:** Zara Irfan

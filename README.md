# telco-churn-prediction-DATA-SCIENCE
# Telco Customer Churn Prediction

## Overview
Customer churn is a major challenge in the telecommunications industry, where retaining existing customers is more cost-effective than acquiring new ones. This project builds a machine learning model to predict whether a customer is likely to churn based on historical data.

The system processes raw customer data, analyzes patterns, and generates a list of high-risk customers to support proactive business decisions.

---

##  Objectives
The objective of this project is to develop an end-to-end churn prediction pipeline. This includes data preprocessing, exploratory data analysis, model building, evaluation, and generating actionable outputs.

---

##  Dataset
The dataset used is the Telco Customer Churn dataset, which contains information about:
- Customer demographics  
- Account details  
- Services subscribed  
- Billing information  

The target variable indicates whether a customer has churned or not.

---

##  Methodology

### Data Preprocessing
The dataset was cleaned by handling missing values and converting data types. Categorical variables were encoded into numerical format, and feature scaling was applied to normalize numerical features.

### Exploratory Data Analysis
EDA was performed to identify patterns in the data. Key insights include:
- Customers with month-to-month contracts are more likely to churn  
- New customers have higher churn rates  
- Fiber optic users show higher churn behavior  

### Model Development
Two machine learning models were implemented:
- Logistic Regression  
- Random Forest  

### Model Evaluation
The models were evaluated using accuracy, ROC-AUC score, and recall. Special focus was given to identifying actual churners.

---

##  Results
The Logistic Regression model performed better overall and was more effective in detecting customers who are likely to churn.

  ROC Curve and Confusion Matrix images here
<img width="846" height="624" alt="image" src="https://github.com/user-attachments/assets/e3cd606b-1dfb-43c8-b66e-0776e3f0f83d" />
<img width="1447" height="590" alt="image" src="https://github.com/user-attachments/assets/323c49ed-c641-45a9-adfd-3cfef1a718ce" />
<img width="1447" height="590" alt="image" src="https://github.com/user-attachments/assets/9e7b3f6e-9b05-4a98-a85b-bcbb789f59ca" />



---

##  Output
The final output is a file named:

`at_risk_customers.csv`

This file includes:
- Risk Score (probability of churn)  
- Prediction (Churn/Stay)  

---

##  Business Impact
This project helps businesses identify high-risk customers and take proactive actions such as offering discounts, improving services, or providing personalized support. This leads to improved customer retention and increased revenue.

---

## Future Improvements
Future work may include hyperparameter tuning, advanced models like XGBoost, and integration with real-time systems. A dashboard can also be developed for better visualization.

---

##  Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/telco-churn-prediction.git
cd telco-churn-prediction
pip install -r requirements.txt

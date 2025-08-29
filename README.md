 Customer Churn Prediction (Telco Dataset)

📌 Overview
This project predicts Customer Churn using the Telco Customer Churn Dataset.  
Churn occurs when customers stop using a company’s service. By predicting churn, companies can take action to improve retention.  

The dataset contains demographic, account, and service-related information for 7,043 customers.  
We perform **exploratory data analysis (EDA)**, preprocess the data, and build a **Logistic Regression Model** to predict churn.

-⚙️ Features
- Data Cleaning & Preprocessing
  - Handled missing values
  - Converted categorical variables using One-Hot Encoding
  - Converted `TotalCharges` column to numeric  
- Exploratory Data Analysis (EDA):
  - Distribution of churned vs non-churned customers
  - Distribution of monthly charges by churn status
  - Contract type vs churn visualization
- Model Training:
  - Used Logistic Regression to classify churn (`Yes` or `No`)
  - Achieved = 81% accuracy
- Evaluation:
  - Accuracy score
  - Predicted churn labels

 📂 Dataset
- File: `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- Rows: 7043  
- Columns: 21  
- Target Variable: `Churn` (`Yes` = customer left, `No` = customer stayed)

Sample Columns:
- `gender`
- `SeniorCitizen`
- `Partner`
- `Dependents`
- `tenure`
- `PhoneService`
- `InternetService`
- `Contract`
- `MonthlyCharges`
- `TotalCharges`
- `Churn`

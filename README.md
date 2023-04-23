#Predicting Customer Churn - Classification Project
###Project Overview

The objective of this project is to predict customer churn for a telecommunication company using classification models. Churn prediction is an important problem for companies that rely on subscription-based revenue models, as it can help identify customers who are at risk of leaving the service and allow the company to take proactive measures to retain them.

In this project, we will analyze a dataset of customer information and service usage patterns to build a predictive model that can identify customers who are likely to churn.

##Dataset
The dataset used for this project is provided by the telecommunication company and contains information about customers, their account information, and their usage patterns. It contains the following columns:

customerID: Unique identifier for the customer

gender: Customer gender (male or female)

SeniorCitizen: Indicates if the customer is a senior citizen (1) or not (0)

Partner: Indicates if the customer has a partner (Yes or No)

Dependents: Indicates if the customer has dependents (Yes or No)

tenure: Number of months the customer has been with the company

PhoneService: Indicates if the customer has a phone service (Yes or No)

MultipleLines: Indicates if the customer has multiple lines (Yes, No, or No phone service)

InternetService: Indicates the type of internet service the customer has (DSL, Fiber optic, or No)

OnlineSecurity: Indicates if the customer has online security (Yes, No, or No internet service)

OnlineBackup: Indicates if the customer has online backup (Yes, No, or No internet service)

DeviceProtection: Indicates if the customer has device protection (Yes, No, or No internet service)

TechSupport: Indicates if the customer has tech support (Yes, No, or No internet service)

StreamingTV: Indicates if the customer has streaming TV (Yes, No, or No internet service)

StreamingMovies: Indicates if the customer has streaming movies (Yes, No, or No internet service)

Contract: Indicates the type of contract the customer has (Month-to-month, One year, or Two year)

PaperlessBilling: Indicates if the customer has paperless billing (Yes or No)

PaymentMethod: Indicates the payment method (Electronic check, Mailed check, Bank transfer (automatic), or Credit card (automatic))

MonthlyCharges: The amount charged to the customer monthly

TotalCharges: The total amount charged to the customer

The target variable for this project is the "Churn" column, which indicates if the customer has churned (Yes) or not (No).

##Tools Used
The following tools were used in this project:

Python 3.7.10
pandas 1.2.4
NumPy 1.20.3
Scikit-learn 0.24.2
Matplotlib 3.4.2
Seaborn 0.11.1

##Methodology
The project was divided into the following steps:

Data Preparation: The dataset was loaded and preprocessed, including handling missing values, encoding categorical variables, and scaling numerical variables.
Exploratory Data Analysis (EDA): The dataset was explored using descriptive statistics, visualizations, and correlation analysis.
Feature Selection: The most important features for predicting churn were identified using feature selection techniques.
Model Training: Classification models, including Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, and Support Vector Machines, were trained using the selected features and evaluated using cross-validation.
Model Tuning: The best performing models were further tuned using hyperparameter optimization techniques.
Model Evaluation: The final models were evaluated on

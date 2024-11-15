   **Bank Customer Churn Analysis Project**
  
**Project Overview**

The Bank Customer Churn Analysis project focuses on understanding and predicting customer churn in a banking context. Churn refers to customers leaving the bank, and reducing churn is critical for maintaining profitability and growth. This project utilizes machine learning techniques to analyze customer data, identify key drivers of churn, and develop predictive models.

**Objectives**

•	Perform exploratory data analysis (EDA) to understand the data structure and distributions.
•	Identify features most correlated with customer churn.
•	Build and evaluate machine learning models to predict customer churn.
•	Provide actionable insights to reduce churn rates.

**Features**

Data Preprocessing: Handling missing values, encoding categorical variables, and scaling numeric features.
Exploratory Data Analysis (EDA): Visualizing data distributions, relationships, and churn trends.
Feature Engineering: Selecting and transforming features to optimize model performance.
Machine Learning Models: Training and evaluating classifiers such as logistic regression, decision trees, and ensemble methods.
Model Evaluation: Using metrics like accuracy, precision, recall, F1-score, and AUC-ROC to assess model performance.
**File Structure**
Bank Customer Churn Analysis Project.ipynb: Contains the full workflow for data loading, preprocessing, modeling, and evaluation.
Churn_Modelling.csv: "Credit Card Transactions Fraud Detection Dataset" from Kaggle 

**Prerequisites**

Tools and Libraries
•	Python 3.x
Jupyter Notebook
•	pandas for data manipulation
•	numpy for numerical computations
•	matplotlib and seaborn for visualization
•	scikit-learn for machine learning models and evaluation

**Dataset**

The dataset used in this project is the "Credit Card Transactions Fraud Detection Dataset" from Kaggle:
[https://www.kaggle.com/datasets/kartik2112/fraud-detection]
The dataset includes:
● trans_date_trans_time: Transaction datetime
● cc_num: Credit card number
● merchant: Merchant name
● category: Transaction category
● amt: Transaction amount
● first: Customer first name
● last: Customer last name
● gender: Customer gender
● street: Street address
● city: City
● state: State
● zip: ZIP code
● lat: Latitude
● long: Longitude
● city_pop: City population
● job: Customer occupation
● dob: Date of birth
● trans_num: Transaction number
● unix_time: Unix timestamp
● merch_lat: Merchant latitude
● merch_long: Merchant longitude
● is_fraud: Fraud flag (0 or 1)
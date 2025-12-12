# 📊 Customer Churn Analysis using Python
# 🔍 Predicting customer churn using data analysis & machine learning

# 📝 Project Overview

This project analyzes telecom customer data to identify key factors that influence churn and builds predictive models to classify whether a customer is likely to leave. The goal is to help businesses develop data-driven retention strategies.

# 🎯 Objectives

Analyze demographic and service-related factors affecting churn

Identify high-risk customer segments

Build machine learning models to predict churn

Derive actionable business recommendations

# 📂 Dataset

~7,000 customer records

# Key features include:

CustomerID, Gender, SeniorCitizen, Tenure

MonthlyCharges, TotalCharges

InternetService, Contract, PaymentMethod

Target variable: Churn (Yes/No)

# 🛠️ Tech Stack

Languages: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
Techniques: EDA, Data Cleaning, Feature Engineering, Classification Models

# 🔧 Workflow

Data Cleaning

Handled missing values and inconsistent numerical entries

Converted data types and created derived features

Exploratory Data Analysis (EDA)

Churn distribution across contract types, tenure, payment methods

Visualized customer spending patterns

Feature Engineering

Encoded categorical variables

Scaled numerical features

Modeling

Logistic Regression

Random Forest Classifier

Evaluation

Accuracy: 80%+

Precision, Recall, F1-score

Confusion Matrix

# 📈 Key Insights

Month-to-month contract customers churn the most

Senior citizens have higher churn probability

Higher monthly charges correlate with churn

Long-tenured customers tend to stay loyal

# 🤖 Model Performance
Model	Accuracy	Notes
Logistic Regression	~80%	Good baseline classifier
Random Forest	~82%	Better generalization, handles feature interactions
# 💡 Business Recommendations

Promote long-term contracts to high-risk groups

Target senior citizens with personalized offers

Introduce loyalty programs for high-paying customers

Monitor month-to-month customers proactively

# 📁 Project Structure
📦 Customer Churn Analysis
├── 📄 churn_analysis.ipynb
├── 📄 data.csv
├── 📄 README.md
└── 📄 models/

🚀 How to Run
# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook Customer_Churn_Analysis.ipynb

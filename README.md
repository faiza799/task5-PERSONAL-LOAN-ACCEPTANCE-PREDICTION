# task5-PERSONAL-LOAN-ACCEPTANCE-PREDICTION


📌 Internship

DevelopersHub Corporation
Data Science & Analytics Internship

# 🎯 Objective

The objective of this task is to build a machine learning classification model that predicts whether a bank customer is likely to accept a personal loan offer. The goal is to analyze customer demographics and behavior to identify key factors influencing loan acceptance.

# 📂 Dataset

The dataset used for this task is the Bank Marketing Dataset from the UCI Machine Learning Repository:

Bank Marketing Dataset

It contains customer information such as:

Age
Job
Marital status
Education
Account balance
Contact type
Previous campaign outcomes
Loan acceptance status (Target variable)

#🛠️ Tools & Libraries Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
# 📊 Project Workflow
1. Data Loading
Dataset loaded using Pandas (read_csv)
Initial structure explored using .head(), .shape, and .info()
2. Data Exploration (EDA)

The following visualizations were performed:

📌 Age Distribution

To understand the age distribution of customers.

📌 Job Distribution

To analyze customer occupations.

📌 Marital Status Distribution

To study customer demographics.

3. Data Preprocessing
All categorical variables were converted into numerical format using Label Encoding
Dataset was prepared for machine learning modeling
4. Feature Scaling
StandardScaler was applied to normalize feature values
This improved model performance and removed convergence issues
5. Model Training

A Logistic Regression model was used:

Training set: 80%
Testing set: 20%
Maximum iterations: 3000
6. Model Evaluation

The model was evaluated using:

Accuracy Score
Confusion Matrix
Classification Report
# 📈 Results
The model successfully predicts customer loan acceptance behavior.
Scaling improved model convergence and performance.
Logistic Regression provides a strong baseline for classification problems.
# 🔑 Key Insights
Customer age and job type influence loan acceptance.
Marital status also plays a role in decision-making.
Financial behavior patterns help predict loan acceptance likelihood.
Proper feature scaling improves model stability.
# 🚀 Conclusion

This task demonstrates how machine learning can be used to predict customer behavior in banking systems. Data preprocessing, encoding, and feature scaling were essential for building an accurate and stable model.

# Author

DevelopersHub Data Science Intern
Faiza Memon

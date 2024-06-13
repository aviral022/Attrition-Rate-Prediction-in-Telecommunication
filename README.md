
Introduction:
This project aims to predict customer attrition (churn) in the telecommunication industry using various machine learning techniques. Customer attrition is a significant issue in the telecom sector, and predicting it can help companies take proactive measures to retain customers.

Dataset:
The dataset used for this project contains various features related to customer demographics, account information, and usage patterns. It includes both categorical and numerical features.

attrition-rate-prediction/
├── data/
│   ├── raw/
│   ├── processed/
├── notebooks/
├── src/
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   ├── model_evaluation.py
│   └── utils.py
├── tests/
│   ├── test_data_preprocessing.py
│   ├── test_feature_engineering.py
│   ├── test_model_training.py
│   ├── test_model_evaluation.py
├── .gitignore
├── README.md
├── requirements.txt
└── main.py

Models and Techniques

The project employs several machine learning algorithms to predict customer churn, including:

Decision Trees,
Random Forest,
Gradient Boosting Machines,
Support Vector Machines,

Result:
The performance of each model is evaluated using metrics such as accuracy, precision, recall, and F1-score. The best-performing model is selected based on these metrics and further analyzed to understand the key factors influencing customer churn.

Highest achieved accuracy in 80-20 test-train split is 98.48%

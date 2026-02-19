# survivor_prediction_with_titanic_dataset
🚢 Titanic Survival Prediction (Machine Learning)

A beginner-friendly machine learning project using the Titanic dataset to predict whether a passenger survived the disaster.
This project covers the full ML pipeline: data preprocessing, feature engineering, model training, and evaluation using cross-validation.

📌 Project Goal

Predict the target:

Survived

1 = Survived

0 = Not Survived

📂 Dataset

This project uses the well-known Titanic dataset (Kaggle).
It contains passenger details such as:

Pclass (Passenger class)

Sex

Age

SibSp

Parch

Fare

Embarked (Port of embarkation: S, C, Q)

🛠️ Tools & Libraries

Python

Pandas

NumPy

Scikit-learn

Jupyter Notebook / Kaggle Notebook

🔄 Workflow
1️⃣ Data Cleaning

Removed unnecessary text columns:

Name

Ticket

Cabin

Handled missing values

Ensured dataset was ready for training

2️⃣ Feature Engineering

Converted categorical columns into numeric form:

Sex converted into:

male → 0

female → 1

Embarked converted using one-hot encoding:

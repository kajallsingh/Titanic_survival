
Titanic Survival Prediction using Machine Learning

📖 Project Overview
This project focuses on predicting Titanic passenger survival using historical passenger data. The goal is to build a machine learning model that can assist in understanding factors influencing survival and predicting outcomes for new passengers.

📊 Dataset
The dataset contains passenger information such as Pclass, Sex, Age, SibSp, Parch, Fare, Embarked, and survival status.
Target variable: Survived (0 = No, 1 = Yes).
Source: Kaggle Titanic Dataset.

⚙ Methodology
1. Data Preprocessing
Handled missing values in Age, Cabin, and Embarked
Encoded categorical variables (Sex, Embarked)
Feature scaling for numerical columns

2. Model Training
Logistic Regression

3. Evaluation Metrics
Accuracy
Confusion Matrix

📈 Results
Training Accuracy: 80%
Test Accuracy: 78.2%

Confusion matrix analysis was used to evaluate model performance.
📌 Logistic Regression achieved a solid baseline performance in predicting survival.


🚀 Tech Stack
Python (Pandas, NumPy, Matplotlib, Seaborn)
Scikit-learn

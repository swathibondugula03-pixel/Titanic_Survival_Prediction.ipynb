Titanic Survival Prediction – Machine Learning Project
Project Overview
This project builds a binary classification model to predict whether a passenger survived the Titanic disaster based on features such as age, gender, passenger class, fare, and embarkation details.

The objective is to demonstrate:
Data preprocessing
Feature engineering
Model training
Model evaluation
Interpretation of results

Machine Learning Approach
This project uses Logistic Regression, a supervised learning algorithm used for binary classification problems.
Logistic Regression estimates the probability of an event occurring using the sigmoid function.

Dataset Description
The dataset contains 891 passenger records with features such as:
Passenger Class (Pclass)
Sex
Age
Fare
Number of Siblings/Spouses aboard
Number of Parents/Children aboard
Port of Embarkation
Survival (Target Variable)
Target Variable:
  0 → Did Not Survive
  1 → Survived

Data Preprocessing Steps
Handled missing values:
Filled missing Age values using median
Removed unnecessary columns
Encoded categorical variables:
Converted text features (e.g., Sex, Embarked) into numerical format using one-hot encoding
Split data:
  80% Training data
  20% Testing data

Model Training
Algorithm Used: Logistic Regression
Library: Scikit-learn
Maximum iterations set to ensure convergence
The model was trained on the training dataset and evaluated on unseen test data.

Model Evaluation
Evaluation metrics used:
Accuracy Score
Confusion Matrix
Precision
Recall
F1-Score
Model achieved approximately:
  ~80% accuracy
This indicates that the model correctly predicts survival status for most passengers.

Titanic Survival Prediction
Project Overview

This project predicts whether a passenger survived the Titanic disaster using machine learning. The model is trained on passenger data such as age, gender, ticket class, and fare to classify survival outcomes.

The project demonstrates data preprocessing, feature selection, model training, and evaluation using Python and Scikit-learn.

Dataset

The dataset contains passenger details including:

PassengerId

Pclass (Passenger Class)

Name

Sex

Age

SibSp (Siblings/Spouses aboard)

Parch (Parents/Children aboard)

Ticket

Fare

Cabin

Embarked

Survived (Target Variable)

Target Variable:

Survived

0 = Did Not Survive

1 = Survived

Technologies Used

Python

Pandas

NumPy

Scikit-learn

Machine Learning Model

Random Forest Classifier was used to train the model and predict passenger survival.

Steps Performed

Import libraries

Load dataset

Handle missing values

Encode categorical variables

Split dataset into training and testing sets

Train Random Forest model

Predict survival on test data

Evaluate accuracy

Evaluation Metrics

Accuracy Score

Classification Report

Result

The trained model successfully predicts survival of passengers with good accuracy using the available features.

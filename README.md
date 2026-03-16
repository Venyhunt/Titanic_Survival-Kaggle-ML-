Titanic Survival Prediction (Kaggle ML Competetition)

This project builds a machine learning model to predict passenger survival on the Titanic dataset from Kaggle.
The goal is to explore feature engineering techniques and evaluate classical ML models.

Dataset

Dataset from Kaggle competition:

Titanic - Machine Learning from Disaster

Contains passenger information including:

Age

Sex

Ticket class

Fare

Family relationships

Feature Engineering

Engineered features used in the model:

Title extracted from passenger name
FamilySize
IsAlone
FarePerPerson
AgeGroup
Embarked encoding

These features improved model performance compared to baseline models.

Model

Model used:

RandomForestClassifier

Parameters:

n_estimators = 100
max_depth = 5
Validation

Model evaluated using train/validation split.

Validation Accuracy: ~0.81
Kaggle Score
Public leaderboard score: 0.787

Top ~14% of participants.

Feature Importance:
Sex and Fare were the most important predictors of survival.

How to Run
pip install -r requirements.txt
run notebook/titanic_solution.ipynb

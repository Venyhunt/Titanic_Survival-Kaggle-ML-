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

n_estimators = 300
max_depth = 7
min_samples_split = 5
Validation

Model evaluated using train/validation split.

Validation Accuracy: ~0.79
Kaggle Score
Public leaderboard score: 0.786

Top ~15% of participants.

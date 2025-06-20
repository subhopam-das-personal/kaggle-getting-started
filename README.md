# kaggle-getting-started

This repository contains Python notebooks for Kaggle "Getting Started" problems, including the Titanic - Machine Learning from Disaster competition.

## Project Description
The Titanic competition on Kaggle is a classic binary classification problem. The goal is to predict whether a passenger survived the Titanic shipwreck based on features such as age, sex, ticket class, and more. This project demonstrates a full data science workflow: data cleaning, feature engineering, model selection, evaluation, and prediction for submission.

**Competition link:** https://www.kaggle.com/competitions/titanic

## Files
- `Titanic-ML/Titanic_machine_learning.ipynb`: Main notebook for the Titanic competition solution.
- `Titanic-ML/data/train.csv`: Training data used for model development.
- `Titanic-ML/data/test.csv`: Test data for generating predictions.
- `Titanic-ML/titanic_predictions.csv`: Submission file with `PassengerId` and predicted `Survived` values.

## Approach & Findings
- Data preprocessing: handled missing values, encoded categorical variables, and selected top features.
- Models used: Random Forest, Gradient Boosting, and Voting Classifier.
- Model tuning: Performed GridSearchCV for hyperparameter optimization.
- Final predictions were made using the Random Forest model.

## Accuracy Results
- **Random Forest Classifier accuracy:** ~0.82 (on validation set)
- **Gradient Boosting Classifier accuracy:** ~0.80 (on validation set)
- **Voting Classifier accuracy:** ~0.82 (on validation set)

See the notebook for detailed code, analysis, and output files.

# 🚢 Titanic Survival Prediction | Machine Learning Classification Project

Machine learning project developed using the Titanic dataset from Kaggle.

## Project Overview

This project applies machine learning techniques to predict passenger survival in the Titanic disaster using the Kaggle dataset.

The workflow includes exploratory data analysis (EDA), data preprocessing, feature engineering, model training, and performance evaluation to identify the most effective classification approach.

The goal is to build a robust and interpretable predictive model while demonstrating key data science skills such as data cleaning, feature transformation, and model comparison.

## Project objective

To predict whether a passenger survived the Titanic disaster based on demographic, socio-economic, and travel-related features.

## Data Preprocessing

Key steps included:

- Handling missing values (Age, Cabin, Embarked)
- Imputing missing data using statistical strategies
- Converting categorical variables into numerical format
- One-Hot Encoding for categorical features

## Exploratory Data Analysis (EDA)

EDA revealed important patterns such as:

- Gender as a strong indicator of survival
- Higher survival rates among younger passengers
- Passengers with recorded cabin information showing different survival patterns

## Models Tested

Multiple machine learning models were trained and compared:

Logistic Regression (baseline and final model)
Decision Tree Classifier
Random Forest Classifier

## Final Model

The final model selected was Logistic Regression, due to its:

- Strong and stable performance
- High interpretability
- Better generalization compared to more complex models

## Evaluation
- Kaggle Submission Score (Accuracy): 0.76076

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Feature Engineering

The following features were created to improve model performance:

AgeGroup: Age categorized into meaningful bins
HasCabin: Binary feature indicating whether cabin information is available
Transformation of categorical variables into model-ready format

## Project Workflow

1. Data loading and exploration
2. Missing value handling
3. Feature engineering
4. Encoding categorical variables
5. Model training and evaluation
6. Kaggle submission

## Key Insights
- Gender was one of the most influential predictors of survival
- Socio-economic indicators (Pclass) strongly impacted survival probability
- Feature engineering improved model interpretability and performance
- Simpler models (Logistic Regression) performed competitively against more complex ones

## What this project demonstrates
- End-to-end machine learning pipeline
- Data cleaning and preprocessing skills
- Feature engineering techniques
- Model comparison and evaluation
- Ability to communicate results clearly

## Dataset

- Source: Kaggle Titanic Competition
- Link: https://www.kaggle.com/competitions/titanic
- Type: Binary classification problem

## Links
- Project Repository: https://github.com/Tatiane-Vieira/titanic-machine-learning-project
- LinkedIn: https://www.linkedin.com/in/tatiane-cvieira/

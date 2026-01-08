# CODSOFT
# Titanic Survival Prediction

## Description
This project predicts whether a passenger survived the Titanic disaster using machine learning. The model uses passenger information such as age, gender, ticket class, fare, and other features to make predictions. This notebook demonstrates an end-to-end machine learning workflow: data preprocessing, feature engineering, model training, evaluation, and insights.

## Dataset
The Titanic dataset contains information about individual passengers, including:
- PassengerId
- Pclass (Ticket class)
- Name
- Sex
- Age
- SibSp (Number of siblings/spouses aboard)
- Parch (Number of parents/children aboard)
- Ticket
- Fare
- Cabin
- Embarked
- Survived (Target variable)

 ## Methodology
1. Data Loading & Exploration (EDA)
2. Handling missing values (Age, Cabin, Embarked)
3. Encoding categorical variables (Sex, Embarked)
4. Feature selection (drop PassengerId, Name, Ticket, Cabin)
5. Train-test split (80% train, 20% test)
6. Logistic Regression model training
7. Model evaluation (Accuracy, Confusion Matrix, Classification Report)

## Algorithms Used
- Logistic Regression


## Results
- Accuracy: ~[75.4]%  
- Confusion Matrix:
        - Insights:
        - Female passengers had a higher survival rate.
        - Higher-class passengers had better chances of survival.
        - Age and fare influenced survival probabilities.

## Tools
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn


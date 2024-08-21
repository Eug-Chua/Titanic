# Titanic Survival Prediction

This repository contains a Jupyter Notebook dedicated to predicting the likelihood of survival on the infamous Titanic using machine learning classification techniques.

## Overview

The purpose of this project is to demonstrate the application of machine learning algorithms to a real-world dataset, showcasing the end-to-end process from data preprocessing to model evaluation. This notebook serves as a portfolio piece to exhibit my skills in data analysis, feature engineering, and model building.

## Data

The dataset used in this project is the well-known Titanic dataset, which is publicly available on Kaggle. It includes information on passengers such as age, gender, class, and more, along with their survival status.

- **Training Data:** 891 rows, with features like `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, `Embarked`.
- **Test Data:** 418 rows, similar features but without the survival outcome.


## Models and Evaluation
In this project, several machine learning models were tested, including:
- Logistic Regression
- Support Vector Machines
- Random Forest
- Gradient Boosting

The performance of these models was evaluated using metrics such as accuracy, precision, recall. Hyperparameter tuning was also performed to optimize model performance.

## Results
The base model achieved an accuracy of 77.0% on the test dataset, with a balanced precision and recall, indicating a robust prediction of survival.

Upon further tuning, the final model achieved an accuracy of 77.2%.

## Conclusion
This project illustrates the application of machine learning techniques to a classical dataset, providing insights into the factors influencing survival on the Titanic. The notebook demonstrates the complete workflow from data preprocessing to model evaluation and selection.

## Acknowledgements
The dataset is provided by Kaggle.

Inspiration and guidance were drawn from various sources including Kaggle discussions and other public machine learning resources.
## Overview of the Analysis

### Purpose: 
The analysis aims to build machine learning models for predicting loan status based on financial information provided in the dataset.


### Financial Information: 
The dataset includes the following features: loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status.


### Variable Information:
The loan status is the variable that is being predicted using this model. It is showing 18,759 numbers of healthy loans and 625 numbers of high-risk loans.


### Machine Learning Process:
Data Preprocessing: Present the dataset in a dataframe and clean the data if necessary.

Separating the data into labels and features: Create the labels set (y)  from the “loan status” column, and then create the features (X) DataFrame from the remaining columns. 

Splitting Data: Splitting the dataset into training and testing sets.

Creating a Logistic Regression Model: Using machine learning algorithms such as Logistic Regression to train models on the training data.

Evaluating Performance: Evaluating model performance using confusion matrix, accuracy, precision, recall, and F1-score.


### Method Used: 
Logistic Regression Model was used for predicting loan status based on the provided financial features.

<br />

## Results
Machine Learning Model - Logistic Regression
- Accuracy: 0.99
- Precision: 
    - Class 0 (healthy loans) - 1.00
    - Class 1 (high-risk loans) - 0.87
- Recall: 
    - Class 0 (healthy loans) - 1.00
    - Class 1 (high-risk loans) - 0.89
- F1-Score
    - Class 0 (healthy loans) - 1.00
    - Class 1 (high-risk loans) - 0.88

<br />

## Summary
The performance of Logistic Regression Model is excellent with the accuracy of 0.99, which means there is a high accuracy in prediction. The Precision and Recall scores are high, which represent 1.00 and 1.00 for healthy loans; 0.87 and 0.89 for high-risk loans respectively. Besides, the F1-score is high as well, with 1.00 for the healthy loans and 0.88 for high-risk loans. This model is particular well in identifying healthy loans, because it scores 1.00 in Precision, Recall and F1-Score. This model is recommended for predicting the loan status based on the overall high scores in every aspect. 


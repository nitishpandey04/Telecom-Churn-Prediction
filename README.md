# Telecom-Churn-Prediction
> Using historical customer data, we predict whether a particular customer will switch to another telecom provider or not.

## Table of Contents
* [General Info](#general-information)
* [Steps](#steps)
* [Model Building](#model-building)
* [Model Evaluation](#model-evaluation)
* [Conclusions](#conclusions)
* [Concepts Used](#concepts-used)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information

A telecom firm has collected data of all its customers. The main types of attributes are:

- Demographics (age, gender etc.)
- Services availed (internet packs purchased, special offers taken etc.)
- Expenses (amount of recharge done per month etc.)
 
Based on all this past information, we built a model which predicts whether a particular customer will 
churn or not, i.e. whether they will switch to a different service provider or not. So the variable of interest, i.e. 
the target variable here is ‘Churn’ which will tell us whether or not a particular customer has churned. 
It is a binary variable - 1 means that the customer has churned and 0 means the customer has not churned.

The datasets that are being used can be found [here](https://drive.google.com/drive/folders/1Fzml-oBTKHQ5qZlC_9J1bcRbSjB3eA6H?usp=sharing).

## Steps
1. Data Preparation
2. Data Cleaning
3. Exploratory Data Analysis
4. Random Forest Model for getting important variables
5. Logistic Regression model for interpretability
6. Business Recommendations
7. Decision Tree for interpretation
8. Principal Component Analysis for dimensionality reduction
9. Ensemble models for improved accuracy

## Model Evaluation
1. After the model was built which predicts the probability of churn, cutoff probability was decided using ROC Curve
2. Sensitivity - Specificity trade off was kept in mind while evaluating the model on different cutoffs until ideal cutoff was found.
3. The model was also evaluated on Precision and Recall for comparison purposes

## Concepts Used
- Exploratory Data Analysis
- Tree Based Models eg. Decision Trees
- Logistic Regression
- Cross Validation
- Prinipal Component Analysis
- Ensemble Techniques eg. Random Forest, XGBoost

## Technologies Used
- python
- numpy
- pandas
- matplotlib
- seaborn
- statsmodels
- sklearn
- xgboost

## Acknowledgements
This project was based on case study at IIITB

## Contact
Created by [nitishpandey04]<br>
email id- nitishpandey2117@gmail.com

# Loan Status Prediction
Documentation Date: 07/23/2023 <br>
Author: Jake Meyer

## Project Description
The focus for this assignment was selection of the best model and hyperparameter tuning. The data set used was from Kaggle (G Ranjith Kumar) which centered around loan approvals. The high-level steps for this assignment were data preparation, creating a pipeline with min-max scaler and a KNN Classifier, Logistic Regression Classifier, and a Random Forest Classifier. A grid search was used to determine the best parameters for the various models and check which model performed the best. 

## Table of Contents
<ol>
    <li>Supporting Files
    <li>Project Environment Overview
    <li>Data Preprocessing 
    <li>Model Training 
    <li>Model Evaluation
    <li>Report an Issue
    <li>Project References
</ol>

## Supporting Files
Dataset - [Loan Approval Data Set](https://www.kaggle.com/datasets/granjithkumar/loan-approval-data-set)

## Project Environment Overview
The project was completed in Jupyter Notebook (through Anaconda Navigator) via Python. All relevant libraries are called out in the Import Necessary Libraries section of the code.

## Data Preprocessing
Removed irrelevant columns not related to predicting loan status. Dropped all rows with missing data. Converted categorical features into dummy variables.

## Model Training
Split the data into train/test split, with Loan_Status as the target feature. Created a pipeline with a min-max scaler and KNN classifier. Created a search space with k-values between 1 to 10 and fit a grid search with 5-fold cross validation. Repeated the problem with Logistic Regression Classifier and a Random Forest Classifier.

## Model Evaluation
Used the 5-fold cross validation with accuracy as the evaluation metric.

## Report an Issue
In the event of an error or major concerns, please reach out to my email via meyerjake@gmail.com.

## Project References
No aditional references.

## Citation for this Project
Meyer, J. (2023, August 11). *Loan Status Prediction*. JakeLMeyer Portfolio Projects. https://github.com/JakeLMeyer/Portfolio_Projects/tree/main/Loan_Status_Prediction

## Return to Jake Meyer Github-Page
Github-Page - [Jake Meyer Github-Page](https://jakelmeyer.github.io)<br>
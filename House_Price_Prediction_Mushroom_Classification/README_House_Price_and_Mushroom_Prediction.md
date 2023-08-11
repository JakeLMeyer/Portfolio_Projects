# Project Title
Documentation Date: 07/12/2022 <br>
Author: Jake Meyer

## Project Description
There were two main objectives for this project. The idea was to show how a model performs when the most important features were included compared to all features. First, used Principal Component Analysis and Variance Threshold with a regression problem. House Prices data set from Kaggle was used for this portion of the project. The high-level steps for the regression problem were performing some data wrangling steps, identifying numerical vs. categorical features, preparing the data for training the model, application of feature selection methods of Principal Component Analysis and Feature Selection, and compared the model performance with R2 and RMSE evaluation metrics. <br>
The second main objective was to apply the feature reduction techniques with a classification problem. The data set used for this portion of the assignment was from Kaggle (UCI Machine Learning) and focused on mushroom classification. This portion of the assignment consisted of converting categorical features to dummy variables, preparing the data, fitting a Decision Tree classifier on the training set, reporting the accuracy of the model, showing a visualization of the model, and using a Chai-statistic selector to identify the five best features for the model and repeating the accuracy evaluation of the model with only those features.

## Table of Contents
<ol>
    <li>Supporting Files
    <li>Project Environment Overview
    <li>Data Preprocessing 
    <li>Model Training 
    <li>Model Evaluation
    <li>Report an Issue
    <li>Project References
    <li>Project Citation
    <li>Github-Page Return
</ol>

## Supporting Files
House Price labeled training dataset from this link (Kaggle): [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data?select=train.csv) <br>
Mushroom data from this link (UCI ML): [Mushroom Classification](https://www.kaggle.com/datasets/uciml/mushroom-classification).

## Project Environment Overview
The project was completed in Jupyter Notebook (through Anaconda Navigator) via Python. All relevant libraries are called out in the Import Necessary Libraries section of the code.

## Data Preprocessing
For House Price Prediction, the data preprocessing steps were drop the column(s) with >40% missing data, fill in any numeric feature data with median values for the respective feature, and fill in any missing categorical feature data with the most common value.<br>
For the Mushroom Classification, the data preprocessing step focused on converting the categorical features to dummy variables.

## Model Training
Both problems involved splitting the data into train/test splits. <br>
A Linear Regression Model was trained for the House Price problem. The same problem and data was then utilized with PCA and Variance Threshold applied to the data.  <br>
A Decision Tree Classifier was trained for the Mushroom Classification problem. The same problem and data was then utilized with χ2-statistic to choose the top 5 features for mushroom prediction. 

## Model Evaluation
For House Price Prediction, the R-Squared and RMSE value on the test data was utilized for the evaluation metric. <br>
For the Mushroom Classification, a confusion matrix and accuracy metric were utilized for model performance.

## Report an Issue
In the event of an error or major concerns, please reach out to my email via meyerjake@gmail.com.

## Project References
No additional project references.

## Citation for this Project
Meyer, J. (2023, August 11). *House Price Prediction and Mushroom Classification*. JakeLMeyer Portfolio Projects.https://github.com/JakeLMeyer/Portfolio_Projects/tree/main/House_Price_Prediction_Mushroom_Classification

## Return to Jake Meyer Github-Page
Github-Page - [Jake Meyer Github-Page](https://jakelmeyer.github.io)<br>
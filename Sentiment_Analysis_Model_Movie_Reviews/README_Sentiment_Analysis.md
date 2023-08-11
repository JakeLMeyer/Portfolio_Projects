# Sentiment Analysis of Movie Reviews
Documentation Date: 06/20/2022 <br>
Author: Jake Meyer

## Project Description
This project focused on building a Logistic Regression model for prediction of sentiment from movie reviews. The dataset used was from 50,000 records of the IMDB movie reviews. The high-level steps within the assignment were getting stemmed data to prepare for training/testing the model, fitting and applying tf-df vectorization to the training data, applying tf-df vectorization to the test data, training/testing a logistic regression model, determining metrics (accuracy, recall, precision, F1-score), plotting a confusion matrix, creating an ROC curve, and lastly repeating the training/test steps with a Multinomial Naïve Bayes model.

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
Dataset from Kaggle - [Bag of Words Meets Bags of Popcorn.](https://www.kaggle.com/c/word2vec-nlp-tutorial/data)

## Project Environment Overview
The project was completed in Jupyter Notebook (through Anaconda Navigator) via Python. All relevant libraries are called out in the Import Necessary Libraries section of the code.

## Data Preprocessing
Stem the data by converting all text to lowercase, removing punctuation, removing special characters, limit only alpha characters, remove stop words, and apply NLTK's PorterStemmer. 

## Model Training
Split the data into Train/Test subsets. Fit and apply a TF-IDF Vectorization to the training data. Apply the TF-IDF Vectorization to the Test data. Train and Test a Logistic Regression Model initially, then train and test a Multinomial Naive Bayes Classifier.

## Model Evaluation
Accuracy, recall, precision, F1-score, confusion matrix, and an ROC curve were used as evaluation metrics.

## Report an Issue
In the event of an error or major concerns, please reach out to my email via meyerjake@gmail.com.

## Project References
No additional references.

## Citation for this Project
Meyer, J. (2023, August 11). *Sentiment Analysis Model for Movie Reviews*. JakeLMeyer Portfolio Projects. https://github.com/JakeLMeyer/Portfolio_Projects/tree/main/Sentiment_Analysis_Model_Movie_Reviews

## Return to Jake Meyer Github-Page
Github-Page - [Jake Meyer Github-Page](https://jakelmeyer.github.io)<br>
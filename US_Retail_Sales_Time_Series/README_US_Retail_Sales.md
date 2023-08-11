# US Retail Sales Time Series Analysis
Documentation Date: 10/25/2022 <br>
Author: Jake Meyer

## Project Description
As the title outlines, this assignment focused on time series analysis with US Retail Sales Data. The data consisted of total monthly retail sales in the US from January 1992 until June 2021. There were several plots of the data with respect to time. The data was split based on time (last year-target, previous years training) to prepare for training/testing the model. A Holt-Winters Forecast with Exponential Smoothing model was chosen for predictive forecasting. Root Mean Squared Error (RMSE) was the metric chosen to evaluate the performance of the model. 

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
US Retail Sales CSV - [US Retail Sales Data](https://github.com/JakeLMeyer/Portfolio_Projects/blob/main/US_Retail_Sales_Time_Series/us_retail_sales.csv)

## Project Environment Overview
The project was completed in Jupyter Notebook (through Anaconda Navigator) via Python. All relevant libraries are called out in the Import Necessary Libraries section of the code.

## Data Preprocessing
Renamed the column headers for convenience. Only considered date and sales to revise the dataframe. Removed the missing records from the dataset.

## Model Training
Split the data into Train/Test subsets. Used the last year of data from July 2020-June 2021 as the test set. Trained and tested a Holt-Winters Forecast Model with Exponential Smoothing. 

## Model Evaluation
RMSE was utilized for the evaluation metric.

## Report an Issue
In the event of an error or major concerns, please reach out to my email via meyerjake@gmail.com.

## Project References
Enter References here.

## Citation for this Project
Meyer, J. (2023, August 11). *US Retail Sales Time Series Analysis*. JakeLMeyer Portfolio Projects. https://github.com/JakeLMeyer/Portfolio_Projects/tree/main/US_Retail_Sales_Time_Series

## Return to Jake Meyer Github-Page
Github-Page - [Jake Meyer Github-Page](https://jakelmeyer.github.io)<br>
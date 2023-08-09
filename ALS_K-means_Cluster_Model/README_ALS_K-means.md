# ALS K-Means Cluster Model
Documentation Date: 09/18/2022 <br>
Author: Jake Meyer

## Project Description
The focus for this project was to use ALS patient data from PRO_ACT to apply clustering methods. The high-level highlights consist of removing irrelevant data, applying a standard scalar to the data, plotting a cluster silhouette score, fit a K-means model to the data, fit a PCA transformation with two features of the scaled data, generate a scatterplot of the PCA transformed data, and overview a summary of the results.

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
Link to PRO-ACT Dataset: <br>
[Dataset als_Data.csv Source](https://ncri1.partners.org/ProACT/Document/DisplayLatest/2)

## Project Environment Overview
The project was completed in Jupyter Notebook (through Anaconda Navigator) via Python. All relevant libraries are called out in the Import Necessary Libraries section of the code.

## Data Preprocessing
No missing values in the data set initally. Features irrelevent to the target response of ALS condition were removed after correlation values were understood. A standard scalar was applied to the data. 

## Model Training
Plots of the cluster silhoute score versus number of clusters helped identify optimum value for k. A K-means model was fit to the data. Also, PCS tranformation was fit with two features to the scaled data.

## Model Evaluation
A plot of the PCA transformed data was generated to understand the clustering groups.

## Report an Issue
In the event of an error or major concerns, please reach out to my email via meyerjake@gmail.com.

## Project References
No additional references to cite.

## Citation for this Project
Meyer, J. (2023, August 9). *ALS K-Means Cluster Model*. JakeLMeyer Portfolio Projects. https://github.com/JakeLMeyer/Portfolio_Projects/tree/main/ALS_K-means_Cluster_Model 

## Return to Jake Meyer Github-Page
Github-Page - [Jake Meyer Github-Page](https://jakelmeyer.github.io)<br>
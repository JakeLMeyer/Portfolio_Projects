# World Happiness Models
Documentation Date: 07/22/2023 <br>
Author: Jake Meyer

## Project Description
Since 2012, the Sustainable Development Solutions Network has been publishing the World Happiness Report every year around March 20 in recognition of the International Day of Happiness. The World Happiness Report, “reflects a worldwide demand for more attention to happiness and well-being criteria for government policy” (2023). A thorough understanding of happiness around the globe is important for several reasons. First, the underlying factors for the happiest or unhappiest countries can be compared. Leaders within each country can review their current policies to understand areas to improve for a happier country. Second, major events such as wars or pandemics may have a significant impact on mental health. Leaders within countries with sharp declines in happiness for their citizens can act when needed. Third, many scientific studies indicate great benefits for individuals that tend to be happier compared to peers. Some of these benefits include improved heart health, handling stress more effectively, better immune systems, pain reduction, healthy lifestyles, and increased life expectancy (Mead, 2019). Although the focus for this project will consider happiness by country, it is also important to recognize the benefits of happiness on an individual level. The primary objective for this project is to create a regression model to predict the happiness level of countries. The research questions related to this analysis are shown below: <br>
<ul>
    <li> Which countries are the happiest?
    <li> Which countries are the unhappiest?
    <li> Which features are most significant for the happiest countries?
    <li> Which model provides the best accuracy for predicting a country’s happiness level?
<ul> <br>

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
The raw datasets were pulled from the World Happiness Report supporting files shown in the link below: <br>
[World Happiness Report Data](https://worldhappiness.report/archive/) <br>
There is a section for supporting data under each report that was pulled from 2015-2023 and consolidated into one single file.

## Project Environment Overview
The project was completed in Jupyter Notebook (through Anaconda Navigator) via Python. All relevant libraries are called out in the Import Necessary Libraries section of the code.

## Data Preprocessing
Merged the annual data together into one file. File is included in the repository for future analysis. Removed columns irrelevent to the world happiness score or repetitive for information. A lot of EDA was performed on the features and is outlined in the code.

## Model Training
Train/Test split was utilized on the data. Linear, Lasso, Decision Tree Regressors, and Random Forest Regressors were trained and tested.

## Model Evaluation
Evaluation metrics chosen for the models were R-Squared, MAE, RMSE, and MSE.

## Report an Issue
In the event of an error or major concerns, please reach out to my email via meyerjake@gmail.com.

## Project References
Ache, M. (2022). World Happiness Report up to 2022. About Dataset. Retrieved July 08, 2023, from https://www.kaggle.com/datasets/mathurinache/world-happiness-report?select=2022.csv 

Hunter, M. (2023, March 20). The world’s happiest countries for 2023. CNN Travel. Retrieved July 07, 2023, from https://www.cnn.com/travel/article/world-happiest-countries-2023-wellness/index.html 

Global Finance. (2022, April 27). The Happiest Countries in the World. Global Data. Retrieved July 07, 2023, from https://www.gfmag.com/global-data/non-economic-data/happiest-countries#:~:text=High%20GDP%20per%20capita%2C%20social%20support%20in%20times,time%20in%20their%20report%20on%20global%20life%20satisfaction. 

Mead, E. (2019, June 5). 6 Benefits of Happiness According to the Research. Happiness & SWB. Retrieved July 07. 2023, from https://positivepsychology.com/benefits-of-happiness/ 

Rozzelle, J. (2023, June 28). Global Unhappiness Levels in 2022 Match All-Time High, Report Finds. U.S. News World Report. Retrieved July 07, 2023, from https://www.cnn.com/travel/article/world-happiest-countries-2023-wellness/index.html 

Singh, A. (2023). World Happiness Report 2023. About Dataset. Retrieved July 08, 2023, from https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2023 

Sustainable Development Solutions Network. (2023). World Happiness Report. About Dataset. Retrieved July 07, 2023, from https://www.kaggle.com/datasets/unsdsn/world-happiness?select=2015.csv 

World Happiness Report and Gallup World Poll. (2023). World Happiness Report. About. Retrieved July 07, 2023, from https://worldhappiness.report/about/ 

## Citation for this Project
Meyer, J. (2023, August 11). *World Happiness Models*. JakeLMeyer Portfolio Projects. https://github.com/JakeLMeyer/Portfolio_Projects/tree/main/World_Happiness_Models

## Return to Jake Meyer Github-Page
Github-Page - [Jake Meyer Github-Page](https://jakelmeyer.github.io)<br>
# SC1015_A128_team7_MiniProject

## About

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on predicting the risk of contracting cardiovascular diseases based on health data using Data Science and Machine Learning.

## Contributors
A128 team 7
- Law Zhei En (<a href="https://github.com/zheien">@zheien</a>)
  -Data Cleaning & EDA
- Ong Yong Tze Marcus (<a href="https://github.com/MarcusongytDev">@Marcus</a>)
  -Machine Learning

## Background
Cardiovascular disease is the leading cause of death globally, taking an estimated 17.9 million lives in 2019, representing 32% of global deaths. 
With the high number of deaths globally and almost 45% of all heart attacks being silent, it is estimated that by 2030, 40% of US adults will have one or more forms of CVD. This is especially concerning as these attacks can be deadly. 

## Problem Definition 
To accurately predict the risk of people developing cardiovascular diseases for early prediction and intervention

## Objective
Our objective is to accurately predict the risk of a person contracting cardiovascular diseases based on parameters from their health and personal data.

## What's Included
1. Our cardiovascular disease dataset
2. Our presentation slides
3. Our Jupyter Notebook for our project
    - Data preparation and cleaning
    - Exploratory Data Analysis
    - Machine Learning
      1) Random Forest Model
      2) K-Nearest Neighbour Model

# Notebook Walkthrough:

## Data Preparation and Cleaning
Data shaping and processing for more accurate analysis and exploration. Dataset found is already cleaned, and there is no missing value; therefore, no need to fill missing values. We check for null columns and outliers, dropping those rows which had values that were totally out of range, by comparing to data range on various charts. 

## Exploratory Data Analysis
Data Visualisation - Using different plots and graphs to paint insightful pictures of the relationship between the response variable "cardio" and the numerical and categorical predictor variables

Univariate Analysis - used to find the pattern in the data to describe the variable. In univariate analysis, all variables are analysed independently. For each numeric variable, analyse it by looking at its mean, mode, median, quartiles and distribution. For each categorical variable, analyse it by looking at its number of categories, top, and cardinality.

Bivariate Analysis - used to find the relationship between variables, specifically to determine the existence and the degree of statistical association. For instance, the relationship between predictors and response is analysed. The purpose of this is to discover variables that have a significant statistical association with the response variable, so that they may be used in machine learning. For bivariate analysis between "cardio" and a categorical variable: the probability of having heart disease is analysed for different conditions in that categorical variable.

Multivariate Analysis - similar to Bivariate Analysis, Multivariate Analysis is also used to identify the statistical association between variables. The difference is to study multiple factors at once, and this is particularly effective in minimizing bias. For multivariate between "cardio" and 2 categorical variables: the probability of having heart disease is analysed for different combinations of conditions in those 2 variables.

We did EDA on all the features provided in the dataset seperately to analyse the relationship between each factor and cardiovascular disease

## Machine Learning
We subjected the dataset to a 80-20 train-test split.
Then we subjected the data to the Random Forest Model as well as the K-Nearest Neighbour Model.
1. Random Forest Classifier
    - Random Forest is a meta estimator that fits decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting.
2. K-Nearest Neighbour
    - K-Nearest Neigbour model is a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point.


## Conclusion
1. We recommend that health services can collect relevant patient health data and subject the data to machine learning models to better predict their cardiovascular diseases risk for early intervention. 
2. The most significant factors in predicting cardiovascular diseases were blood pressure, cholesterol level and BMI.

Using our refined and fine-tuned Random Forest classification model, hospitals and doctors can better predict whether a patient has or is going to have heart disease, increasing early detection

Data-Driven Insights

1. Increase early treatment - Patients who detected heart disease early can go for early treatment and increase chances of recovering
2. Lower medical costs - With early treatment, operations and surgeries are less likely to be needed for the patient to recover
3. Lower hospital demands - Early treatment prevents heart disease and allows patients to recover on their own, reducing the need to stay at hospitals
4. Increase survivability - Early detection leads to early intervention which saves lives


## Dataset Used
https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset?datasetId=107706&sortBy=voteCount

## Presentation Slides
https://docs.google.com/presentation/d/1qAmgKLhVzMqxEsPq6UNXdzAZwhsQ-KouzBmIRs0SIIk/edit?pli=1#slide=id.g219f8bde7d4_0_7922

## Reference List
https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html
https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html
https://www.medicalnewstoday.com/articles/death-statistics-by-cause-2020#causes-of-death-in-the-us
https://www.who.int/news-room/fact-sheets/detail/cardiovascular-diseases-(cvds)#:~:text=Cardiovascular%20diseases%20(CVDs)%20are%20the,%2D%20and%20middle%2Dincome%20countries
https://www.moh.gov.sg/resources-statistics/singapore-health-facts/principal-causes-of-death

Video Editing:
https://www.veed.io/login

Images:

https://www.healthline.com/health/high-blood-pressure-hypertension/blood-pressure-reading-explained
https://www.template.net/editable/95034/bmi-index-chart
https://www.frontiersin.org/files/Articles/284242/fnagi-09-00329-HTML/image_m/fnagi-09-00329-g001.jpg


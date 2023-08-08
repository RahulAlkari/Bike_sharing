# Project Name
Bike Sharing predictions using linear regression model

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
-A US bike-sharing provider BoomBikes wants to predict the demand of their bikes on a given day. 
For that they have provided a bike sharing dataset for last 2 years having feature variables like year, month ,
season, temp, humidity , windspeed, working day, holiday etc. 

Based on this data the count of bikes shared on a particular day needs to be predictaed so that company can manage the demand
of bikes more effifiently.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Based on data evaluated and EDA done we decided to implement Linear regression model to predict the deamnd of bikes.
Based on final model, below features are having higher weightage to get predicted demand of the shared bike as they are having the high coefficient values. :
1) Yr : high positive coef
2) Spring : High negative coef
3) Light rain or snow : High negative coef.

When model was applied on the test data we could predict the numbers with 74% accuracy.


## Libraries used Used
- import pandas as pd,
- import numpy as np,
- import seaborn as snsimport matplotlib.pyplot as plt ,
- from sklearn.model_selection import train_test_split,
from sklearn.feature_selection import RFE,
from sklearn.linear_model import LinearRegression,
from statsmodels.stats.outliers_influence import variance_inflation_factor,

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Bike Sharing assignment on Linear regression topic from Upgrad.


## Contact
Created by @RahulAlkari- feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

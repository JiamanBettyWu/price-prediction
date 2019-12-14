# Evaluating Model Accuracy and Time Efficiency for Price Predictions on Online Retail Markets
This project is a part of the final project for UC Davis [STA 141C - Big Data & High Performance Statistical Computing](https://statistics.ucdavis.edu/expanded-descriptions/141C) in Spring Quarter 2019. 

#### -- Project Status: [Completed]

### Data Source
This project is inspired by the Kaggle's [Mercari Price Suggestion Challenge](https://www.kaggle.com/c/mercari-price-suggestion-challenge). We also obtained data from this competition.

### Methods Used
* Principal Component Analysis
* Predictive Modeling

### Technologies
* Python

## Project Description
In this project, we want to use machine learning models to evaluate a given item’s conditions and features in order to make a price suggestion for sellers on an online second-hand shopping market. We compared prediction accuracy and time efficiency for different models, including linear regression model, Lasso, KNN, and random forest. We were able to achieve an error rate (measured by MSE) at 0.6072. Through the project, we also explored variables that are important in predicting prices.

Through comparing different models, we found that models rank from linear regression, Lass, KNN, and Random Forest in terms of time efficiency, with linear regression performed under one second, and Random Forest ran for 17 hours. And models rank from Lasso, linear regression, KNN, and Random Forest from the least accurate to the most accurate. Although Random Forest has the highest accuracy, it takes an excruciating amount of time to run. Considering the time and accuracy trade-off, KNN is the most cost-effective method for this dataset.


#### Project Member
[Tian Yue](https://github.com/lumapaty)@lumapaty


For more details about the project, please refer to the [report](https://github.com/JiamanBettyWu/price-prediction/blob/master/price_prediction.pdf) and [code](https://github.com/JiamanBettyWu/price-prediction/blob/master/project.py).




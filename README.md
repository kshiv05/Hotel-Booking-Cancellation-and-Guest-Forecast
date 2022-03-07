# Hotel Booking Cancellation and Guest Forecast

## Introduction
The hospitality industry often fails to better analyze their bookings, cancellations, etc. as the industry is quite volatile. A lot of dynamic factors impact their business continuity. The inspiration for this project came in as we often find ourselves intrigued by the below questions:

  •	Grounds on which a hotel is likely to receive a cancellation.
  
  •	What would be the expected footfall of the customers in future?

## Purpose
The purpose of this project is to perform data cleaning, wrangling, preprocessing, EDA, data visualizations and to develop hotel booking cancellation machine learning models. Guest forecasting using time series forecasting is also being done.

## Data Source
The dataset has been sourced from the article Hotel Booking Demand Datasets, written by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019. It contains over 100k booking information records having 32 features.

## Conclusion
Analyzed the data and developed hotel booking cancellation models using Logistic Regression and Random Forest algorithms with about 77% and 82% accuracy respectively. Hyperparameter tuning was performed on Random Forest Algorithm with these parameters: 'bootstrap': True, 'max_depth': 50, 'max_features': 3, 'min_samples_leaf': 3,  'min_samples_split': 8, 'n_estimators': 250 which increased the accuracy by 1.29%.
 
 Time series forecasting was also apploed to predict footfall of guests in future.

## Credit
Source: Hotel Booking Demand Datasets, written by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019

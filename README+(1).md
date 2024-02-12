# Project Name
> Upgrad EPGP AI ML Bike Sharing case study from Pushpendra Hirwani

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes. You will need to submit a Jupyter notebook for the same. 
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
- The dataset in use is day.csv

## Conclusions
- People seem to take lesser bike rentals in spring season
- There seems to have been significant rise in total rentals from 2018 to 2019
- People dont seem to prefer to take rentals on holidays when compared with non-holidays
- Clear and misty seems to have similar number of total rentals but there is a significant decrease in total rentals if it's a Light snowy day or a day with heavy rains
- There is high correlation between cnt and temp feature
- **Without RFE, following features were found to be significant and useful for model building, 
        'yr', 'workingday', 'temp', 'hum', 'windspeed',
       'weekday_monday', 'weekday_saturday', 'weekday_tuesday',
       'season_spring', 'season_summer', 'season_winter', 'weathersit_misty',
       'weathersit_snowy', 'mnth_January', 'mnth_March', 'mnth_May',
       'mnth_September'**
 **The R^2 value using this method is 0.8175783496843466**
- **Using RFE, following features were found to be significant and useful for model building, 
       'yr', 'workingday', 'temp', 'hum', 'windspeed',
       'weekday_saturday', 'weekday_sunday', 'season_spring',
       'weathersit_misty', 'weathersit_snowy', 'mnth_July'
 The R^2 value using RFE method is 0.8037672953255921**
- Both approach showed uniform distribution for error terms

## Technologies Used
- Visual studio Code
- numpy, pandas, seaborn, matplotlib, statsmodel, scikit
- Anaconda 3
- Python 3.11.4

## Acknowledgements
Give credit here.
- This project was inspired by learn.upgrad.com


## Contact
Created by [@pozoxoxo] - feel free to contact me!

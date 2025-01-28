# Bharti-Linear-Regression-Assignment
# Predicting Demand for Shared Bikes Using Multiple Linear Regression: A Business Strategy for Post-Pandemic Recovery

## Overview

This project involves developing a multiple linear regression model to predict the demand for shared bikes, based on various factors affecting bike-sharing systems. 
The dataset contains daily bike demand information, along with independent variables such as weather conditions, time of year, and other relevant features.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- What is the background of your project? 
This project focuses on predicting the demand for shared bikes using a multiple linear regression model. 

With the ongoing recovery from the COVID-19 pandemic, the bike-sharing service BoomBikes seeks to optimize its operations by understanding what drives bike rentals across various factors, such as weather conditions, time of year, and public holidays. By leveraging data, BoomBikes aims to anticipate future demand patterns and plan effectively.

- What is the business problem that your project is trying to solve?
BoomBikes has faced significant revenue losses due to the pandemic, resulting in reduced demand for bike rentals. 

As the situation improves, the company wants to predict bike rental demand to better align its resources and strategy. 

This project aims to identify which factors most influence demand, allowing BoomBikes to prepare for future spikes and optimize service availability, pricing, and marketing strategies.

- What is the dataset that is being used?
The dataset used in this project includes daily bike rental data, capturing the demand (number of bikes rented) along with various features like:

Weather conditions (e.g., temperature, humidity, windspeed)

Time-related features (e.g., season, month, weekday, working day)

Special conditions (e.g., holidays)

## Conclusions
Key Predictors: Temperature, season, and weather conditions (humidity, windspeed) are strong predictors of bike demand.

Model Performance: The model's R-squared value of 0.84 indicates a strong fit, suggesting reliable demand prediction.

Seasonality & Weather: Warmer months and mild weather lead to higher demand, guiding fleet and marketing strategies.

Actionable Insights: BoomBikes can adjust bike availability and resources based on demand patterns for optimal service.

Next Steps: Future improvements could include incorporating more detailed data and exploring advanced models for better predictions.

## Technologies Used

Numpy version: 1.26.4

Pandas version: 2.2.2

Seaborn version: 0.13.2

Scikit-learn version: 1.4.2

Statsmodels version: 0.14.2

## Acknowledgements
This project was inspired by BoomBikes.

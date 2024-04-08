# Boombikes Multiple Linear Regression
> Problem Statement
    Boombikes is a bike sharing company in the US that offers shared bikes to people on rent/free.
    BoomBikes aspires to understand the demand for shared bikes among the people and identify what factors it depends upon.
    A consulting company has gathered a large dataset on daily bike demands across the American market based on some factors.
    The company wants to know: 
    -- Which variables are significant in predicting the demand for shared bikes. 
    -- How well those variables describe the bike demands

> Business Goal
    Build a model to predict the demand for shared bikes with the available independent variables
    The model will be a good way for management to formulate/adapt business strategy to meet the demand levels and meet the customer's expectations and understand the demand dynamics of a new market


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Background: A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
- Problem Statement: A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
- Action Plan: They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
    Which variables are significant in predicting the demand for shared bikes.
    How well those variables describe the bike demands
- Business Goal: It is required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
- Dataset: The dataset provided indicates the count of bikes rentals by users on a daily basis for the year 2018 and 2019, and the data points also have independent variables indicating factors such as the weekday, month, weather situation, season etc. A multiple linear regression model is to be fit on this data to identify the factors that influence the count of rentals.


## Conclusions
- Based on the final model the top 3 features contributing significantly towards explaining the demand of the shared bikes are:
    a.	temp: temperature in Celsius - with a coefficient of 0.5499
    b.	weathersit - cloudy - with a coefficient of -0.2871
    c.	yr : year (0: 2018, 1:2019) - with a coefficient of 0.2331



## Technologies Used
- pandas
- matplotlib
- seaborn
- sklearn
- statsmodels


## Acknowledgements
Give credit here.
- https://www.statlect.com/glossary/variance-inflation-factor
- https://www.sigmamagic.com/blogs/what-is-variance-inflation-factor/#:~:text=If%20all%20the%20independent%20variables,a%20correlation%20between%20the%20variables.
- https://www.sfu.ca/~mjbrydon/tutorials/BAinPy/09_regression.html


## Contact
Created by [@amulay11] - feel free to contact me!
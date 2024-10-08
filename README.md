# Bike Sharing Assignment
Objective of this assignment is to build a linear regression model for predicting top features responsible for the demand of rental bikes.

## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

## Business Goal
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Conclusions

The top 3 features contributing significantly to explaining the demand of the shared bikes are
1. season,
2. weather and 
3. temperature or year as well.

Below are the R-squared values obtained for Train and test datasets.

1. Train R-squared=0.8311443094714427
2. Test R-squared=0.8099137099809726
3. Train Adj-R-squared=0.8277604278977241
4. Test Adj-R-squared= 0.7819009935571158

## Technologies Used
Python, numpy, pandas, matplotlib, seaborn, sklearn, statsmodels,


## Contact
Created by [@bhushanpande01] - feel free to contact me!
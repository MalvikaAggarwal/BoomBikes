# Project Name - Lending Club Case Study
> This project utilizes the data from US bike-sharing provider BoomBikes and Linear regression model is applied to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

### Domain Background
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

### Business Problem
To understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demands

### Dataset Information
The dataset day.csv contains the complete data for all rental counts for each day between 2018 & 2019 with various factors on each day.
The Data dictionary describes the meaning of all the column variables.
The 'count' variable indicates the total number of bike rentals, including both casual and registered.

## Conclusions

After Model building with Linear Regression - 

R2 score on the train set is 0.8355513232579529
R2 score on the test set is 0.8057616301094371

Liner Equation - 

cnt = 0.2339×yr + 0.4917×temp - 0.1497×windspeed -0.0682×spring + 0.00479×summer + 0.0818×winter - 0.0483×Jul + 0.0723×Sep - 0.0450×Tue - 0.0802×Cloudy -0.2847×Raining + 0.2034

Mean squared error of the train set is 0.008266171610223671
Mean squared error of the test set is 0.009287367709021672

#### Recommendations to Company

1. Highly dependent on temperature.
2. More rentals seem to be demanded on the winters as compared to the summer and spring.
3. We had observed that the September has higher use of rentals.
4. While when its cloudy then also people seem to rent more bikes.

## Technologies Used

-Pandas - version 2.0.3
-NumPy - version 1.24.3
-Seaborn - version 0.12.2
-MatplotLib - version 3.4.3
-Python - version 3.11.5 
-Jupyter Notebook- version 6.5.4

## Acknowledgements
This project was inspired by UpGrad IITB Programme as an linear regression assignment for the Machine Learning and Artificial Intelligence PG.


## Contact
Created by 
    - Malvika Singhal
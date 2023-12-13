# BoomBikes Linear Regression Case Study
> Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.
The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment..


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information

- Background : A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

- Business Problem: You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

- Approach: To create a linear model that quantitatively relates which variables are significant in predicting the demand for shared bikes e.g. season, month of the year, temperature, etc.
To know how well those variables describe the bike demands.

- Dataset used: Data dictionary and day data s issued through the time period 2018 t0 2019


## Conclusions
- Since the Rsquare and Adjusted Rsquare value of Backward method for MLP is better than RFE selection method so we will go with Backward method model

Final Prediction:
We can see that the equation of our best fitted line is:
demand = 0.2908+0.0612*workingday+0.3058*temp-0.0573*windspeed-0.1646*spring+0.0571*winter+0.2366*2019-0.0830*Dec-0.1094*Jul-0.0228*Jan
-0.0567*Nov+0.0286*Sep+0.0540*Mon-0.0118*Wed-0.3064*light_snow-0.1122*mist

Overall we have a decent model, but we also acknowledge that we could do better.

## Technologies Used
- library - pandas
- library - matplotlib
- library - seaborn


## Acknowledgements

- This project was inspired by live sessions and course material for Executive PG Programme in Machine Learning & AI - September 2023


## Contact
Created by @nishtha0807  - feel free to contact me!



Data Sourcing and importing required libraries for EDA



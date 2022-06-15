Bike Sharing Assignment
> To build a multiple linear regression model for the prediction of demand for shared bikes


## Table of Contents
* Problem Statement and Business Goal
* Technologies Used 
* Conclusions


<!-- You can include any other section that is pertinent to your problem -->

## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Python - pandas, matplotlib.pyplot, seaborn, sklearn(train_test_split, MinMaxScaler, LinearRegression, r2_score, RFE), statsmodels(variance_inflation_factor)

## Conclusions
1. Model has p-values within the accepatable range i.e., below 0.05.
2. Modle has VIF values within the acceptable range i.e., below 5.
3. Model satisfies all the assumptions for errors.
4. Model has the R- square value of 0.8211 for test data and 0.8367 for train data which tells model is well built. Because 82% of variance can be expalined by model.
5. Prob (F-statistic) which is eqaul to 0(1.95e-184) tells that overall variance is good.
6. Equation for total number of bike for rental with variable which influence this count can be represented as,
   cnt = 0.2989 + yr * 0.2325 + atemp * 0.4575 + hum * (-0.1612)+ windspeed * (-0.1627) + spring * (-0.0789 )+ winter * 0.0992 + Light Snow * (-0.2309) + Misty or Cloudy * (-0.0537) + 3 * 0.0618 + 4 * 0.0585 + 5 * 0.0938 + 6 * 0.0649 + 8 * 0.0628 + 9 * 0.1156

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->




## Contact
Created by Chaitramokhasi - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
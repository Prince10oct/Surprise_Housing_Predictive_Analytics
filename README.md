# Surprise_Housing_Rent_Predictive_Analytics_Investment

> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The company is looking at prospective properties to buy to enter the market. The task is to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
+ Which variables are significant in predicting the price of a house, and
+ How well those variables describe the price of a house.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
These are the final features that should be selected for predicting the price of house, hence the equation:
```
Log(Y) = C + 0.391359(x1) + 0.359583(x2) + 0.345160(x3) + 0.318507(x4) + 0.218726(x5) + 0.201420(x6) + 0.197847(x7) + 0.181017(x8) + 0.175515(x9) + 0.114792(x10) + Error term(RSS + alpha * (sum of absolute value of coefficients))
```
> Inference: Keep a check on these predictors affecting the price of the house.
> + The higher values of positive coeeficients suggest a high sale value.
> + The higher values of negative coeeficients suggest a decrease in sale value.
> + So, when the market value of the property is lower than the Predicted Sale Price, its the time to buy.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - library - version 1.0
- Scikit - Learnlibrary - version 2.0
- Pandas - library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was executed  by... Prince


## Contact
Created by [https://www.linkedin.com/in/prince-43314a14a/] - feel free to contact me!

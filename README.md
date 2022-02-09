# Advanced Regression Assignment - House Price Prediction


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

 

The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house 

**Business Goal:**<br>
We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
Through this exercise, we also want to determine the optimal value of lambda for ridge and lasso regression 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
 In simple words, below are the top features that are predicitve of price:

- Top quality material and finish of the house (scored 9,8,10)
- Higher living area above ground
- Neigborhoods of Crawford, NorthRidge, Somerset, StoneBrook,Northridge Heights
- Higher total square feet of basement area
- Exterior covering on house with Briackface has higher price
- 'Residential Low Density' zoning classification has higher price
- Type of dwelling that is '2-STORY 1945 & OLDER' has higher price
- Basement exposure that is 'Good' exposure to walkout or garden level walls

The optimal value of Alpha after gridsearch was alpha = 10

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Python libraries used:
- pandas
- numpy
- matplotlib
- seaborn
- skelearn
- warnings

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

This assignment is part of the Advanced Regression module in the Master's in ML & AI


## Contact
Created by [@udaykadavi] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project --># 
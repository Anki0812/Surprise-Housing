# Surprise Housing
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The company is looking at prospective properties to buy to enter the market. A model needs to be created to be used by management to understand how exactly the prices vary with the variables. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Below are top 10 significant variables in predicting house price:-
    - GrLivArea - Above grade (ground) living area square feet
    - OverallQual - Rates the overall material and finish of the house
    - GarageArea - Size of garage in square feet
    - MSSubClass - Identifies the type of dwelling involved in the sale.
    - Neighborhood - Physical locations within Ames city limits
    - YearRemodAdd - Remodel date (same as construction date if no remodeling or additions)
    - YearBuilt - Original construction date
    - FullBath - Full bathrooms above grade
    - BsmtFullBath - Basement full bathrooms
    - HalfBath - Half baths above grade

- Below are the optimum lambda values
    - Ridge - 100
    - Lasso - 0.01

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.21.3
- pandas - version 1.5.3
- matplotlib - version 3.4.3
- seaborn - version 0.12.2
- sklearn - version 1.2.1
- statsmodels - version 0.13.5

## Acknowledgements
- The training provided by IIIT Bangalore and Upgrad greatly contributed to the successful execution of this project.
- This project was based on [this tutorial](https://learn.upgrad.com/course/4617/segment/27465/225458/689472/3488520).


## Contact
Created by [@Anki0812] - feel free to contact.
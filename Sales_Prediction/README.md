# Big Mart Sales Prediction

## Problem statement:
Data scientists at bigmart have collected 2013 sales data for 1559 products across 10 stores 
in different cities. Also, certain attributes of each product and store have been defined. The aim is 
to build a predictive model and find out the sales of each product at a particular store.

## Dataset:
We have train and test dataset. Train dataset has both input and output variables.\
-> Number of observations in train set = 8523\
-> Number of observations in test set = 5681

## Approach to problem:
1) Pre-process the data.\
2) Define the architecture of model.\
   (since it is a regression problem, we have linear activation function in output layer.)\
3) Train model.\
4) Apply same pre-processing steps on test set.\
5) Generate predictions for the test set using trained model.

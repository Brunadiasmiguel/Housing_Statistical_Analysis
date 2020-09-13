# Housing_Statistical_Analysis

![IronHack Logo](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_d5c5793015fec3be28a63c4fa3dd4d55.png)

# Housing Stats

## Project Description

The goal of the project was to analyse the characteristics that can influence housing price. I wanted to limit the effect of the neighborhood as well and focus on the characteristics of the house itself.

## Questions & Hypotheses

For the project, the initial hypotheses was that the price depends on the neighborhood. The model is focus on a certain range of sales price, excluding the neighborhood outliers (other model for expensive and cheap sales price would be needed). The variables focus was on characteristics of the house, as square meters, number of rooms etc.



## Datasets

The dataset is about house price and it is called train.csv. It can be found on kaggle.


## Analysis

The analysis consisted mostly on checking potential correlations by plotting the variables and checking empirically with OLS if it fits the regression. To be considered into the regression, the variable/variables needed to have a significant R squared/adjusted R squared.


## Workflow

The workflow was basically:
- Clean dataset
- Chooose metrics to be evaluated
- Test regression with the metrics and adjust the metrics of the model looking at the adjust R squared mostly - taking into consideration that above 0.7 might be worth to keep the metric into the regression.


## Results

The results were positive, a regression was found.



## Problems

The model could be more accurate with more time spent on modelling/ searching for additional relevant variables


## Organisation

The repository is organised in:

1) stats jupyter file with the code
2) CSV file train.csv 
3) READ.me file with the project explanation and links

## Links

The links to repository is:

https://github.com/Brunadiasmiguel/Housing_Statistical_Analysis
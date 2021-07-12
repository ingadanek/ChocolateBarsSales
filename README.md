# Chocolate Sales project overview

Using Python and its packages in order to analyse Chocolate Bar Sales.

## Code and Resources Used
**Python Version:** `3.8.6`

**Packages:** `pandas, numpy, statsmodels, matplotlib, seaborn` 

**Pearson Correlation Github:** https://github.com/krishnaik06/Complete-Feature-Selection/blob/master/2-Feature%20Selection-%20Correlation.ipynb

## Data Cleaning
After loading the data, I needed to clean it up so that it was usable for our model. I made the following changes:
* checked for any null values and replaced them with 0s,
* removed outliers

## EDA
I created a pieplot to realize that the majority of chocolate bars' customers in our dataset prefer to buy offline. Over 80% of sales are offline sales with just nearly 20% of online sales. From a lineplot of Sales vs Week it is clear that the trend is increasing, meaning that we have more and more sales as time passes. I could also spot a trend - during the last week of each year, sales decrease to increase again at the beginning of new year.

## Verifying OLS assumptions
Before using Multiple Linear Regression we need to relax the OLS assumptions.

These include:
*No multicollinearity,
*Linearity,
*Normality of Residual,
*Homoscedasticity,
*No autocorrelation

## Statistically significant variables
In order to find out which variables contribute to Sales we need to have a closer look at the p-value. There is a hypothesis involved here. The values statistically significant are those with p-value less that 5% (0.05). 

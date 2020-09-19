# Predict-Sales-by-Advertising-Ads-Budget
---

## Project Overview

- Objective : To predict sales for given budget spend on TV, Radio and Newspaper in dollars. 
- Regression Problem
- Data cleaning and Data preprocessing
- Exploratory Data Analysis
- Multiple Linear Regression model training and prediction
- Statistical Analysis done from coefficients, p value, R² and Adj. R² value and F-statistic


---
## About Project

Machine Learning Regression model is developed to predict sales based on budgesting spends on various platforms for marketing adn advertising.The features are TV, Radio and Newspaper marketing spend in thousands of dollars.

---
## Code and Resources used

- Python version: 3.7.6
- Packages: Pandas, Numpy, Seaborn, Matplotlib, Scikit and Statsmodels.
- Resources used:

*Analytics Vidya
*towards data science
*Kaggle

---
## Web Scraping

Dataset URL: https://www.kaggle.com/ashydv/advertising-dataset/notebooks

### Data fields

Values in thousand dollars.

Features:

* TV: advertising dollars spent on TV for a single product in a given market (in thousands of dollars)
* Radio: advertising dollars spent on Radio
* Newspaper: advertising dollars spent on Newspaper

Target:

* Sales budget in thousands of dollars

---
## Data Cleaning

There is no missing values in data.

---
## EDA

I looked at the distributions of the data and the value counts for the various categorical variables. Below are a few highlights :

![](https://github.com/SidSolanki28/Predict-Sales-by-Advertising-Ads-Budget/blob/master/images/index.png)

---
## Model Building

### Multiple Linear Regression

Simple linear regression can easily be extended to include multiple features. This is called multiple linear regression:

y=β0+β1x1+…+βnxn

Each x represents a different feature, and each feature has its own coefficient. In this case:

y=β0+β1×TV+β2×Radio+β3×Newspaper

##### Advantages:
* widely used
* runs fast
* easy to use (not a lot of tuning required)
* highly interpretable
* basis for many other methods

---
## Model Prediction

                            OLS Regression Results                            
==============================================================================
Dep. Variable:                      y   R-squared:                       0.903
Model:                            OLS   Adj. R-squared:                  0.901
Method:                 Least Squares   F-statistic:                     605.4
Date:                Sat, 19 Sep 2020   Prob (F-statistic):           8.13e-99
Time:                        11:50:24   Log-Likelihood:                -383.34
No. Observations:                 200   AIC:                             774.7
Df Residuals:                     196   BIC:                             787.9
Df Model:                           3                                         
Covariance Type:            nonrobust                                         
==============================================================================
                 coef    std err          t      P>|t|      [0.025      0.975]
------------------------------------------------------------------------------
const          4.6251      0.308     15.041      0.000       4.019       5.232
x1             0.0544      0.001     39.592      0.000       0.052       0.057
x2             0.1070      0.008     12.604      0.000       0.090       0.124
x3             0.0003      0.006      0.058      0.954      -0.011       0.012
==============================================================================
Omnibus:                       16.081   Durbin-Watson:                   2.251
Prob(Omnibus):                  0.000   Jarque-Bera (JB):               27.655
Skew:                          -0.431   Prob(JB):                     9.88e-07
Kurtosis:                       4.605   Cond. No.                         454.
==============================================================================

---
## Conclusion

To summarise, we have performed a multiple linear regression and have covered some basic introductory statistics as well. This is by no means a comprehensive analysis of the marketing data set but simply an example of how to perform and interpret a mulitple linear regression. It’s a good starting point, especially when attempting to understand the relevance of important statistical concepts like t-statistic, p-value and standard error. 

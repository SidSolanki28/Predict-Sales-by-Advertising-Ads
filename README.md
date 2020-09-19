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

Nil

---
## Web Scraping

Dataset URL: https://www.kaggle.com/ashydv/advertising-dataset/notebooks

### Data fields

Values in thousand dollars.

Features:

* TV
* Radio
* Newspaper

Target:

* Sales budget

---
## Data Cleaning

There is no missing values in data.

---
## EDA

I looked at the distributions of the data and the value counts for the various categorical variables. Below are a few highlights :

![](https://github.com/SidSolanki28/Predict-Future-Product-Sales/blob/master/images/download.png)
![](https://github.com/SidSolanki28/Predict-Future-Product-Sales/blob/master/images/download%20(3).png)
![](https://github.com/SidSolanki28/Predict-Future-Product-Sales/blob/master/images/download%20(2).png)

---
## Model Building

### Facebook prophet
Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.

##### Advantages:
* Open Source
* Accurate and fast
* Allows for a large number of people to make forecasts, possibly without training in time series methods;
* Tunable parameters
* Available for both Python and R

---
## Model Prediction
Facebook prophet model for store Id 10 to forecast its sales
![](https://github.com/SidSolanki28/Predict-Future-Product-Sales/blob/master/images/download%20(4).png)
![](https://github.com/SidSolanki28/Predict-Future-Product-Sales/blob/master/images/download%20(5).png)

---
## Conclusion
This was an interesting study and it’ll be great to analyse the results when I get the actual views. Having said that, Prophet does make the entire forecasting process easy and intuitive and also gives a lot of options. The actual advantage of this model can only be assessed on large datasets but Prophet does enable forecasting a large number and a variety of time series problems — which is truly forecasting at scale.

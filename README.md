# Forecasting Bikeshare Demand<br>

<img src='visualizations/bikes.gif' width=500>

## Introduction
Capital Bikeshare is a DC-based bike sharing business. This dataset contains various weather and time conditions and is used to predict overall demand. 

## Data Exploration

Exploratory analysis will tell us how many bicycles are expected to be checked out during any given time of the day.<br>

Some questions explored are:<br>
Which factors contribute most to the number of bicycles being checked out over the course of a given day?<br>
How much of an impact does weather have on demand?<br>
How does the behavior of casual users differ from subscribers?<br>

### Outlier Analysis with Boxplots

<img src='visualizations/boxplots.png' width=700>

### Correlation Matrix
Correlation matrix to visualize how rentals are influenced by various features like temperature, atemp, humidity, and windspeed

<img src='visualizations/matrix.png' width=500>

<img src='visualizations/Distribution of Data.png' width=700>

<img src='visualizations/dependent variables time temp.png' width=700>

<img src='visualizations/observations.png' width=700>


### Feature Engineering

<img src='visualizations/feature engineering.png' width=1000>

## Windspeed

Frequency of windspeed values in the data:

<img src='visualizations/windspeed.png' width=1000>

# With a large number of zero values in the windspeed column, use random forests algorithm to do a missing values analysis

Windspeed after imputation:

<img src='visualizations/windspeed imputation.png' width=1000>


## Model Evaluation

RMSLE Scorer will be the main metric focused on evaluating. It will be particularly helpful in penalizing underestimation of the actual values. Once that's contraucted we can build the models.

<img src='visualizations/linear_regression_model.png' width=1000>

<img src='visualizations/Lasso.png' width=1000>

<img src='visualizations/Random_forests.png' width=1000>

<img src='visualizations/compare_distribution.png' width=1000>








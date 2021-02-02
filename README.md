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
Correlation motrix to visualize how rentals are influenced by various features like temperature, atemp, humidity, and windspeed

<img src='visualizations/matrix.png' width=700>

### Feature Engineering

<img src='visualizations/feature engineering.png' width=1000>

## Model Evaluation

RMSLE Scorer will be the main metric focused on evauating. It will be particularly helpful in Penalizing underestimation of the actual values. Once that's contraucted we can bukld the models.






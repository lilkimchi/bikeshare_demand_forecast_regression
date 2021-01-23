# Forecasting Bikeshare Demand<br>

<img src='visualizations/bikes.gif' width=500>

## Introduction
Capital Bikeshare is a DC-based bike sharing business. This dataset contains various weather and time conditions and is ised to predict overall demand. 

## Data Exploration

Some Exploratory analysis will tell us how many bicycles are expected to be checked out during any given time of the day.<br>

Some questions explored are:<br>
Which factors contribute most to the number of bicycles being checked out over the course of a given day?<br>
How much of an impact does weather have on demand?<br>
How does the behavior of casual users differ from subscribers?<br>

### Outlier Analysis with Boxplots

### Correlation Matric to Visualize how rentals are influenced by various features like temperature, atemp, humidity, and windspeed
### Observations:
- windspeed is correlation value with "count"
- 'atemp' and 'temp' are highly correlated (multicolinearity)
- temp has positive correlation with count
- humidity has negative correlation with count. Although the correlation between them is not very prominent still the count variable has got little dependency on "temp" and "humidity".

### Decision:
- drop windspeed during model building
- Drop atemp to avoid multicolinearity.
- drop 'Casual' and 'Registered' during model building.

## Feature Engineering





# Forecasting Bikeshare Demand<br>

<img src='visualizations/bikes.gif' width=500>

## Introduction
### How many bikes need to be ready?
Capital Bikeshare is a DC-based bike sharing business. This dataset contains various weather and time conditions, and is ised to predict overall demand. Some Exploratory analysis will tell us how many bicycles are expected to be checked out during any given time of the day.<br>

This dataset contains the following attributes:<br>
datetime: hourly date + timestamp<br>
season: 1 = spring, 2 = summer, 3 = fall, 4 = winter<br>
holiday: whether the day is considered a holiday<br>
workingday: whether the day is a weekend or holiday<br>
weather: 1: Clear, Few clouds, Partly cloudy, Partly cloudy 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
temp: temperature in Celsius<br>
atemp: "feels like" temperature in Celsius<br>
humidity: relative humidity<br>
windspeed: wind speed<br>
casual: number of non-registered user rentals initiated<br>
registered: number of registered user rentals initiated<br>
count: number of total rentals (Dependent Variable)<br>

## Data Exploration

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





# PyBer_Analysis

## Project Overview
V.Isualize has asked that for this project we perform an analysis of Pyber's ride-sharing data by city type, then create visualizations of the data that depicts the total weekly fares for each city type.
Our analysis aims to help guide Pyber decision-makers in providing better assess to ride-sharing services, and determine affordability of their service by neighborhood

## Results

After helping Omar and V.Isualize analyze Pyber's ride-sharing data, we were tasked with making a summary DataFrame that depicted several different variables within Pyber's service. 
![PyBer Summary DataFrame](https://user-images.githubusercontent.com/84881187/125173379-04acbd80-e18d-11eb-9c44-ad4b2c6b44bd.PNG)1

We then created a multi-lined graph to visualize the weekly fares for each typ of city:

![Pyber_fare_summary](https://user-images.githubusercontent.com/84881187/125173398-2c9c2100-e18d-11eb-8534-52c1811cf34e.png)

Looking at both our DataFrame and our graph, we are able to determine:

  * Urban cities have the highest number of riders, and Rural cities have the fewest.
  * Urban cities have over 4x as many drivers than Suburban cities, and 30x as many drivers than Rural cities.
  * Suburban cities have 6x as many drivers as Rural cities with almost 4.5x the Total Fares; and Urban cities have almost twice as many Total Fares than Suburban cities.
  * Rural cities have the highest average fare per ride and per driver.
  * The DataFrame summary shows that there is a correlation between Fares per Ride/Driver and the ratio of Total Drivers to Total Rides.
  * Urban areas have the highest total drives and rides, but the lowest Average Fare per Ride and lowest Average Fare per Driver despite the population density



## Analysis Summary
We were tasked with analyzing PyBer's ride-sharing data to create a DataFrame summary by city, that will help guide PyBer's decision-maker's. We examined the ride-sharing data by city type: Urban, Suburban, & Rural. We also parsed the data to analyze the Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and the Average Fare per Driver within those city types. Looking at our data, we were able to determine that even thought Urban cities have the highest Total Rides and highest Total Drivers, they ended up having the lowest Average Fare per Ride and lowest Fare per Driver. Our data analysis shows that Rural Cities had both the highest Average Fares per Ride, and highest Average Fares per Driver, despite them having the lowest Total Rides and Totales Drives by a large margin. 

Our data suggests that PyBer could potentially benefit from increasing the amount of drivers in rural areas to meet demand. Fewer rides in Rural areas could suggest that each of the 78 drivers is taking their fares on longer trips, which would result in the higher average fares per ride despite the lowest total rides. Increasing the amount of drivers within Rural cities could ensure there are enough riders to meet the demand of all riders, avoid missing potential fares, and increasing profits for both PyBer and their drivers. PyBer could create some incentive for their drives to head out to Rural areas and suburban areas to service the unmet demands in those areas. Collecting data on Average Distance per Ride would give us great datas for this hypothesis.

Another variable that could be worth collecting data on would be the Average Time of Day of each ride, or peak rides would also be a great asset in determining where to allocate drivers to effectively ditribute the driver to rider ratio in each city type to maximize fares.


# PyBer_Analysis_Challenge
Module 5 challenge repository for PyBer_Analysis

## Overview of the Analysis
After calculating various data about PyBer rides by City, we were asked to create a summary DataFrame of the ride-sharing data by city type. This included creating a multiple-line graph that shows the total weekly fares for each city type. This written report will summarize how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Results
It is not surprising that different "city types" (`Urban`, `Suburban`, and `Rural`) have different outcomes.  There is a large difference between the number of drivers, number of rides, and average fare for the three types.  

![Summary by City Type Data Frame](/analysis/Summary_by_City_Type.png)
### Total Rides
There is quite a difference in the number of rides in each area.  The larger 'Urban' cities have more than 2 and a half times the number of total rides of 'Suburban' cites and  13 times the number of total rides of the smaller 'Rural' areas

### Total Drivers
Understandably given the number of Rides available, the total drivers for these city types are even more varying with `Urban` cities having more than 30 times the number of  drivers of the `Rural` areas

### Total Fares
Total Fares in 'Urban' cities with more drivers and more rides are twice the total in 'Suburban' cities and more than 9 times the total in 'Rural' cities.

### Average Fare per Ride
Given the smaller number of rides and the fewer drivers, 'Rural' areas actually earn more per ride (on average) compared to the average fare per rides of both 'Suburban' and 'Urban' cities

### Average Fare per Driver
Given the smaller number of rides and the fewer drivers, this somewhat higher average fare per ride translates to a significant difference in Average Fare per Driver, with 'Rural' drivers earning more than three times as much as drivers in 'Urban' cities

### Total fare by city type
![Graph of Total Fares by City Type](/analysis/Pyber_fare_summary.png)
All three city types have dips and raises in the fare earned by week, and not always at the same time, showing that ridership is unique to each city type


## Summary
The smaller `Rural` sites with the fewest drivers and rides collect a the largest fare per ride (on average) and largest fare per driver (on average). While the larger, `Urban` cities with 13 times the number of total rides and more than 30 times the drivers of the `Rural` areas understandably earn less than a third of the average fare per Driver.  This may indicate an overabundance of drivers in certain areas of the 'Urban' cities.  Potentially incentivizing drivers to be available at peak times in various neighborhoods across the larger 'Urban' cities may help to spread this out somewhat.  Alternatively, It seems that there may be some need to hire more drivers in 'Rural' cities while working with these 'Rural' cities to understand the distances traveled and needs of the customers. 

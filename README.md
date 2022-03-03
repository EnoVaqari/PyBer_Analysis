# PyBer Analysis

## Overview of the analysis

This analysis includes ride and city datasets, which are used to create a ride sharing summary DataFrame by city type and a multiple-line chart of total fares for each city type. 
The purpose of the analysis is to identify the differences of data by different city types and provide the information to PyBer's decision-makers to assist with business decision making.

## Results

The analysis required the creation of a ride sharing summary DataFrame by city type and a multiple-line chart of total fares for each city type. In order to create a summary DataFrame for PyBer, we merged the datasets, and then we calculated the total number of rides and drivers, the sum of fares, and the average fare per ride and per driver for each city type. To create the multiple-line chart, we created the following dataframes: a dataframe that shows the total fare amount of each date and time; a dataframe with date as index, city type as columns, and fare as values; a dataframe with a date range from 2019-01-01 to 2019-04-28; and a dataframe that showed the sum of fares per week.

(summary dataframe png)

By analysing this summary DataFrame, we identify the following:

* Urban total rides number is higher than both Rural and Suburban rides combined.
* There are more drivers in the Urban cities than in both Rural and Suburban cities.
* Urban cities generate the highest revenue, and Rural cities generate the lowest based on total fares column.
* Rural cities have the highest average fare per ride, and urban cities have the lowest.
* Drivers in rural cities make more per ride ($55.49) compared to the drivers of Suburban ($39.5) and Urban ($16.57) cities.

This miltiple-line chart shows the total fare by city type.



(multiplechart)


The chart above identifies the following:

* Urban cities have the highest total fares from January to the end April.
* There is an icreased total fare for all types of cities during the 3rd week of February.
* There is a decrease of total fare for all types of cities during the fourth week of February.


## Summary 

After analysing our results, we make the following recommendations addressing the disparities among the city types:


* Increase the fare per ride in Urban cities to improve the average fare per ride ratio.
* Decrease the number of drivers in Urban cities to match the number of rides.
* Increase the number of drivers in Rural and Suburban cities to match the increasing ride requests.
* Due to the average perfomance in Suburban cities, the best investment opportunities lie in Rural and Urban cities.

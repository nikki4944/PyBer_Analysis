# PyBer_Analysis

## Project Overview

As part of a larger project to improve access and affordability to underserved communities, PyBer, a ride-sharing company, has requested an analysis of the data collected by its app showing the relationship between fare prices, number of drivers, and type of city served (rural, suburban, or urban). To demonstrate this relationship, I created a Pandas DataFrame showing the caluclation of the total number of drivers, total number of rides, total fares, average fare per ride, and average fare per driver broken down by each type of city served by PyBer. Finally, I created a visualiztion showing the total fares of each city type by week over a four month period in 2019, January to April.

## Analysis

The fist step of this analysis consisted of combining the provided city and ride data into a single Pandas DataFrame. As shown by the the below code, once consolidated, I was able to extract the total ride, total fare, and total drivers information, grouped by city type, in order to calculate the average fare per ride and per driver.

<img width="724" alt="Screen Shot 2021-05-27 at 1 36 18 PM" src="https://user-images.githubusercontent.com/82982901/119871736-bef3a880-bef0-11eb-98c9-dd693af699a6.png">

These variables were then used to create a DataFrame which clearly demonstrates the differences between the requested categories of analysis.

<img width="645" alt="Type DataFrame" src="https://user-images.githubusercontent.com/82982901/119872137-21e53f80-bef1-11eb-9849-b324e22ea65c.png">

As one might expect, rural areas have the fewest number of drivers and rides while urban areas have the highest concentration of both. Additionally, rural areas have the highest average fares per driver and per ride and bring in the smallest amount of revenue while urban areas have the lowest and are the most profitable.

In order to demonstrate this trend more clearly, I extracted all fares categorized by city type for the period of January 1st through April 28th from the provided 2019 app data. With this data set, I created a line graph to show the changes over time to the fares per city type.

![PyBer_fare_summary](https://user-images.githubusercontent.com/82982901/119873268-5e656b00-bef2-11eb-9963-ade6a2417164.png)

The graph reinforces the data findings from the prior DataFrame. Urban areas have the highest fare totals while rural areas have the lowest.


## Summary

A further analysis taking into consideration population density of the city types and mileage of each ride is recommended in order to determine a correlation between fare rates and mileage. Rural fares are more expensive than urban ones but they are also fewer in number. This could be due to a smaller population in rural areas as well as a difference between the distance traveled per ride, further analysis taking these factors into account would be needed to confirm. 

An analysis taking mileage into consideration would be useful for evaluating a potential change to how PyBer charges its users and may help make the app more affordable.

Based on the provided data, it is recommended that more drivers be added to the rural areas. While these areas account for the least amount of business, the urban area has more drivers than rides. Additionally, it is recommended that more marketing and promotion be centered in the urban area with the most concentration of drivers in order to have total rides more closely match the number of drivers. 

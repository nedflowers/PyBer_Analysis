# PyBer_Analysis

## Overview of Project

Perform exploratory analysis of rideshare data with visualization, python script, Jupyter Notebook, and Matplotlib. The analysis will help improve rideshare accessibility and affordability for underserved neighborhoods. First, separate the cities into three types: rural, urban, and suburban. Next, find the total drivers, rides, fares, and averages of fares per ride and driver. Finally, create a multiple-line chart to visualize the differences. 

## Analysis of Rideshare Data
 
The following DataFrame was created to showcase the difference in data between city types: 

<img width="444" alt="pyber_summary_df" src="https://user-images.githubusercontent.com/95272294/150885839-d48670f0-85f7-4e54-a64e-a1fea5deb73b.png">

- ### Rides
    * Urban areas had 13x more rides than rural areas
    * Suburban areas had 3x less rides than urban areas
    * Rural cities had 5x less rides than suburban areas
- ### Drivers
    * Rural areas had about 31x less drivers available than urban areas
    * Suburban areas had 6x more drivers than rural areas
    * Urban areas had 5x more drivers than suburban areas
- ### Total Fares
    * Urban areas brought in the largest amount of revenue 

![total_fare_by_type](https://user-images.githubusercontent.com/95272294/150885880-f51ff04c-8fff-4b2e-bf5c-e2ba8f1cb430.png)

- ### Average Fares
  * Average fare per ride was highest in rural areas and lowest in urban areas
  * Average fare per driver was highest in rural areas and lowest in urban areas

## Summary

The analysis points toward a trend where fare revenue is largest when the demand for rides is higher than the driver-to-ride ratio. For example, looking at the Pyber Summary Data Frame, urban areas are the only city type where the number of rides is lower than the total amount of drivers. Not surprisingly, we see urban areas have the lowest averages in revenue for fares per driver and per ride. 

To improve accessibility and affordability in rural areas, which are the most underserved, I would suggest increasing the number of drivers in rural areas. I believe capping the number of drivers available at a high driver-to-ride ration will increase average revenue for urban areas. Finally, I think this analysis leaves room for more research into the high cost of rural rideshares. Rates should lower with more drivers, but are rural ride-shares driving longer distances than their urban or suburban colleagues? Is distance, perhaps, a bigger factor in cost of travel than the current data suggests? Again, I believe these questions call for further exploration of ride-share data. 



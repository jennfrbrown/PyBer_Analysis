# PyBer_Analysis

## Overview of the analysis:

### Purpose

The purpose of this analysis is to perform exploratory data analysis for PyBer, a ride-share company.  Once the analysis is complete, we will make graphs to show the data is a compelling, visual way.  This analysis focuses on the relationship between city type - urban, suburban, and rural - and its relationship to fares, number or drivers, number of rides, and when those rides occurred.  We are specifically looking at data collected from January to the end of April 2019.

#### Resources
- Data Source: 
  - city_data.csv
  - ride_data.csv
- Software: 
  - Juypter Notebook: 6.0.3
- Environment: 
  - Python 3.7.6
- Dependencies:
  - Matplotlib Library 3.2.2
  - Pandas Library 1.0.5
 
### Results

#### Summary
<img src ="https://github.com/jennfrbrown/PyBer_Analysis/blob/master/Analysis/PyBer_fare_summary.png">

- Total Rides
  - Urban cities have the greatest number of total rides, 2.6 times higher than suburban cities and 13 times higher than rural cities.
  
- Total Drivers
  - Urban cities have the greatest number of total drivers, 4.9 times more than suburban cities and 30.8 times more than rural cities.  This is supported by urban cities also having the highest number of total rides.
  
- Total Fares
  - Urban cities produce the highest of total fares, 2.1 times higher than suburban cities and 9.2 times more than rural cities.  This is supported by urban cities also having the highest number of total rides and the greatest number of drivers.
  
- Average Fare per Ride
  - Rural cities have the highest Average Fare per Ride, 1.4 times higher than Average Fare by Ride in urban cities and 1.1 times higher than Average Fare by Ride in suburban ciies.  This is supported by rural cities having a greater distance between destinations, thus potentially having longer rides.

- Average Fare per Driver
  - Rural cities have the highest Average Fare per Driver, 3.3 times higher than Average Fare by Driver in urban cities and 1.4 times higher than Average Fare by Driver in suburban cities.  This is supported by rural cities having a greater distance between destinations, thus potentially having longer rides and rural cities also having the least number of drivers.
 
 
 <img src="https://github.com/jennfrbrown/PyBer_Analysis/blob/master/Analysis/Deliverable_2_Challenge_Graph.png">
 
When looking at results for each city type in correlation to the total fare amount per week from January to the end of April 2019, you see that all city types have a steady number of rides from week to week.  Of interest is a matching spike in the third week of February.

#### Business Recommendations.
1. There is a matching peak in the third week of February for all city types.  Determining the cause of this peak would be beneficial to help determine any marketing or business strategies surrounding it.  Was this a result of a holiday or a special event?  If so, what promotions or driver ability strategies can be incorporated to capitalize on the increase utilization?

2. Rural city types have the greatest average fare per ride.  If PyBer is looking to recruit drivers, it would be be beneficial to show driver's what their potential income could be.  Drivers may not want to work for $25/ride but may be enticed to work for $35/ride.

3. In January and February, the data shows an inverse relationship between fares in urban and rural areas.  Those in the rural areas are more likely to own cars than those in urban areas.  The weather may play a factor into ride decisions.  PyBer could provide an incentive for rural drivers to work in urban areas or it could provide a package deal for those in the urban area to promote multiple ride purchases. 


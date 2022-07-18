## Pyber Analysis


## Overview


### Purpose

* The purpose of this project is to provide an analysis of Pyber ride and fare data during a 4-week period in 2019 in a sampling of rural, urban and suburban cities. 

* Specifically, the goal is to provide statistical and graphical models to evaluate whether Pyber fare totals differ by city type (urban, suburban, rural).  If disparities are found, the analysis should provide recommendations on how to further explore and/or address these.  

### Data Description

Two data sets were provided: 
```
City data:   city name, city type, number of Pyber drivers

Ride data:   ride date/time, fare, ride_id

```
Figure 1.   Sample of the merged city and ride data sets.

![Merged DataFrame sample](https://user-images.githubusercontent.com/107505166/179433367-cba63363-7a54-4b21-9a7b-8004f852d87a.PNG)

## Analysis 

### Ride and Fare Data Table 

Ride and fare data were summarized to allow a comparison of total number of rides, total number of drivers and total fare amounts by city type, as well as the average fare per ride and average fare per driver by city type.

Figure 1.   Summary table of ride and fare data by city type
![Pyber summary table](https://user-images.githubusercontent.com/107505166/179433404-0912eb4a-cae9-4fe7-b54f-e53ee9d2c057.PNG)
* In the summary data table, we see that Pyber ride activity, number of drivers and fare totals in the sample data are largest in urban cities and smallest in rural cities with suburban cities falling in the middle.   These data points appear to vary proportionally with city size.  This would be expected as transportation activities in a population are generally dependent on population size. 
* However, average fare amount per ride and average fare amount per driver appear to vary inversely with city size.  We may guess that residents in rural areas may need to travel longer distances to reach their desired destinations, and thus the total fare amounts for rural trips are higher, but we can't base that conclusion on the data provided for analysis.

### Total Fare Comparison Chart

A line chart was provided to show total weekly Pyber fare amounts per city type over a 4-month period.

Figure 2.   Weekly Pyber ride fare totals by city type
![Total Fare by City Type chart](https://user-images.githubusercontent.com/107505166/179433433-4c3e9cc6-8a95-42e3-acc1-099c1285af10.png)
* The chart graphically displays the expected proportionality of total fare amounts to city size.

## Summary

### Recommendations  
* Clearly defined goals will be helpful in making use of this analysis of weekly total Pyber fare amounts by city type.
* Disparities in total fare amounts by city type have been demonstrated, but would be expected given the relationship of transportation activity to population size.  
* Disparities in average fare amount per ride and average fare amount per driver could be due to length of trip, but need to be analyzed further. 
* The data set provided is hampered by the data points that aren't included.   Helpful data points to include would be Pyber driver ID, and trip length.  These data points could help inform statistics such as the average fare amount per driver and the average fare amount per ride with more meaningful explanations.   

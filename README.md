# Surfs Up
Using Python, SQLAlchemy, and Flask, analyze and visualize climate data as you prepare to open up a surf shop.

## Challenge Overview 

An analysis on Oahu's weather could help determine whether seasons affect the surf and ice cream shop business in the island. 
In this analysis, I compared June and December data to describe summer and winter temperatures across a seven-year period. 
During this time period, both June and December had an average temperature of 75°F and and 71°F, respectively. 
June had a low temperature of 64°F and a high temperature of 85°F whereas December had a low temperature of 56°F and a high temperature of 83°F.
In addition, both June and December had roughly similar standard deviations. 
June's standard deviation of 3.26 and December's standard deviation of 3.75 tells me that their temperature records are concentrated around both of their average temperatures. Lastly, June and December had a 75th percentile of 77°F and 74°F, respectively, 
which indicates that these two seasons had relatively warm temperatures.

## Summary of Findings
I would summize that even though temperatures recorded in December seem to vary more than those of June, December would still provide appropriate weather conditions for both surfing and demand in ice cream. The average temperatures in June and December only differ by 4 degrees, and looking at the December histogram, I feel more confident in this decision--December's median temperature, with the highest frequency recorded across a span of years, is about 72 degrees, at least double the frequency of the next highest recorded temperatures, 75 and 67 respectively. It would be ill advised to not open the surf and ice cream shop based on at first clance temperature minimums.
Before making a final deicision though, I would want to perform some additional queries to get more color on weather conditions in these two months.

1. For specificity, I would like to delve into the summary statistics of temperatures recorded by station for each month. This can help determine geopgraphically where in Oahu to build the prospective shop. By comparing the variances in temperatures and the frequencies recorded, we can narrow in on an optimal location. 
- _Stations vs Temps for June and December Starting Point_
<img width="656" alt="station_temps" src="https://user-images.githubusercontent.com/77628698/121732019-af16bf80-cabf-11eb-90b5-a7918402c3b7.png">

2. Secondly, I would like to review other important variables that are correlated with optimal beach and surfing weather. Such varibles include precipitation, wave swells and wind condition. Though there may be some contrasting optimal conditions based on surfing vs sunbathing, it is important to identify those conditions and see how they correlate to foot traffic to the beach (depending on the time of year). It would be foolish to only value temperatures as the key indicator for opening a business. 
![June vs December Scatter Plot](https://user-images.githubusercontent.com/22300710/143785039-3dbd58da-f571-478a-86d2-514f0f62dcfd.png)

Recommendations
 I would recommend further analysis on:
* Precipitation to observe quantity and frequency during June and December, and determine whether precipitation plays a factor despite the warm temperatures that are experienced during this time.
* Elevation to observe and compare in various Oahu locations, and determine whether one location's elevation attracts or deters business more than another location.
* Elevation to observe and compare in various locations in Oahu, and determine whether one location's elevation attracts or deters business more than another location.
* Elevation relative to both temperature and precipitation during June and December, and determine whether these metrics coupled together also contribute to business.
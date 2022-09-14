# PyBer Analysis Challenge
## Overview of the Analysis

I have just started working for PyBer, a ride sharing app company.  I have been working with very large csv files and using them to show visualizations.  Our goal is to improve access and affordability to the underserved neighborhoods.  I am working on this goal with my manager, Omar, and our CEO, V. Isualize.

In my current assignment I will use Python and Pandas to create a summary DataFrame of the ride sharing data by city type.  Then using Pandas and Matplotlib I will create a multiple line graph that shows weekly fares for each city type.  Finally I will prepare this and present it in a report format so PyBer executives can use it in their decision making.

## Resources
The resources for this analysis are as follows:

•	Data Source: city_data.csv and ride_data.csv files.

•	Software: Python 3.7.6, Jupyter Notebook version 6.4.8, Pandas version 1.4.5, MatPlotLib version 3.5.2 and Numpy version 1.21.5

•	Repository: GitHub


## Results

### Total Fare by City Type

![__](https://github.com/Johnnytoobadman/PyBer_Analysis/blob/main/analysis/PyBer_Graph.png)

The above graph shows:

-	Rider total fares are highest in the urban areas. This would make sense considering that the need for ride sharing in the urban area is greater because of the cost and hassle of parking and owning a vehicle. Also Urban areas have higher density. These rides would be shorter rides and the drivers would be able to quickly pick up another rider keeping them busy.
 
-	Suburban and Rural Rider total fares will be lower than the urban total fares due to lower density, better parking and longer distances to cover which encourages vehicle ownership. The further the distances of the rides the lower the total fares.  Suburban rider demand is low and Rural demand is the lowest.


The DataFrame below shows a similar trend of higher figures for urban areas and lower for Suburban and the lowest for Rural.

![__](https://github.com/Johnnytoobadman/PyBer_Analysis/blob/main/analysis/Pyber%20Averages%20Summary.png)


![__](https://github.com/Johnnytoobadman/PyBer_Analysis/blob/main/analysis/PyBer%20Averages%20with%20Percentages.png)

The above spreadsheet takes the DataFrame one step further by doing percentage analysis on the values:

-	The percentages show that Urban drivers are getting 68% of the rides yet have 81% of the drivers meaning some drivers are not getting much work.  Especially since urban driver’s can usually get their next rider quickly.
 
-	Suburban drivers are getting 26% of the rides but only have 16% of the drivers meaning they are likely overworked, especially when you consider the additional distance required to get the next ride.

-	Rural drivers are getting only 5% of the rides have only 3% of the drivers and have the longest distances to covers with the furthest to go to get the next rider.


## Summary 

### The recommendations to the Chief Executive Officer and executives are as follows:

-	The number of Urban drivers is not optimal.  Urban drivers represent 81% of all drivers but are only getting 68% of the rides.  This is further exacerbated by the quick turnaround drivers get with riders in the urban area. Some of these drivers would be better served working in the suburban and rural areas and should be encouraged to make the change.
 
-	Increase the demand in the urban areas to help get the urban driver’s more work.  This may involve marketing, advertising and even fare reduction as they have high fares per ride.

-	Increase the fares in the suburban and rural areas to attract more drivers, incentivize them and accommodate them for the additional time and cost of the additional distances that are required to work in the lower density areas. Additional marketing and advertising will be needed to offset the fare increases.



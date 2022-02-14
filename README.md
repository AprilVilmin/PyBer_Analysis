# PyBer with Matplotlib

## Overview of Project
As a new data analyst at PyBer, a ridesharing company, you are tasked with making visualizations using pandas in conjunction with matplotlib to create a line graph with multiple lines to display the variations in fares between rural, suburban and urban cities. To make this line graph you will be using fare data at the weekly level for each city type.

## Results

### Total Fares by Month/Week
The results of analysis revealed that on a weekly basis between January 2019 and the end of April 2019 urban cities made the most fares. Urban cities were always above $1,500. Whereas Suburban cities stayed between $500 and $1,500  and rural cities stayed under $500. Meaning that urban cities earn at least three times the amount of fares in the same time period as rural cities. This can be see in greater detail in the graph below. 

![PyBer_fare_summary.png](https://github.com/AprilVilmin/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)


### Total Rides
The data shows that the total number of rides in the PyBer Summary Data is higher for urban and suburban areas than it is for rural areas. Urban cities gave 1000 more rides than suburban cities. Urban cities gave 1,625 rides, suburban cities 625 and rural cities 125. That is urban cities have 62% more rides than suburban cities and 92% more rides than rural communities. This can be seen in the dataframe below.

### Total Drivers
The number of drivers who drive for PyBer are greater in urban areas than suburban areas and greater in suburban areas than rural areas. There are 2,405 PyBer drivers in urban cities, 490 in suburban cities and 78 in rural cities. There are more drivers in urban cities than in rural and suburban cities combined. This can bee seen in the dataframe below.

### Total Fares
Due to the vast difference in the number of rides and drivers between urban and rural cities the total fares is much higher for urban cities than rural cities. The total amount of fares for suburban cities is also greater than it is for rural cities. The amount of total fares for rural cities is about an eighth of total fares for urban cities. This can be seen in greater detail on the dataframe below.

### Average Fare per Ride
 and in  a Contrary to how the Total Fares metric is higher in urban cities, the Average Fare per Ride metric is higher in rural communities. This makes sense as riders in rural communities are most likely going to have to travel farther between destinations on average and drivers are going to have to travel farther to pick them up. The average fare per ride in a rural city is $34.62, in suburban city $30.97 and in an urban city $24.53. The average fare is about $10 cheaper in an urban city rather than a rural city. This can be seen in the data frame below.

### Average Fare per Driver
Like the Average Fare per Ride metric, the Average Fare Per Driver metric is also higher in the rural cities than it is in urban and suburban cities. The average fare per driver in urban cities is $16.57, in suburban cities $39.50 and in rural cities 55.49. This means that that a rural city driver earns about two-thirds more per ride than a urban city driver. This can be seen in the dataframe below.


![PyBer_Summary_DataFrame.png](https://github.com/AprilVilmin/PyBer_Analysis/blob/main/Analysis/PyBer%20Summary%20DataFrame.png)


## Summary
Based on the results, the following recommendations are made to solve disparities:

1. Try to increase both riders and drivers in suburban cities.
2. Reduce the number of drivers in urban areas to try to increase the Average Fare per Driver for urban cities.
3. Increase the number of drivers in rural cities If the drivers didn't have to travel as far or the customers have to wait so long, maybe there would be higher utilization.

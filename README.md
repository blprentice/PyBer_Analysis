# PyBer Ridesharing Analysis

## Project Overview
The purpose of this project is to analyze PyBer ridesharing data to identify disparities between city types and how those disparities could be addressed by PyBer leadership. It consists of two technical deliverables: 1. a Pandas summary DataFrame breaking out and displaying PyBer ridesharing data by city type (urban, suburban, and rural) and 2. a multiple line graph depicting total weekly fares for each city type.

## Results of the analysis
![PyBer Summary DataFrame](../analysis/PyBer_Summary_DataFrame.png)

The totals data for each city type makes intuitive sense. Urban cities have far and away the most total rides, total drivers, and total receipts from fares, followed by Suburban cities and then Rural cities. The roles are reversed when looking at the averages data: Rural cities have the highest average fare per ride and per driver, followed by Suburban and Urban cities. In fact, Rural fares per driver are over three times that of Urban cities. Of course, Urban cities have many more drivers than rural areas - 13 times as many. Ultimately, the situation we have is downward pressure on fares in Urban cities due to the surfeit of drivers and upward pressure on fares in Rural cities due to a relative dearth of drivers. The situation in Suburban cities is more nuanced, but is closer to the situation in Rural cities than Urban cities. Suburban cities have less than half (38%) as many rides as Urban cities and not even a quarter (20%) as many drivers. Total fares in Suburban cities stand up better to that of Urban cities, but still falls shy of half as much (49%). Average fare per ride is only a few dollars less in Suburban cities than in Rural cities, while there is more separation in average fare per driver in Suburban cities compared to Rural cities, but closer in value than between Suburban and Urban cities.

![Total Fare by City Type](../analysis/Total_Fare_by_City_Type.png)


The above graphic depicts total weekly fares by city type from January through April. The first impression upon studying the three lines on the graph is that they are all fairly flat; there are no major spikes in the data for urban, suburban, or rural cities. Total weekly fares for urban cities started the year around $1600, then rose to above $2000 and stayed there until the end of April. The high points for urban cities were in late February and early March, when total fares reached approximately $2500. Total fares in suburban cities tracked just above or below $1000 for most of the period, except for a spike in late February that almost reached $1500. Total fares for rural cities tracked just above and below $250 for most of the period. There were two spikes in the data, though, in late February and the beginning of April when total fares were just below and approximately equal to $500, respectively. All three city types experienced a spike in the fare data in late February; more research could be conducted to find out if there was any particular reason for that.

## Summary

Urban cities will always be the core of PyBer's business. Urban cities are where most of the people live, especially younger people who either cannot afford a personal vehicle or prefer not to own one. That said, increasing the number of drivers in Suburban and Rural cities should be a high priorty for PyBer. Developing some type of incentive structure will be necessary to encourage more people to become PyBer drivers in Suburban and Rural area. Here are three possible options:

- Providing a low-cost "Lease to Buy" option for potential drivers in Rural and Suburban cities
- Developing a subsidy program to assist with the cost of fuel
- Developing a bonus program for drivers in Urban cities who agree to drive in suburban or rural cities

Of course, all three of these options represet a cost for PyBer. But, as the old saying goes, you have to spend money to money!
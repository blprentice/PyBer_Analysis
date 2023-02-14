# PyBer Ridesharing Analysis

## Project Overview
The purpose of this project is to analyze PyBer ridesharing data to identify disparities between city types and how those disparities could be addressed by PyBer leadership. It consists of two technical deliverables: 1. a Pandas summary DataFrame breaking out and displaying PyBer ridesharing data by city type (urban, suburban, and rural) and 2. a multiple line graph depicting total weekly fares for each city type.

## Results of the analysis
![PyBer Summary DataFrame](analysis/PyBer_Summary_DataFrame.png)

The totals data for each city type makes intuitive sense. Urban cities have far and away the most total rides, total drivers, and total receipts from fares, followed by Suburban cities and then Rural cities. The roles are reversed when looking at the averages data: Rural cities have the highest average fare per ride and per driver, followed by Suburban and Urban cities. In fact, Rural fares per driver are over three times that of Urban cities. Of course, Urban cities have many more drivers than rural areas - 13 times as many. Ultimately, the situation we have is downward pressure on fares in Urban cities due to the surfeit of drivers and upward pressure on fares in Rural cities due to a relative dearth of drivers. The situation in Suburban cities is more nuanced, but is closer to the situation in Rural cities than Urban cities. Suburban cities have less than half (38%) as many rides as Urban cities and not even a quarter (20%) as many drivers. Total fares in Suburban cities stand up better to that of Urban cities, but still falls shy of half as much (49%). Average fare per ride is only a few dollars less in Suburban cities than in Rural cities, while there is more separation in average fare per driver in Suburban cities compared to Rural cities, but closer in value than between Suburban and Urban cities.

![Total Fare by City Type](analysis/Total_Fare_by_City_Type.png)



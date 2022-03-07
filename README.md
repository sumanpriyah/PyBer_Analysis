# PyBer analysis

## Overview of the analysis:

In this project we need to deliver below deliverables for the analysis of the PyBer by importing data into Pandas DataFrame from csv files, Merging dataframes, using functions pivot(), resample(),creating plot using Python libraries like Jupyper Notebook, Pandas, Matplotlib.
The purpose of the project is help Omar to create summary DataFrame of the ride-sharing by city type through Visual story so that stakeholders at PyBer can determine affordability for underserved neighborhoods by increasing the drivers.
 
 ### Deliverables
1: A ride-sharing summary DataFrame by city type

2: A multiple-line chart of total fares for each city type

3: A written report for the PyBer analysis (README.md)

	
### Software Used
python- 3.9.7 , conda 4.10.3, jupyter 1.0.0

## Results:
### PyBer summary DataFrame
The PyBer Summary DataFrame shows data -Total rides, Total Drivers, Total Fares, Average fare per Ride , Average fare per Driver by city type (Rural, Suburban and Urban)
The total rides in the Urban cities are about 5 times and 13 times higher than Suburban and rural cities, respectively. 
The average fare per driver in the rural cities is about 3.5 and 2.5 times higher than urban and suburban cities, respectively.
The total fares as per city type is very low in Rural and very high in Urban but Average fare per ride is almost similar due to a smaller number of 
drivers in rural cities and a greater  number of drivers in the Urban cities.
As per data there are 0.67 rides per driver for Urban, 1.27 rides per driver for Suburban, 1.6 rides per driver for rural cities.

![PyBer_Fare_Summary dataFrame](https://github.com/sumanpriyah/PyBer_Analysis/blob/main/analysis/Pyber%20summary%20DataFrame.png)

From below plot its concluded that the total fares by city type is way higher in the Rural than in Suburban or Urban.
In the end of feb week of 2/24 the total fares went high for all city types. In March the fares went high and low. 
The total fares are high in rural cities during Feb, march and April, it means there are more rides during that time frame and less drivers. 
For Urban and Suburban the the total fares are less in march as compare to Rural. 

![PyBer_fare_summary]https://github.com/sumanpriyah/PyBer_Analysis/blob/main/analysis/Weekly_fare_dataframe_per_city_type.png)

![](https://github.com/sumanpriyah/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary:
The three recommendations that we can give to the CEO based on the visual data are:
1) Increase drivers in the rural area so that average fare per ride can come down. 
2) Reduce the drivers in Urban cities and Suburban cities when the peak is less because as per data  per driver there is 0.67 rides that means sometimes drivers are not getting work. 
3) More drivers should be added for the weeks where it shows rise in fares for Urban, Suburban and Rural.



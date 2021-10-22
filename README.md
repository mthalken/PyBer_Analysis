# PyBer Analysis

## The purpose of this analysis is to prepare ride sharing data from the PyBer company and be able to present the information found in graphs. 

## Project Overview:
1. Calculate and present a bubble chart that shows the average fare versus the total number of rides based on the total number of drivers for each city type (including urban, suburban, and rural). 
2. Calculate the measures of central tendency for the total number of rides, the average fares, and the total number of drivers for each city type.
3. Create box-and-whisker plots to display outliers for the number of rides, fares, and drives by city type. 
4. Create a pie chart to show the percent of total fares, rides, and drivers by city type.
5. Calculate and present a summary of the data that shows the weekly fares by city type in a multiple-line graph. 

## Resources
- Source of data: [city_data.csv](https://github.com/mthalken/PyBer_Analysis/blob/main/Resources/city_data.csv) & [ride_data.csv](https://github.com/mthalken/PyBer_Analysis/blob/main/Resources/ride_data.csv)
- Software: Python 3.7.10, Conda 4.10.3, Jupyter Notebook 6.3.0, Visual Studio Code 1.60.2
- Please see the [here](https://github.com/mthalken/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb) to see the refactored code.
- You can also see the preliminary code [here](https://github.com/mthalken/PyBer_Analysis/blob/main/PyBer.ipynb)

## Results 
### Analysis
- Total ride fare Summary

    ![png](https://github.com/mthalken/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary_table.PNG)
- Total ride fare by city type (Summary)
    ![png](https://github.com/mthalken/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)
- PyBer Ride-Sharing Data (2019) based on total number of rides per city and the average fare in US dollars. 
    ![png](https://github.com/mthalken/PyBer_Analysis/blob/main/analysis/Fig1_bg.png)
- Ride Count based on city type and the number of rides.
    ![png](https://github.com/mthalken/PyBer_Analysis/blob/main/analysis/Fig2.png)
- Ride fare based on city type and number of rides.
    ![png](https://github.com/mthalken/PyBer_Analysis/blob/main/analysis/Fig3.png)
- Driver count based on city type and number of rides. 
    ![png](https://github.com/mthalken/PyBer_Analysis/blob/main/analysis/Fig4.png)
- Percentage of total fares by city type.

    ![png](https://github.com/mthalken/PyBer_Analysis/blob/main/analysis/Fig5_bg.png)
- Percentage of total rides by city type.

    ![png](https://github.com/mthalken/PyBer_Analysis/blob/main/analysis/Fig6_bg.png)
- Percentage of total drivers by city type.

    ![png](https://github.com/mthalken/PyBer_Analysis/blob/main/analysis/Fig7_bg.PNG)

## Summary
In summary while the average fare per driver and per ride is larger in rural communities the total number of rides is in urban communities is 92.9% larger than in rural. The same relation is also shown in the total number of drivers and total fares. There was one outlier in the Ride Count Data analysis for urban communities at 39 rides that must be noted.  By looking at the [Percentage of total fares by city type](https://github.com/mthalken/PyBer_Analysis/blob/main/analysis/Fig5_bg.png) pie chart you can see that increasing drivers in urban and suburban cities will have a higher return. Also looking at [Total ride fare by city type summary](https://github.com/mthalken/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png) you can see that total fares have increased in the first quarter of 2019 for urban and suburban while rural cities have relatively stayed the same. 

Further analysis could look at the ratings of the drivers as well as tip amount and average per city type. We could also look at total advertising and marketing costs per city type for drivers and rides compared to total fares. 
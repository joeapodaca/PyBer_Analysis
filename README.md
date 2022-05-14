# PyBer_Analysis

## Overview
V. Isualize would like to see a summary of the ride-sharing data by city type.  Seeing those differences will help the decision-makers at PyBer.

### Resources
Data Source: ride_data.csv, city_data.csv, Pyber_ride_data.csv

Software Python 3.6.1, Jupyter Notebook

### Results
Lets start by breaking down the average fare by city types.  After all the higher the fare the more money, right?  The Box and Whisker plot below shows that the rural cities have the highest average fares.  They must be raking it in.

![Box and Wisker](https://github.com/joeapodaca/PyBer_Analysis/blob/main/analysis/Fig3.png)

But how many drivers are collecting these high fares. Let’s count the average number of drivers in each city type. You can see in the Box and Whisker plot below that the urban cities have the most drivers.  Rural cities have very few drivers.

![Box and Wisker](https://github.com/joeapodaca/PyBer_Analysis/blob/main/analysis/Fig4.png)

With all these drivers in urban cities, how many people need a ride?  In the Box and Whisker plot below the urban cities also have the most riders.

![Box and Wisker](https://github.com/joeapodaca/PyBer_Analysis/blob/main/analysis/Fig2.png)

In the scatter plot below the circle size correlates with the driver count per city.  You can see that the urban city drivers are providing the most rides per city type.

![Scatter Plot](https://github.com/joeapodaca/PyBer_Analysis/blob/main/analysis/fig1.png)


This is getting interesting. The Pie Chart below shows that even though rural cities fares are the highest, the urban city drivers are collecting the most fares.

![Pie Chart](https://github.com/joeapodaca/PyBer_Analysis/blob/main/analysis/Fig5.png)

Let’s create a new dataframe to show how the fares are collected overtime.  Let’s break down the data by city type over the last few months.  You can clearly see a big difference between the fares being collected in each city type.

![Line Chart](https://github.com/joeapodaca/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)


## Summary
Urban cities are collecting about 8x more than rural cities and 2x more than suburban cities.  Although rural cities have higher fares, they are giving very few rides and not making as much money.  The urban drivers are collcting less per fare, but are giving far more rides.  Suburban cities fall right in the middle.  Subruban has a good number of riders but looks like they can use some more drivers.

Here are my 3 recommendations.

  1) Increase fares in urban cities to maximize profits.
  
  2) Decrease fares in rural cities to encourage more riders.
  
  3) Increase driver share of fare in suburban cities to encourage more drivers.


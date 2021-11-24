# PyBer_Analysis

## Overview

### Purpose:
Pyber is a ride-sharing app company, and we've been asked to do an exploratory analysis on some   very large CSV files.  Our job is to create a variety of charts that showcase the relationship between the type of city and the number of drivers and riders, as well as the percentage of total fares, riders, and drivers by type of city.
  
### Process:
- Create line, bar, scatter, bubble, pie, and box-and-whisker plots using Matplotlib.
- Add and modify features of Matplotlib charts.
- Add error bars to line and bar charts.
- Determine mean, median, and mode using Pandas, NumPy, and SciPy statistics.


## Results

![Summary_df](https://github.com/charlagarcia/PyBer_Analysis/blob/main/analysis/pyber_summary_df.png)
  - Looking at the DataFrame, we can see that Urban cities have nearly 3x the number of riders than Suburban cities, and 13x the number of riders than Rural cities!
  - While the number of rides, drivers, and total fares increase from rural to suburban to urban, the average fare per ride and per driver actually decrease in direct correlation to the city type. This tell us that urban cities make more money based on the volume of riders, and while rural communities don't serve as many customers, they make more money per ride.
  - We can tell that drivers in rural communities make significantly more money than those in more populated areas. 
_________________________________________________________________________________________________________________

![Total_fare_line](https://github.com/charlagarcia/PyBer_Analysis/blob/main/analysis/total%20fare%20by%20city%20type.png)
  - This line chart shows us clearly the high and low seasons in each city type. It is clear that all three city types follow the same pattern of highs and lows with only minor differences.
  - The beginning of January is one of the biggest differences - while fares raise significantly in urban and suburban cities, they drop to almost nothing in rural communities.
_________________________________________________________________________________________________________________

![overall bubble](https://github.com/charlagarcia/PyBer_Analysis/blob/main/analysis/overall%20data.png)

**(circle size correlates with driver count per city)**
  - Looking at this chart of overall data for PyBer, we can see the number and size of bubbles increase based on color (city types).
  - This chart visually shows the number of drivers increasing significantly with the denseness of population.


## Summary
Three recommendations I would make to PyBer's CEO are:
  1. Look into reducing the number of drivers in Urban cities. These areas seem to be oversaturated with drivers.  While this is great for the rider since they'll have almost no wait time, it might be worth a few minutes of waiting for the drivers to be able to pick up more rides.
  2. Consider adding those urban drivers to rural routes instead.  Riders likely have a long wait time for rides because the driver population is small and routes tend to be longer.
  3. Invest in advertising in rural communities!  Ride-sharing isn't just for big cities, and rural residents are less likely to know that this service is available to them!

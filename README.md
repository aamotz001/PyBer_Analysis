# PyBer Rideshare Analysis
## Overview
Our goal is to help a rideshare company make informed decisions based upon analysis of data sets summarizing buisness in the past year. To begin, we aggregate all of the data given to us into a DataFrame which summarizes the parameters which will be important to our discussion. The resulting DataFrame is shown below in Figure 1.  Essentially, it the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type (rural, suburban or urban). To further summarize the data, the initial database is further sorted according to city types and the fares by city type over a section of the year is considered.

![alt_text](https://github.com/aamotz001/PyBer_Analysis/blob/main/Images/Fig1.png)
**Figure 1: Initial DataFrame for Rideshare Analysis**

## Results
The figures below (2-7) summarize trends which are of interest to the company. Firstly, we have a scatter plot which provides a visual summary of the data: a scatter plot, which compares the average fare (y axis) to the 
total rides in a given city (x axis). The size of the point correlates to the number of drivers in the city, and the color indicates the type of city the data point belongs to. The visual summary confirms a trend that the urban rides tend to be more plentiful, but less costly, and in contrast, the rural rides tend to be more profitable per ride, but occur at a much slower rate.

![alt_text](https://github.com/aamotz001/PyBer_Analysis/blob/main/analysis/Fig1.png)
**Figure 2: Ride Share Data Summary**

In order to compare the different types of cities, two pie charts which compare the percentage of fares by city type and the number of drivers per city type are shown. This identifies a lack of balance between the percentage of drivers as compared to the fare percentage: it would likely be most efficient to have these fractions be the same.

![alt_text](https://github.com/aamotz001/PyBer_Analysis/blob/main/analysis/Fig5.png)

**Figure 3: Fares by City Type**

![alt_text](https://github.com/aamotz001/PyBer_Analysis/blob/main/analysis/Fig7.png)
**Figure 4: Number of Drivers by City Type**

Next, we a DataFrame which includes the total rides, total drivers, total fares, average fare per ride and driver, and total fare for each of the three city types, providing a decent summary of our initial analysis of the data. From this, it is clear that the Urban type city contributes the bulk of each of the "total" comlumns, whearas the Rural city type tends to have the highest average fare. 

![alt_text](https://github.com/aamotz001/PyBer_Analysis/blob/main/Images/Fig2.png)
**Figure 5: Initial DataFrame for Rideshare Analysis**

We would like to view the trends over time, and to do so we first rearrange the DataFrame to be indexed by date, which is shown in Figure 7 below.

![alt_text](https://github.com/aamotz001/PyBer_Analysis/blob/main/Images/Fig3.png)
**Figure 6: DataFrame Indexed by Date**

And finally, we want to visualize the data so we include a line plot of the fare over time, over the span of a few months.

![alt_text](https://github.com/aamotz001/PyBer_Analysis/blob/main/analysis/Dev2_Plot.png)
**Figure 7: Fares VS Date (All City Types)**

## Summary & Conclusions
From the analyses presented above, we can draw the following conclusions:

1. The number of drivers in urban areas may be slightly too large, and the number of drivers in rural areas may be slightly too small. The suburban area seems to be well balanced. This is supported by the pie charts shown in Figs 3 & 4.
2. The 

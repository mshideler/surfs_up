# surfs_up

## Overview of the Analysis

The purpose of this analysis is to provide temperature data for the months of June and December in Oahu to determine if the surf and ice cream shop will be successful if open year-round.

## Results

Here are the summary statistics for temperature data from June (2010 - 2017) and December (2010 - 2016).

![temp_stats](https://github.com/mshideler/surfs_up/blob/main/Resources/temp_stats.png)

- Data collection stopped after 8/23/2017, so that's why there is a significant difference in the count between the two tables.  Ideally they should have the same amount of data for a better comparison; however, that is beyond our control.

- Most of the temperature differences between the two tables above are minor (2 - 4 degrees).

- Because the mean and median for each table are nearly identical, this says the data distribution is symmetric.

## Summary

Because the temperature differences between the two tables above are so minor, it implying that the temperature doesn't fluctuate much throughout the year. That means it shouldn't affect the surf and ice cream shop enough that it would have to close during colder months.  There may be slightly less profit but enough to keep the shop open all year; however, additional analysis might more accurately predict trends.

For example, one additional query that could be use would be to group the data by year and plot the results to see annual trends and what affects may take place by weather trends such as El Nino and La Nina.

Another query that would provide more information would be to retrieve the precipitation data for those months and grouped by year to see annual trends.  Ideally, this should be performed for all months to determine if and when Hawai'i experiences rain seasons or how often they are affected by rain due to hurricanes.
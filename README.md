# surfs_up
## Resources
- SQLite
- VS code
- Python 3.10, Jupyter notebook

## Overview of Analysis

This analysis gathered information on temperature trends on a Hawaiian island to determine if opening a surf and ice cream shop would be profitable throughout the entire year. Specifically, the months of June and December were examined by filtering the date and daily temperature from an SqLite database. This data was stored in a list to be entered into separate dataframes for a better comparison as well as calculating the summary statistics for June and December.

## Results
### June vs. December
- Below is the summary statistics of June and December temperatures on Oahu.

![june temps](https://github.com/rhiandoy/surfs_up/blob/42ace12c1a3a067371e839177adcbd3e558f752e/junetemps.png)
![dec temps](https://github.com/rhiandoy/surfs_up/blob/42ace12c1a3a067371e839177adcbd3e558f752e/dectemps.png)
- The greatest difference in weather between both months is shown within the temperature minimum. December's minimum temperature sits at 56 degrees while June's is 64 degrees. This might not make ice cream as profitable during the winter as during the summer.
- The data (count) for the month of June begins in 2010 and covers every June until 2017 whereas the December data only observes 2010 through 2016. Because of this, the data can be seen as bias and the deviation between the weather might not be as different as we have observed. 
- Below the graphs visualize the difference between the frequency of temperatures in both months. 

![june graph](https://github.com/rhiandoy/surfs_up/blob/7742007a457d7351625fc999935d409995957f8a/june_graph.png)
![dec graph](https://github.com/rhiandoy/surfs_up/blob/7742007a457d7351625fc999935d409995957f8a/dec_graph.png)

## Summary

From the data collected, the difference between temperatures in June and December are not large enough to reject the idea of opening up a surf and ice cream shop on Oahu. We could assume from this analysis that temperatures throughout the year in Oahu are steady enough to maintain a profitable business year round.

#### Additional Queries
Based on what we have learned so far in our analysis, it seems important to find additional information on the weather in Oahu before opening up the surf and ice cream shop. Since the temperatures dont show a unique difference, a query that could also be performed to help this decision would be determining the rainfall during both months. If possible, I would also gather more data that either has equal data points or another month to help draw more distinct comparisons.

# PyBer_Analysis
PyBer with Matplotlib
## Overview 
Complete an analysis for Pyber, a ride sharing business, and review data using Python skills and knowledge of Pandas, create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, create a multiple-line graph that shows the total weekly fares for each city type. Finally giving the CEO of Pyber our recommendations on addressing any disparities among the city types for the business.
## Results
### Summary DataFrame
After getting our total, rides, drivers, city types, and fares established using the group() functions, the fare per ride and per driver averages can be calculated in the summary DataFrame by city type.

![Capture.PNG](/Resources/Capture.PNG)

1. We can see from our results that the Urban city type had the highest total in all categories, but the lowest average fare per ride and driver.
2. The rural city type had the lowest total drivers which gave it the highest average fare per driver. This in turn could mean that the rural city type has more potential for revenue growth than in other city types. 

### Total Fare by City Type
From the summary DataFrame, the data was pivoted into a new DataFrame, and then grouped by weeks to show the total fares by city type.

![Capture2.PNG](/Resources/Capture2.PNG)

1. We can see on our chart that all of our city types seem to peak towards the begining of March.
2. The rural and urban types start to decline toward the end of April while the Suburban city type trended up.

## Summary
From our analysis of the results after calculating various metrics for each of the city types, here are the recommendtions for addressing any disparities among the city types:
1. Because of the rural area have less total rides PyBer could consider investing in advertising in those rural areas to increase the total rides.
2. With Urban cities having the highest total fare with the most amount of rides this would bring in the higher revenue for the company. Continuation of investments of this type is recommended to increase profits for PyBer.
3. The suburban city type being in the middle of overall performance metrics PyBer can continue to let this type perform as is, while it focuses it's efforts on the other two and boosts their performance.

<!--                                                                                           Michelle Werner (5/8/2022)-->
# Pyber Ride Share Analysis
---

<!--![alt](resources/___.png)-- >
<img src="https://github.com/miwermi/pyber-analysis/blob/main/resources/PyBer_Welcome.png" width="500" height="293" alt ="graphic: PyBer Welcome">
Pictured: Welcome to PyBer-->

# Analysis Overview:
As the a new data analyst at PyBer, a ridesharing app company, my first assignment was to do an exploratory analysis of PyBer's driving data, and specifically to isolate different types of cities (urban, suburban, and rural) and investigate differences in number of rides, number of drivers, average fare price, etc. 

This assignment also included showcasing the results by telling a compelling story about the data for each type of city, visualizing the number of drivers and riders, and fare totals and averages, through a variety of charts and graphs.

My final analysis should help stakeholders determine how to improve access and affordability for underserved areas.

## Initial Results:
To target findings to address the main comparison goals, initially data was separated into three new datasets: one for urban areas, one for suburban areas, and one for rural.  This initial separation revealed stark differences immediately and was especially obvious when charted in a scatter plot:
<br />
![alt](resources/Fig1.png)
<br />
Figure 1: Scatter plot illustrating type of fare, plotted with size relevant to ride numbers and a y-axis location representing fare price, color-coded to city type.


Box and whisker charting and pie options were also visualized. Figures 2, 3, 4, directly below, show Ride Count ranges by city type, Driver Count ranges by city type, and Fare ranges by city type:

![alt](resources/Box+Wiskers.png)
Figures 2, 3, 4 (above)

![alt](resources/PieCharts.png)
Figures 5, 6, 7 (above)

Pie chart figures 5, 6, and 7 directly above, show percentages of: Total Rides by city type, Total Drivers by city type and Total Fares by city type.

## Initial Summary:
In all of the data analyzed, it is clear that rural users are paying far higher fare rates than urban users - but that urban users are so much higher in number and in frequency of use, that the majority of the fares are coming from urban users.

<!---img src="https://github.com/miwermi/pyber-analysis/blob/main/resources/Fig2.png" width="300" height="180" alt ="graphic: PyBer Welcome">
<img src="https://github.com/miwermi/pyber-analysis/blob/main/resources/Fig3.png" width="300" height="180" alt ="graphic: PyBer Welcome">
<img src="https://github.com/miwermi/pyber-analysis/blob/main/resources/Fig4.png" width="300" height="180" alt ="graphic: PyBer Welcome"--->

<!---img src="https://github.com/miwermi/pyber-analysis/blob/main/resources/Fig5.png" width="300" height="180" alt ="graphic: PyBer Welcome">
<img src="https://github.com/miwermi/pyber-analysis/blob/main/resources/Fig6.png" width="300" height="180" alt ="graphic: PyBer Welcome">
<img src="https://github.com/miwermi/pyber-analysis/blob/main/resources/Fig7.png" width="300" height="180" alt ="graphic: PyBer Welcome"--->


## Additional Analysis & Summary Data:
After the initial analysis was complete, additional requests were made for summary data of the total rides, drivers, sum of fares, and average fare per city and driver.  Figure 8 below has these results:

![alt](resources/FinalSummary.png)
<br />
Figure 8 (above): Summary dataset with totals by city type.
<br />

<img src="https://github.com/miwermi/pyber-analysis/blob/main/resources/FinalDataset.png" width="250" height="475" alt ="graphic: Ride data from January-April, 2019" align="left" style="padding-right: 30px;">
<br /><br /><br /><br /><br />
<p style="width: 400px;">The final dataset, shown in the figure on the left (unformatted), contains the sum of the total fares per week throughout the months of January through April, 2019 - again by city type.  By summing the fares, instead of looking at the individual averages, we see just how much the frequent, smaller-fared trips of urban users add up to larger profits, and far surpass the higher fares of all other city types. 
<br />
This dataset was used to create the line graph below showing those same fares - by city type - over time.
<br /><br /><br /><br /><br />
Figures 9 & 10: Ride data from January-April, 2019. </p>
<br />

![alt](resources/PyBer_fare_summary.png)
<!---br />
Figure 9: Line chart of fare prices for all city types between January through April, 2019.--->

---
# Recommendations:
Data analysis clearly shows the disparity between city types.  Rural areas, most likely travelling farther distances, are seeing very high average fare prices, while city trips are likely short and therefore less expensive.  Some new business model must be developed if PyBer wishes to gain favorable rural use. Perhaps a membership pricing discount (for rural users wishing to travel to the city on a regular basis) could be put in place for all PyBer users, that would help to spread the cost around - or - PyBer might add an option to the app to have rideshare groups, where users could regularly travel with others in their area, sharing the cost between them, by planning trips ahead of time. Another option might be to add a feature to the app to "donate" a ride (or portion of a ride) to users - city, suburban, or rural - who may not be using PyBer due to financial hardship. Rider profiles could then apply for sliding scale rates and the donations could offset costs for those in need.

If PyBer would like to serve all of these areas with a favorable reputation and continued growth and prosperity, surely some of these and other options could be proposed in focus groups or even through a survey on the app.  Possibly people in the PyBer community might also have feedback and suggestions.



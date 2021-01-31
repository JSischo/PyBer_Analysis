# PyBer Ride Share Analysis
## Overview and Scope of the Analysis
At the request of the PyBer companies CEO, we were to conduct an analysis of ride-sharing data for a given region. The main focus of this analysis was to look at and compare different key performance indicators (KPI) for the rural, suburban and urban areas. The KPIs that we looked at were Total Fare by city type per week, total rides per area, avg fare per ride and average fare per driver per a given timeframe.

## Results
Following is a comparison and discussion of some key findings during the analysis of the rideshare data.

  ![Ride Share Summary Data](/analysis/Rideshare_summary.PNG)
  >***Key metrics for the different city types.***
 
The above summary reflects a little of what one might expect, the ***Urban*** region had the most **Total Rides, Total Drivers and Total Fares**. The second most was the ***Suburban*** cities and finally the ***Rural*** cities had the least.

However, this is flipped when we look at the Average Fare data. We see that the ***Rural*** cities had the **largest Avg. Fare Per Ride**, a little over *33%* more than the Urban cities and about *12%* more than the Suburban cities. This holds true for the **Avg. Fare per Driver** with the ***Rural*** drivers taking in about *230%* more and about *40%* more per ride than their Urban and Suburban counterparts respectively.

The graph below is charting the revenue generated per city type on a per week basis over the timeframe of interest. We also see what might be logically expected in that the region with the largest population and the largest number of drivers, the Urban area, consistently generated the most revenue. This was followed by the Suburban cities with the next largest weekly fare amounts followed by the Rural cities. Again, no real surprises there.

What we do see is a few items of note:
1. There seems to be a small upward trend in total Fares during this timeframe for the Urban areas.
2. The Suburban and Rural areas seem to be flat. So the good news here is that they don't seem to be trending down.
3. There seems to be a small common spike in Total Fares in all 3 City Types in late February. This also coincides with the highest revenue generating week of the timeframe of interest for both the Urban and Suburban regions and the second highest week for the Rural areas. 

  ![Total Fares by City Type](/analysis/PyBer_fare_summary.png)
  >***Total Fares by City Type***
  
## Summary

Based on the analysis above, we would recommend to the CEO that the company consider a few of the following items:
- The data may be indicating that there aren't enough drivers in the rural areas. Based on the laws of supply and demand, the rural drivers may be able to command a higher per ride fare than in the other regions. This might also be indicated by the flat trend in total revenues, there may not be enough drivers to meet the demand. Condidering increasing the number of drivers in these regions.
- Given that the Urban drivers are getting the smallest per ride fare, again based on supply and demand, this may indicate that there is too much completition for rides in this area. A couple of suggestions to address this:
  - Shift some Urban drivers to the Suburban or Rural areas.
  - Since the Total Revenue in the Urban areas are trending upward, they may want to hold steady for a little while and see if this is due to increased demand, which my start to increase per ride fares and thus also the fare per driver amounts.
- Given the relatively flat trend lines in the Suburban and Rural areas, consider putting together a marketing campaign to target those regions. It probaly wouldn't hurt to include the Urban regions also. This could increase the demand in all areas and start to incr the total revenues, fare per ride and fare per driver revenues. 


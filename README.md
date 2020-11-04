# PyBer_Analysis

## Overview
The purpose of this analysis is to identify how much revenue was made from rides facilited through Pyber, a hypothetical ride hailing company, using data provided between Jan 1 and April 29. I used a breakdown of city type to offer the audience composed of senior managment with a month by month trend analysis to help them locate prospective opportunities for business growth. Herein I use the month by month analysis to offer recommendations informed by the the month and town type. To conduct this analysis I used .csv files provided to me by my hypothetical employer and python/juptyer notebook.

## Results
The broadest conclusion of this analysis is that the three town types bring in the most fare/revenue in the following order:
 1. Urban
 2. Suburban
 3. Rural
 
 To see a breakdown in how these town types perform over the course of January 1st 2019 and April 29th 2019, please refer to the table below.
 
### Pyber Fare Summary by City Type
![](Pyber_fare_summary.png)

As one can see, the three town types perform distinctly different from one another, never intersecting in terms of how much in fares they are able to command. Each city type also experiences spikes and drops in fares. For example, see February to pre-march.

To see some of the summary statistics of each town type, please see the below.

### Pyber General Summary Statistics
![](Pyber_summary_stats.png)

Similarly to what we see in the graph, urban town types bring in the most in Total Fares and has the most activity in terms of Total Rides. However, the Average Fare per Ride and Average Fare per Driver are higher in Rural and Suburban towns.

## Summary
The analysis provided here presents us with a few unique windows of opportunities for analysis and business expansion. 

The first opportunity is addressing the discrepancy is Average Fare per Ride between city types. If the Average Fare per Ride for Rural or Suburban towns can be brought to the same level as Urban towns, maybe we might see a rise in the total number of riders which in turn could make up the loss in revenue from getting the average down. I would suggest pursuing this in suburban towns first as suburban towns perform more similarly to urban towns in terms of Average Fare per Ride and Total Rides.

The second opportunity is in rural towns. Rural towns bring in the least in fares but see numerous spikes throughout our data. We need look to see what contributes to those spiking dates (ie. one off rides, local events that require our services). We may even be able to offer a deal around those times, events, or trends to accenuate those spikes.

The third opportunity pertains to the sizeable variances between Q1 and Q2 for urban towns. The strongest of our three markets is the urban one and the variance may spook our investors. We should look into why we see a fairly stable Q1 and a more varied Q2.

# **Analysis – PyBer Exploritory Analysis**
## **Background Breakdown**
The goal of this project was to breakdown the metrics of the ride share data collected throughout the 2019 fiscal year, specifically covering the division between different settlement densities.
By splitting the data between the three major settlement types (Urban, Suburban, and Rural) we wanted to get a better idea of where PyBer’s user base was highest, and how to branch out into lower traffic areas.
Using this base metric, we further sought to measure the comparison between the total of each settlement type, and the average fares in each category with the intent of using these numbers to adjust marketing resources as necessary.
## **Results**
In terms of numbers, the overwhelming majority of riders and drivers are in Urban areas. It’s understandable – not only is public transport more readily available in cities and other urban centers, but the population density is overall higher than either suburban or rural areas, leading to a higher percentage of people using shared transport. The more condensed nature of urban areas also leads to a larger number of people lacking personal transport.
- The total number of Urban rides was 2.6 times higher than Suburban rides (1,625 vs 625) and 13 times higher than Rural rides (1,625 vs 125). Meanwhile, Suburban rides were 5 times higher than Rural (625 vs 125).
- Drivers also see a large divide – there were 2,405 Urban drivers in 2019, 4.9 times higher than the number of Suburban drivers (490), and 30.83 times higher than Rural drivers (78), while there were 6.28 times more Suburban drivers than Rural drivers.
- Interestingly enough, profit from fares didn’t suffer quite the same level of disparity; the total fares in Rural areas ($4,330) were only 9.21 times less than Urban areas ($39, 850), and 4.47 times less than Suburban areas ($19,350).
  - A metric which could potentially clarify this data this would be distance travelled. While cities can be large, rural areas tend to be more spread out, increasing travel time, distance, and fare price.
- Much like the fare profit didn’t show as much spread as the number of rides and number of drivers, the Average Fare per Ride was grouped fairly close together. Rural areas had the highest Average Fare per Ride at $34.62 per ride, which is 1.12 times higher than Suburban areas ($30.97), and 1.41 times higher than Urban areas ($24.53).
  - With a range of just over ten dollars, the data shows that while Rural areas are more profitable on a by-ride basis, they only account for about 6.81% of the profits in 2019.
- Average Fare per Driver has a little bit larger spread – Rural areas ($55.49) are roughly 3.35 times higher than Urban areas ($16.57), and 1.4 times higher than Suburban areas ($39.50), which are 2.38 times higher than Urban areas.

A comprehensive look at the data shows that while *fares* may be lower in Urban areas than Suburban or Rural areas, the use of ride sharing is much higher in Urban areas, leading to higher profits. While this can partially be addressed by increasing the number of drivers in the other two settlement categories, there is no data in the provided material to suggest an increase in rides or profits from either of these areas. More data and careful observation might offer more insights.
## **Summary**
Based on the data summary and the line graph (see chart below) depicting the trends of the first four months of 2019, I have a few ideas on how to strengthen PyBer’s integration into Rural and Suburban communities.
1. Hire more drivers. While there is no definite way of knowing whether more drivers would increase the number of rides, a deficit in drivers makes PyBer’s use as a ride share a limited commodity. As PyBer isn’t a luxury service, having a scarcity encourages Suburban and Rural areas to rely on competitors – which can be a death sentence, particularly in Rural areas .
2. Focus marketing on Rural and Suburban communities. Many app-based services gain momentum and recognition through advertising and branding; in the fast-paced world of social-media trends and hype, media presence and marketing can make or break a brand. Communities in less urban areas are rarely the focal point of company outreach. By building up the recognition of PyBer within non-urban areas, we encourage people to use the service.
3. Look into deals or promotions. In both Average Fare metrics, Rural areas are a minimum of 10 dollars more expensive Urban areas; and, unfortunately, as a service whish is neither billed as luxury nor integrated into the community, PyBer will struggle to survive. Suburban communities are more accessible, and as shown in the Trend Tracking chart below (see Figure 1.1), there is an upswing in the Suburbs as April fades into May. In comparison, April was the month with the highest fare spike in the graph, reaching the $500 benchmark before slowly dropping. Urban areas see a similar trend, though it’s far subtler, and is still far higher than the lowest spike at the beginning of April, where fares dipped below the $2,000 mark, the lowest point since mid-January.
## **Supplemental Data**
- City name and population density. This will give us a better idea of how popular PyBer is within a community and allow us to shuffle resources to more or less populated areas as necessary.
- The trends across winter and mid-summer. The line-graph tracking the first four months of 2019 is interesting, in that the marker for January is the lowest fare point for both Urban and Suburban communities. More data would be useful, as it would be expected that winter would have a higher number of rides, and thus higher fare profits, across all communities due to the weather. Mid-summer is a timeframe of interest for similar reasons; Late June into early August tends to be the hottest portion of the year in the northern hemisphere, which would theoretically make the use of an air-conditioned ride-share more appealing.

Table 1.1  PyBer Summary Table

![PyBer_summary_df](https://github.com/ltkdobbs/pyber_analysis/blob/main/analysis/PyBer_summary_df.png)


Figure 1.1 PyBer Trend Tracking (Jan-April)
![PyBer_fare_sumary](https://github.com/ltkdobbs/pyber_analysis/blob/main/analysis/PyBer_fare_summary.png)

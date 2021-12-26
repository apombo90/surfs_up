# surfs_up
## Project Overview
Analysis done to determine if a surf and ice cream shop business is sustainable year-round. The main goal was to provide insight into the weather patterns of a specific location on Oahu by generating summary statistics of the temperature for the months of June and December from 2010 to 2017. These statistics will help the investors determine if this location is a good fit for their business. 

The analysis was done by writing queries that filtered the desired data, converting those queries to a list and then to a DataFrame. After the DataFrame was created I used .describe() to calculate the summary statistics to present to the investors.

## Resources
- Data source: hawaii.sqlite
- Software: Python, Pandas functions and methods, and SQLAlchemy.

## Results
- The average temperature for the month of June is 75°F whereas for December is 71°F.
- The minimum temperature reported for the month of June was 64°F while December had its lowest at 56°F.
- The maximum temperature for both months is slightly different with June reporting a max of 85°F and December reporting a max of 83°F. 

![image](https://user-images.githubusercontent.com/91766276/147394946-4d3ba55e-1732-4d46-9f53-da0d49c9936b.png) ![image](https://user-images.githubusercontent.com/91766276/147394952-4d7ee47e-6f79-4340-8134-7d189c1c6d92.png)

## Summary

December is colder than June, however when we compare both temperature histograms and the 25th percentile of the data in the statistics summary, we can see that the  75% of the temperature data for June and December is higher than 73°F and 69°F respectively. This makes Oahu a perfect location to open a surf and ice cream shop business due to its warm temperature all year around. 

![Screenshot 2021-12-25 184621](https://user-images.githubusercontent.com/91766276/147395633-6c2830a2-e297-49b8-b681-cc69628c9ec1.png) ![Screenshot 2021-12-25 184922](https://user-images.githubusercontent.com/91766276/147395641-6245fe12-6565-4605-a996-4edd0a9356fb.png)

It was also important to consider the amount of precipitation for both months, for this I performed additional queries to gather more weather data and provide more insights to the investors. Precipitation was very low for June and December between 2010 and 2017, 75% of the June's precipitation data is lower than 0.12 and 75% of the December's data is lower than 0.15. Additionally, the average precipitation for the month of June from 2010 to 2017 was 0.14 whereas for December was 0.22. 

![image](https://user-images.githubusercontent.com/91766276/147396045-d05257f0-ea1a-468d-978a-b5540fb018ed.png) ![image](https://user-images.githubusercontent.com/91766276/147396053-6499c00b-f2d6-4afa-b99d-8f1695202b92.png)

Finally, we can determine that even though December is colder and has more amount of precipitation it's not that different from June and that indicates that the temperature and precipitation all year around is perfect to open the surf and ice cream shop business in Oahu.



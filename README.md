# surfs_up
## Project Overview
An analysis of weather patterns in Hawaii as part of the investigatory process before opening a surf / ice cream shop in Hawaii.
### Purpose
The analysis on weather in Hawaii will assist in determining how viable the proposed business will be.  We hope to determine how favorable the weather is for the type of business we hope to open and present this information to potential investors.  The analysis should calm any possible doubts about the potential success of the business due to unfavorable weather.
## Resources
-	Data Source: Hawaii.sqlite
-	Software: Python 3.7, Jupyter Notebook v. 6.1.4, SQLite v. 3.27.2
## Results
- The most significant difference between the two months is the minimum temperature.  June has only gone down to 64°, but December has gone down to 56°.  It is an important figure because at that point the temperature is a deterrent for both surfing and ice cream and will affect the business.
- The next difference is also in the lower ranges of temperatures.  The first quartile is at very comfortable 73° in June but only goes up to 69° in December.  These lower temperatures are crucial to see because they will affect the business the most.  
- December has a larger range of temperatures and a slightly higher standard deviation.  This tells us temperatures in December fluctuate more than they do in June, and it will be important to keep in mind temperatures in December are less consistent.
<img src="Summary_statistics/June_temps.png" width="200" height="300"/>  <img src="Summary_statistics/December_temps.png" width="200" height="300"/>

   

## Summary
Overall, temperatures appear very stable throughout the year, with very small differences between June and December.  The temperatures are also relatively comfortable, with an average temperature of 75° in June and 71° in December, and it does not get extremely hot as the maximum temperature was 85°.  However, December has a minimum temperature of 56° which I believe the average person would say is too cold for surfing.  It will be important to keep in mind that although temperatures are typically comfortable even in the winter months, there are occasions where the temperature can dip low enough to negatively affect the shop.  I would conclude that temperatures are conducive to comfortable surfing conditions year-round and will not pose an obstacle for the surf / ice cream shop. 
- Rain is another critical weather condition we need to analyze when discussing the surf shop.  Rain is a real obstacle for surfing and could dampen business, especially in a tropical environment like Hawaii’s.  We should alter our earlier queries on precipitation data to see how it changes throughout the year and see if there are periods of heavy rain where business will slow down.
- We should also do a temperature and rain analysis by weather station.  This will help determine if there are areas on the island that are better or worse for the business.  If we determine certain stations are better or worse for the shop, we can then pinpoint the locations using the coordinates data we have for the stations.
- One final query that would be beneficial would be to find the average of the number of days per year where temperatures dip below a certain threshold like 65° for example.  This will give us more incite into how often there are days where temperature can affect the business. 

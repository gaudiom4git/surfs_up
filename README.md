# Surfs Up Analysis
Module 9 Challenge

## Overview of Project
The objective of this project was to learn how to connect and extract information from a SQLite SQLAlchemy database.
Temperature and precipitation measurements were taken at select weather stations.  A potential business
man, W. Avy, wanted to open a surf and ice cream shop and wanted to make sure that the potential location 
in Hawaii had weather that would support the business.

After extracting the information from the database, we used Numpy to produce statistics including mean / average, 
max/min, and median temperatures for the area.   Data extracted and analyzed were for the months of June and 
December (multiple years).

## Results
Here is a side by side glance of the statistics for June and December:
![June Dec Stats](https://github.com/gaudiom4git/surfs_up/blob/main/Resources/June%20and%20December%20Stats.png)

Three key differences in weather between June and December
*  There were 1700 observations in June versus 1517 observations in December. 
*  Min 15 degrees lower than average in Dec.   Min is 10 degrees lower than avg in June
*  Standard deviation across the temps in December are much wider than in June.

## Summary
### High level summary of results 

Overall, the weather in Hawaii seems very consistent between June and December.   Average temperatures for both 
months were 75 for June and 71 for December, so a 4 degree difference.  Even the max temperatures for both 
were only 2 degrees apart.  However, the minimum temperatures are a concern.   56 degrees in December may turn
out lower crowds coming out to surf resulting in lower potential customers in the shop.

### Two additional queries to gather more weather data for June and December

*  A query to gather precipitation totals for June and December can also help with determining crowds in the
area for those months.   This can help with planning labor and materials.   Can also be a factor in deciding
if this business location will be a viable location.

*  Another helpful query would be to get temperature and precipitation by day of the week.   This can also help
with planning business hours as well as labor and materials resource planning.


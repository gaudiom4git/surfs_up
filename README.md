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
High level summary of results 

Two additional queries to gather more weather data for June and December
ImmutableColumnCollection(measurement.id, measurement.station, measurement.date, measurement.prcp, measurement.tobs)

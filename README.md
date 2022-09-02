# Surfs_up

## Overview of Surfs Up Analysis

The purpose of this analysis is to review a dataset pertaining to weather conditions that has been stored in a SQLite database.  The database can be obtained via the link below:

LINK TO Hawaii.sqlite

The overall aim of this project is to provide insight regarding the weather in Oahu, Hawaii prior to construction of a new surf and ice cream shop.  The investor is most interested in temperatures during the months of June and December in order to determine if the shop can be sustainable all year.

In order to explore the data in the SQLite database, SQLAlchemy was used to connect and generate queries to pull the necessary information needed for our analysis. Jupiter notebook was used to import dependencies and create the commands to pull the data from the SQLite database.

## Results

The summary statistics for Oahu, Hawaii during the months of June and December are presented below:

June Statistics for Temperature – LINK TO IMAGE OF JUNE RESULTS

December Statistics for Temperature – LINK TO IMAGE OF DECEMBER RESULTS

1. Based on count of 1,700 temperatures in the month of June over the course of seven years, the mean temperature was about 75oF, minimum of 64oF degrees, and maximum of 85oF degrees.  Based on count of 1,517 temperatures in the month of December over the course of seven years, the mean temperature was about 71oF, minimum of 56oF degrees, and maximum of 83oF degrees.

2. The December temperature appears to demonstrate a greater range than those observed during June.  This was attributed to a larger difference between the maximum and minimum temperatures during the month of December compared to June. 

3. There are 183 more temperatures analyzed for June statistics than December statistics for the seven year period, however the amount of variance between the two data sets was observed to be relatively similar between the two months (standard deviation of 3.26 for June vs. standard deviation of 3.75 for December).

## Summary

In summary, even though temperatures recorded in December seem to vary more than those of June, December would still provide appropriate weather conditions for both surfing and demand in ice cream. The average temperatures in June and December only differ by approximately 4oF.  December's median temperature, with the highest frequency recorded across a span of the seven years analysed, was about 72oF.  This temperature was at least double the frequency of the next highest recorded temperatures, 75oF and 67oF respectively. It is recommended that the company open the surf and ice cream shop based on these preliminary findings.

To gain further understanding of the weather in Oahu, Hawaii, two additional analyses were completed.  The findings of these analyses in included below.

Analysis of Precipitation

The analysis focuses on the temperature and rainfall from six different weather stations On Oahu, Hawaii from 2010-2017 and June and December specifically.  The results of this analysis is depicted below.
INSERT IMAGE OF PRECIPITATION RESULTS
o There are less data points for December (1405 data points) than June (1574 data points).
o There was a greater range for rainfall quantity in December than June.
o June’s mean rainfall was approximately 0.13 inches and the median was about 0.02 inches.
o December’s mean rainfall was approximately 0.21 inches and the median was about 0.03 inches.
o Maximum rainfall in December was 6.42 inches and 4.43 in June.
o Minimum rainfall was 0 inches for both June and December. 
Analysis by Weather Station

Analysis of June and December temperatures by weather stations was completed in order to help determine the optimal geographically location for the shop within Oahu.  

INSERT IMAGE OF STATION RESULTS


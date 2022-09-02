# Surfs_up

## Overview of Surfs Up Analysis

The purpose of this analysis is to review a dataset pertaining to weather conditions that has been stored in a SQLite database.  The database can be obtained via the link below:

[Hawaii Database Link](https://github.com/jbowman86/Surfs_up/blob/d97e27cbc367f2983bf908eb2fc17ba4b529e5fd/hawaii.sqlite)

The overall aim of this project is to provide insight regarding the weather in Oahu, Hawaii prior to construction of a new surf and ice cream shop.  The investor is most interested in temperatures during the months of June and December in order to determine if the shop can be sustainable all year.

In order to explore the data in the SQLite database, SQLAlchemy was used to connect and generate queries to pull the necessary information needed for our analysis. Jupiter notebook was used to import dependencies and create the commands to pull the data from the SQLite database.

## Results

The code for analysing the temperature of Oahu, Hawaii for the months of June and December can be found via the following link:

Code for weather analysis - [Surf's Up Code](https://github.com/jbowman86/Surfs_up/blob/6cda79aa068b15daf57a6a85d776523e42dbf18b/SurfsUp_Challenge.ipynb)

The summary statistics for Oahu, Hawaii during June and December are presented below:

June Statistics for Temperature 


![](https://github.com/jbowman86/Surfs_up/blob/1c3668b1f7cea037ba945d1e67f7b085a4eca46d/Resources/June_Temp_Stats.png)

December Statistics for Temperature  

![](https://github.com/jbowman86/Surfs_up/blob/1c3668b1f7cea037ba945d1e67f7b085a4eca46d/Resources/Dec_Temp_Stats.png)


1. Based on a count of 1,700 temperatures in the month of June between the years 2010-2017, the mean temperature was about 75 degrees Fahrenheit, minimum of 64 degrees Fahrenheit, and maximum of 85 degrees Fahrenheit.  Based on a count of 1,517 temperatures in the month of December from 2010-2017, the mean temperature was about 71 degrees Fahrenheit, minimum of 56 degrees Fahrenheit, and maximum of 83 degrees Fahrenheit.

2. The December temperatures appear to demonstrate a greater range than those observed during June.  This was attributed to a larger difference between the maximum and minimum temperatures during the month of December compared to June. 

3. There are 183 more temperatures analyzed for June statistics than December statistics for the time period between 2010-2017.  However, the amount of variance between the two data sets was observed to be relatively similar between the two months (standard deviation of 3.26 for June vs. standard deviation of 3.75 for December).

## Summary

In summary, even though temperatures recorded in December seem to vary more than those of June, December would still provide appropriate weather conditions for both surfing and demand in ice cream. The average temperatures in June and December only differ by approximately 4 degrees Fahrenheit.  December's median temperature, with the highest frequency recorded across a span of the seven years analysed, was about 72 degrees Fahrenheit.  This temperature was at least double the frequency of the next highest recorded temperatures, 75 degrees Fahrenheit and 67 degrees Fahrenheit respectively. It is recommended that the company open the surf and ice cream shop based on these preliminary findings.

To gain further understanding of the weather in Oahu, Hawaii, two additional analyses were completed.  The findings of these analyses are included below.

### Analysis of Precipitation

This analysis focuses on the rainfall experienced in Oahu, Hawaii during the months of June and December for the time period of 2010-2017.  The results of this analysis is depicted below.

![](https://github.com/jbowman86/Surfs_up/blob/1c3668b1f7cea037ba945d1e67f7b085a4eca46d/Resources/June_Dec_Precipitation_Stats.png)

    o There are less data points for December (1405 data points) than June (1574 data points).
    o There was a greater range for rainfall quantity in December than June.
    o June’s mean rainfall was approximately 0.13 inches and the median was about 0.02 inches.
    o December’s mean rainfall was approximately 0.21 inches and the median was about 0.03 inches.
    o Maximum rainfall in December was 6.42 inches and 4.43 in June.
    o Minimum rainfall was 0 inches for both June and December. 

### Analysis by Weather Station

Analysis of June and December temperatures by weather stations was completed in order to help determine the optimal geographically location for the shop within Oahu.  Due the large number of weather stations (over 32,000), a more comprehensive analysis is recommended to determine the best location for the new shop.  At this time, this is beyind the scope of the current analysis

![](https://github.com/jbowman86/Surfs_up/blob/1c3668b1f7cea037ba945d1e67f7b085a4eca46d/Resources/Station_Temps_June_and_Dec.png)

In summation, both the percipitation and weather stations analyses concur that it is recommended to open the new shop in Oahu, Hawaii.

# PyBer_Analysis

## Project Challenge Overview

Given the task to perform exploratory analysis for PyBer to help improve access to ride-sharing services and determine affordability for neighborhoods.  The following deliverables for the analysis are:

- Technical Analysis Deliverable 1: A DataFrame that summarizes the key metrics for the ride-sharing data by city type.
- Technical Analysis Deliverable 2: A multiple-line chart, with one line for each city type, that shows the sum of the fares for each week.
- Delivering Results: A written report of your results.

## Resources

- Data Sources: city_data.csv, ride_data.csv
- Software: Python 3.7.6 ('base':conda), Visual Studio Code 1.46.1, Juypter Notebook


### Technical Analysis Deliverable 1:

To create the summary DataFrame, follow these steps:

  1. From the merged DataFrame get the total rides, total drivers, and total fares for each city type using the groupby() function on the city type.
  2. Calculate the average fare per ride and the average fare per driver for each city type.
  
To format the summary DataFrame, follow these steps:

1. Delete the index name.
2. Create the summary DataFrame with the appropriate columns, and apply formatting where appropriate.

## Summary

The purpose of this assignment was to create a summary dataframe of the key metrics for the ride sharing data and to show the relationship between each city type (urban, suburban, rural)  and total fares.  An analysis was performed from January to early May 2019.  Analyze the data to create the technical deliverables by inspecting the data first, merged data set into one, performed calculations, and created a summary dataframe that was used to build a chart. Created the summary dataframe by calculating the key metrics which were the total rides, total drivers, and total fares.  After the totals were found, I calculated the average fare per ride and the average fare per driver.  

![](analysis/Fig9.PNG)
 
As shown in the table, the Rural area had the highest average fare per ride out of the three areas.  Urban being the lowest.  The chart visualizes the fare($USD) from January 2019 to the beginning of May.  

![](analysis/Fig8.png)

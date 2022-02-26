# Surfs_Up
Module 9 Surf's Up with Advanced Data Storage and Retrieval
###### Project Overview
- Using Python, Pandas functions and methods, and SQLAlchemy, filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June and December.
- Convert temperatures to a list, create a DataFrame from the list, and generate the summary statistics.
###### Results
- June total count of items in dataset = 1700 
  - Mean = 74.9 
  - Min = 64.0 
  - Max = 85.0
  - Standard Deviation = 3.25

![june_df.describe_d1](https://github.com/robyndook/Surfs_Up/blob/d6dbbc602356c8c54aee2e31584bd5eabb96fc5d/Analysis/june_df.describe_d1.png)

- December total count of items in dataset = 1517 
  - Mean = 71.0
  - Min = 56.0
  - Max = 83.0
  - Standard Deviation = 3.75

![dec_df.describe_d2](https://github.com/robyndook/Surfs_Up/blob/d6dbbc602356c8c54aee2e31584bd5eabb96fc5d/Analysis/dec_df.describe_d2.png)

- Comparrison 
  - Mean (June 74.9, December 71.0) =  December decreased by 3.9
  - Min (June 64.0, December 56.0) =  December decreased by 8  
  - Max (June 85.0, December 83.0) =  December decreased by 2
  - Standard Deviation (June 3.25, December 3.75) =  December increased by .5

- **Additional Query One**
  - June Temps Histogram

![june_temps](https://github.com/robyndook/Surfs_Up/blob/d6dbbc602356c8c54aee2e31584bd5eabb96fc5d/Analysis/june_temps.png)

  - December Temps Histogram

![dec_temps](https://github.com/robyndook/Surfs_Up/blob/d6dbbc602356c8c54aee2e31584bd5eabb96fc5d/Analysis/dec_temps.png)

- **Additional Query Two**
  - Monthly_df from 9/2016 to 8/2017 so min and max temps
  
![monthly_df](https://github.com/robyndook/Surfs_Up/blob/e66784ae093711e8211a11587b4ccc135d8c9eef/Analysis/monthly_df.png)  
  
  - Average minimum temp for one year = 58.0
  - Average maximum temp for one year = 87.0  

###### Summary
The dataset shows the June temps are slightly higher than December temps, but insignificant.

Comparing the June and December weather patterns, the temperatures are fairly close. The temperature data is not skewed for either month and is reasonably similar. The dataset supports opening a Surf and Ice Cream shop year-round.

Further comparison for a full year from 9/2016 to 8/2017 shows temps do not drop below 58.0 throughout the year. The additional dataset also supports opening a Surf and Ice Cream shop year-round.



<!--
Overview of the statistical analysis:

The purpose of the analysis is well defined. (3 pt)
Results:

There is a bulleted list that addresses the three key differences in weather between June and December. (6 pt)
Summary:

There is a high-level summary of the results and there are two additional queries to perform to gather more weather data for June and December. (5 pt)
-->

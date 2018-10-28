# Udacity Data Analyst Nanodegree Program - Term One
## Project One Title : Explore Weather Trends
In this project, I analyzed local and global temperature data and compared the temperature trends where I live to overall global temperature trends.

## Database schema
Given database schema has three tables, namely:
- city_list - List of cities and countries in the database. Look through them in order to find the city nearest to you.
- city_data - Average temperatures for each city by year (ºC).
- global_data - Average global temperatures by year (ºC).

## Project completion Steps
1. Written SQL query to extract city-level data and exported to CSV file.
![](https://github.com/rbpal/Udacity_DAND_2018_TermOne_Project_1_Explore-Weather-Trends/blob/master/images/project-01-Explore-Weather-Trends-world-data-extraction.PNG)

1. Written SQL query to extract my city Philadelphia data and exported to CSV file.
![](https://github.com/rbpal/Udacity_DAND_2018_TermOne_Project_1_Explore-Weather-Trends/blob/master/images/project-01-Explore-Weather-Trends-city-data-extraction.PNG)

1. Written SQL query to extract the global data and exported to CSV file.
![](https://github.com/rbpal/Udacity_DAND_2018_TermOne_Project_1_Explore-Weather-Trends/blob/master/images/project-01-Explore-Weather-Trends-global-data-extraction.PNG)

1. Open CSV file using Pandas


1. Created a line chart(Python's Seaborn Visualization Library) comparing  my city Philadelphia temperatures with the global temperatures.
![](https://github.com/rbpal/Udacity_DAND_2018_TermOne_Project_1_Explore-Weather-Trends/blob/master/images//project-01-Explore-Weather-Trends-Global-Vs-Philadelphia.PNG)

1. Following observation made about the similarities and differences between the world averages and your city’s averages, as well as overall trends
	+ The city, Philadelphia/USA temperatures are rising at a higher rate in comparison to Global temperature trends.
	+ Overall trend from last few centuries show that temperatures are rising and Earth getting hotter.

## Important files and Notes
Following CSV files were used to complete the project
- weatherTrends-global_data.csv
- weatherTrends-city_data.csv
- weatherTrends-city_data_philadelphia.csv


## Author
* **Rajendra B Pal** - [Udacity DAND 2018 TermOne Project 1: Explore Weather Trends](https://github.com/rbpal/Udacity_DAND_2018_TermOne_Project_1_Explore-Weather-Trends)


## Acknowledgments
- https://www.youtube.com/watch?v=4EXNedimDMs
- https://www.datacamp.com/community/tutorials/seaborn-python-tutorial?utm_source=adwords_ppc&utm_campaignid=1565261270&utm_adgroupid=67750485268&utm_device=c&utm_keyword=&utm_matchtype=b&utm_network=g&utm_adpostion=1t1&utm_creative=295208661511&utm_targetid=dsa-473406580275&utm_loc_interest_ms=&utm_loc_physical_ms=9005849&gclid=EAIaIQobChMI2J2Mt7ap3gIVgozICh1NSQkEEAAYASAAEgKzHfD_BwE

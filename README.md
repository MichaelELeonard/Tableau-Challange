# Tableau Challenge - Citi Bike Analysis

<img src="ReadME Pictures/Opening Pic.png" width="700" height="700">


### Tableau Presentation

* Link to Tableau Storyboard: https://public.tableau.com/app/profile/michael.leonard4092/viz/TableauChallengeWeek18v2/May-July2023BikeStationsAnalysis?publish=yes

## Background

As the new lead analyst for the Citi Bike Program (https://citibikenyc.com/homepage, and oversee the largest bike sharing program in the United States. One of my responsibilities in this new role is to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, so my first task on the job is to build a set of data reports to provide the answers to key business needs to drive decision making. 

In this initial submission I will be examining data covering the summer months of May, June & July from 2023 and looking to identify: 
•	The top ten must successful Citi Bike Stations and identify why these specific locations have been successful.
•	Locate ten stations that have strong growth potential and identify strategies that may help them achieve their full potential.        

## Data Preparation
To prepare the data for analysis, the May, June & July data files were downloaded from https://www.citibikenyc.com/system-data.  Each table was imported into a Pandas data frame for cleaning and the null values were removed. Finally, the three individual data frames were joined using the pd.concat function. The code can be viewed by clicking the following link: https://github.com/MichaelELeonard/Tableau-Challange/blob/main/CitiBikeCleaningCode.ipynb

## All the Citi Bike Locations sized by Rides Starts:    

<img src="ReadME Pictures/All Stations by Size.png" width="900" height="700">

## The top ten must successful Citi Bike Stations 

The top ten most successful Citi Bike Stations bike stations are listed below. Traditional bike usage significantly outnumbers electric bikes with peak check out times being 8am and 6pm. Another contributing factor to these specific locations’ success appears to be the station location, with stations near the scenic views of the Hudson River and downtown Jersey City locations proving to be popular with our customers.


<img src="ReadME Pictures/Top 10 Bike Stations.png" width="700" height="500">

<img src="ReadME Pictures/Top 10 Bike Stations by Month & Bike Type.png" width="700" height="500">

<img src="ReadME Pictures/Top 10 Bike Stations Map.png" width="700" height="500">

<img src="ReadME Pictures/Top 10 Bike Stations Peak Times.png" width="700" height="500">



## Map



## 10 Most Popular Stations

## High Growth Opportunity Stations    



<img src="ReadME Pictures/10 Growth Opportunity Stations by Month and Bike Type.png">
<img src="ReadME Pictures/10 Most Popular Dashboard.png">
<img src="ReadME Pictures/All Stations by Size.png">
<img src="ReadME Pictures/Bike Stations with Strong Growth Opportunity Map.png">
<img src="ReadME Pictures/Most Popular Starting Points.png">
<img src="ReadME Pictures/Strong Growth Opportunity Dashboard.png">
<img src="ReadME Pictures/Top 10 Bike Stations Map.png">
https://github.com/MichaelELeonard/Tableau-Challange/blob/main/CitiBikeCleaningCode.ipynb





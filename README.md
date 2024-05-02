# Citi Bike Analysis

<img src="ReadME Pictures/Opening Pic.png" width="700" height="700">


## Tableau Presentation

Link to [Citi Bike Tableau Storyboard](https://public.tableau.com/app/profile/michael.leonard4092/viz/TableauChallengeWeek18v2/May-July2023BikeStationsAnalysis?publish=yes)

<br>

## Background

As the new lead analyst for the [Citi Bike Program](https://citibikenyc.com/homepage), I oversee the largest bike sharing program in the United States. One of my responsibilities in this new role is to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, so my first task on the job is to build a set of data reports to provide the answers to key business needs to drive decision making. 

In this initial submission I will be examining data covering the summer months of May, June & July from 2023 and looking to identify: 
<br>
<br>
•	The top ten must successful Citi Bike Stations and identify why these specific locations have been successful.
<br>
•	Locate ten stations that have strong growth potential and identify strategies that may help them achieve their full potential.        

<br>

## Data Preparation
To prepare the data for analysis, the May, June & July data files for 2023 were downloaded from [Citi Bike Data](https://www.citibikenyc.com/system-data).  Each table was imported into a Pandas data frame for cleaning and the three individual data frames were joined using the pd.concat function. The code can be viewed [here.](https://github.com/MichaelELeonard/Tableau-Challange/blob/main/CitiBikeCleaningCode.ipynb)

<br>

## All the Citi Bike Locations sized by Rides Starts:    

<img src="ReadME Pictures/All Stations by Size.png" width="900" height="700">

<br>

## The Top Ten Most Successful Citi Bike Stations 

The top ten most successful Citi Bike Stations bike stations are listed below. Traditional bike usage significantly outnumbers electric bikes and daily peak check out times are 8am and 6pm. A strong contributing factor to these locations’ success appears to be the station location, with stations near the scenic views of the Hudson River and downtown Jersey City locations proving to be popular with our customers.

<br>

<img src="ReadME Pictures/Top 10 Bike Stations.png" width="700" height="500">

<img src="ReadME Pictures/Top 10 Bike Stations Map.png" width="700" height="500">

<img src="ReadME Pictures/Top 10 Bike Stations Peak Times.png" width="700" height="500">

<br>

## High Growth Opportunity Stations    

Ten high growth opportunity stations are outlined in the charts below. These locations were identified as having similar location traits as the higher performing stations. In addition to having scenic views of the Hudson River and downtown Jersey City locations, [Liberty State Park](https://visitnj.org/article/liberty-state-park) located just south of downtown Jersey City has been identified as a growth opportunity location. This 1,212 acre park offers a two-mile promenade titled the ‘Liberty Walk’, links to multiple picnic areas, interpretive center and terminal, and sweeping views of the Hudson River and Manhattan skyline.  There are ferry rides available to the Statue of Liberty and Elles Island, as well as boating and canoeing opportunities. With a new ad campaign and incentive program for our membership and casual riders, our ten high growth opportunity stations will see increased customer traffic. 

<br>

<img src="ReadME Pictures/10 High Growth Stations.png" width="700" height="500">

<img src="ReadME Pictures/10 Growth Opportunity Stations by Month and Bike Type.png" width="700" height="500">

<img src="ReadME Pictures/Bike Stations with Strong Growth Opportunity Map.png" width="700" height="500">

<img src="ReadME Pictures/Liberty State Park.png" width="700" height="500">





## Conclusion
The Citi Bike Program in the New York/New Jersey area is already the largest bike sharing program in the United States, but we continue to explore new opportunities for growth. With a new ad campaign and incentive program focused on growth oppertunities, Citi Bike will continue to be the leading bikeshare program in the nation.

<br>

<img src="ReadME Pictures/Closing Pic.png" width="900" height="500">

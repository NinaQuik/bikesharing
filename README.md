# Bikesharing

## Overview

This project is an analysis of NYC CitiBike bikesharing data, using Tableau to explore the viability of opening a similar bike sharing company in Des Moines, IA.

In this analysis, Tableau is used to:

 - Show the length of time that bikes are checked out for all riders and genders	
 - Show the number of bike trips for all riders and genders for each hour of each day of the week
 - Show the number of bike trips for each type of user and gender for each day of the week
 - Map the most popular starting and ending locations for bike trips in NYC
 - 
### Tools:
Tableau Public,
Python 3.7.11,
Jupyter Notebook,
Pandas Library

### Data
CSV file containing bike share information for the month of August, 2019 in New York City.

## Results

### **Public Tableau link : [Tableau_Bikeshare_Challenge](https://public.tableau.com/app/profile/nina.quick/viz/BikeshareChallenge_16478351821400/NYCBikshare?publish=yes)**

There were over 2.3 million NYC CitiBike trips in the month of August 2019.

<img src="https://github.com/NinaQuik/bikesharing/blob/main/Resources/summary.png" width="600" height="500">

### Length of Rides

Most rides were of short duration and less than 30 minutes in length.  Males clearly make up the majority of riders, but ride duration is fairly consistent regardless of gender.

<img src="https://github.com/NinaQuik/bikesharing/blob/main/Resources/checkout_times.png" width="500" height="600">

### Customer Types

Subscribers comprise over 81 percent of all bikeshare rides, highlighting that there is a regular and predictable source of revenue. 

<img src="https://github.com/NinaQuik/bikesharing/blob/main/Resources/customer_type.png" width="600" height="600">

### Trips by Weekday

Weekdays are busiest, with male subscribers riding Monday through Friday.   Customers (non-subscribers) ride more often on weekends, and unspecified genders tend to be customers. It's possible that the subscriber registration process requires gender identification, whereas customer rides are more anonymous. It appears that male commuters are the bread and butter of bikeshare rides in August despite the generally favorable weather for weekend tourist bike rides at this time of the year.

![weekday](/Resources/gender_weekday.png)

Commuting hours between 7-9 am and 5-7 pm on weekdays are the most popular times for rides.  Most bikes are clearly used for commuting purposes.

![gender_hours](/Resources/gender_hours.png)

### Peak Locations
The most popular starting locations are clustered around busy Manhattan, with many popular spots near train stations like Grand Central and Penn Station.

![top_start_locs](/Resources/top_starting_locations.png)

The most popular ending locations are similarly located.

![top_ending](/Resources/top_ending_locations.png)

## Summary

To further analyze the given dataset of bike share rides in NYC, I would:

- Plot starting location to ending location and determine most popular routes.
- Compare duration of bike ride to distance covered.
- Overlay maps with bike lanes and bike friendly corridors.

Although this analysis visualizes bike ride data for NYC, I would be hesitant to apply the same metrics to Des Moines. The two cities are considerably different demographically and many factors should be considered such as:
- Bike Infrastructure
- Safety
- Traffic and congestion
- Length and distance of commutes
- Weather
- Affordability of transportation and parking
- Competition and availability of other bike-sharing programs
- Terrain
- Number of bike shops per population (to gauge enthusiasm for bike riding)

In NYC, the CitiBike program appears to be popular based on the largely male subscriber commuter base. It is unclear if the same conditions would apply to Des Moines, IA.


# bikesharing

## Overview of Project 

### Purpose

The purpose of this project is to gain insights into bikesharing trends in New York City during late summer by creating, and analyzing visualizations, or vizzes, using Tableau Public.\
Data is obtained for August 2019 from citibikes, a bike sharing company in NYC.\
The vizzes are then presented in dashboards, which are used to create a story. 

### Resources used
- Data : "201908-citibike-tripdata.csv.zip" from "https://s3.amazonaws.com/tripdata/index.html"

- Software : Tableau Public 2021.2

## Results

Tableau Public link :
[link to dashboard] https://public.tableau.com/views/NYCCitibikeChallenge_16267935620380/CitiBikeUseinNYCSummers?:language=en-US&:display_count=n&:origin=viz_share_link

Following is a description of the visualizations from the above linked story.
<picture>

The opening page above tells us that 2,344,224 bikes from citibikes were used in Aug. '19 on the streets of NYC.\
The starting locations from where the bikes were rented, and the ending locations where they were dropped off are marked with circles on a base map of NYC. The sizes and the shade of the colors of the circles are proportional to the popularity of the locations (given in the legend).

The above picture shows only the most popular locations, but the number of locations can be changed using the filters. Observe that the starting and the ending locations overlap.

The next page of the story contains two separate visualization showing the duration for which citibikes were checked out. 

(figure)

From the first graph (shown above) we can use the filter on the time to confirm that all bikes were checked out for less than an hour, with most number of bikes being checked out for shorter periods of time, close to 5 - 10 minutes.

(figure)

The second visualization (above) details the first chart even further by adding gender information. We observe that males overwhelmingly checked out bikes compared to females.


(figure)

The story continues with the visualization above that shows the number of bikes that were in use at different hours of the day throughout  the week, with darker shades of the color indicating increasing number of trips. Hovering over the heatmap will give the number of trips at that time of the day.\
The chart tells us that during weekdays, the most popular times for using citibikes were around 7-9 am and 5-6 pm, which commonly corresponds to commute times to and from work.\
During weekends, bikes were in use throughout the day. This may indicate recreational biking during the weekends or after work hours.

(figure)

The next visualization expands on the previous chart by breaking it down by gender, which again confirms that males were by far the most common users of citibikes. For example, the numbers of bikes used by males and females at identical times are displayed here. Hovering at different points over the heatmap will display this information.\
Notice that the trend of bike usage by time of the day, on different days remained the same for both genders.

(figure)

The next page of the story also displays two separate visualization.\
The left chart is a heatmap again depicting the peak riding hours for day of the week, by gender, again affirming that males are the highest users of citibikes.\
Furthermore the chart shows the number of trips undertaken by type of users, whether subscribers or customers. Notice that citibike users are mostly subscribers. This is clearly shown by the second visualization in page (shown below)

(figure)

The next page describes bike utilization, and consists again of two separate visualizations.

(figure)

The figure above gives the total trip duration for each bike identified by its ID number. The sizes of the circle markers increases, and their shade of color deepend as the trip duration increases.

The next figure (shown below) also shows utilization but as a measure of the number of rides for each bikes. Here the top ten bikes with the highest number of rides are depicted. This number can be changed using the filter.

(figure)

Bikes that are used frequently will require higher maintainence and possibly repairs.

   
 

## Summary 

The results from the visualizations indicate that citibikes are more popular among the male gender.\
Furthermore subscribers use the bikes more commonly than customers.
The charts show that most bikes are checked out for shorter trips, and the popular checkout and return locations of the bikes are in the hub of the city. This indicates that citibikes are commonly used to commute to and from work, or to public transport stations during work hours.\
This is also supported by the visualizations indicating that the most popular times to ride citibikes in the weekdays are 7-9am and 5-6 pm.\
Citibikes are also used thoughout the daytime hours during weekends probably for recreational purposes or by tourists visiting the city.

Further visualizations that may be obtained from this data:
1. Chart showing the utilization of bikes and the starting and ending locations for bike checkouts. Citibikes that are rented and returned in locations in the hub of NYC, close to public transportations, show  higher utilizations, then this will strongly support that bike sharing is commonly used to commute to public trasportation sites.

2. Explore the relationship between trip duration and days of the week to answer the question if shorter trips are more common during weekdays and longer trips during the weekends. 

3. Create visualization to find if any correlation exists between bikes that are used more frequently, and their average duration of trips. 





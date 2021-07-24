# bikesharing

## Overview of Project 

### Purpose

The purpose of this project is to gain insights into bikesharing trends in New York City during late summer month by creating, and analyzing visualizations or vizzes, using Tableau Public.\
Data is obtained for August 2019 from Citibike, a bike sharing company in NYC.\
The vizzes are then presented in dashboards, which are used to create a story. 

### Resources used
- Data : "201908-citibike-tripdata.csv.zip" from "https://s3.amazonaws.com/tripdata/index.html"

- Software : Tableau Public 2021.2

## Results

Tableau Public link :
[link to dashboard] https://public.tableau.com/views/NYCCitibikeChallenge_16267935620380/CitiBikeUseinNYCSummers?:language=en-US&:display_count=n&:origin=viz_share_link

The following gives the descriptions of the visualizations from the above linked story.

![Citi Bike Use in NYC Summers](https://user-images.githubusercontent.com/71800628/126814320-a01fe8ef-328c-4fce-851d-510a5229d8a5.png)

The opening page of the Tableau story shown above tells us that 2,344,224 bikes from citibikes were used in Aug. '19 on the streets of NYC.\
The starting locations from where the bikes were rented, and the ending locations where they were dropped off are marked with circles on a base map of NYC. The sizes, and the shade of the colors of the circles are proportional to the popularity of the locations (given in the legend). 

The above picture shows only the most popular locations, but the number of locations can be changed using filters present on the page. Observe that the starting and the ending locations overlap and the most popular ones are in the hub of the city.

The next page of the story contains two separate visualization showing the duration for which citibikes were checked out. 

![Bike_checkout](https://user-images.githubusercontent.com/71800628/126815350-1d3ba85b-7f24-4e9d-a61b-c7e5308ba136.png)

On the first graph (shown above) we can use the filter on the time to confirm that hardly any bike were checked out for more than an hour. In general most bikes are checked out for less than half and hour, with the majority having a shorter trip duration lasting around 5 - 10 minutes.

![Bike_checkout_gender](https://user-images.githubusercontent.com/71800628/126815376-365077ab-19a2-47ea-8b3c-87b6140f58ea.png)

The second visualization (above) details the first chart even further by adding gender information. We observe that males overwhelmingly checked out bikes compared to females.

![peakHours_per_day](https://user-images.githubusercontent.com/71800628/126821414-805cd183-0f91-42bd-b666-dd68fab6d0d6.png)

The story continues with the visualization above that shows the number of bikes that were in use at different hours of the day throughout the week, with the shade of the color getting darker as the number of bikes increase. Hovering over the heatmap in the Tableau story page will give the number of trips at that time of the day.\
The chart tells us that during weekdays, the most popular times for using citibikes were around 7-9 am and 5-6 pm, which commonly corresponds to commute times to and from work.\
During weekends, bikes were in use throughout the day. This may indicate recreational biking during the weekends or after work hours.

![peakHours_per_day_gender](https://user-images.githubusercontent.com/71800628/126818540-26c37628-b90f-443e-a6ae-90550e125da8.png)

The next visualization expands on the previous chart by breaking it down by gender, which again confirms that males were by far the most common users of citibikes. For example, the numbers of bikes used by males and females at identical times are displayed here. Hovering at different points over the heatmap in the Tableau story page will display this information.\
Notice that the trend of bike usage by time of the day, on different days remained the same for both genders.\
(Note: another category in gender marked "UNKNOWN" can be seen on the Tableau story page by moving to bar below the chart to the right)

![user_trips_by_type_gender](https://user-images.githubusercontent.com/71800628/126872893-e959a0b4-b968-4e16-9e15-e3f51ef4d9d6.png)

The next page of the story also displays two separate visualization.\
The visualization on the left (shown above) is a heatmap again depicting the peak riding hours for days of the week, by gender, and by user type. This chart also affirms that males were the highest users of citibikes.\
Furthermore the chart shows that citibike users are mostly subscribers. This is clearly shown by the second visualization in the right.

The last page of the Tableau story describes bike utilization, and consists again of two separate visualizations.

![Citi Bike Use in NYC Summers (4)](https://user-images.githubusercontent.com/71800628/126815938-b3a76415-812c-408e-abcf-052dd09d562a.png)

The first visualization in the page seen above gives the total trip duration for each bike, identified by its ID number. The sizes of the circle markers increases, and their shade of color deepens as the trip duration increases. Hovering over each point in the story page will provide the information for that bike id.

The second visualization also shows utilization but as a measure of the number of rides for each bikes. Here the top ten bikes with the highest number of rides are depicted. This number can be changed using the filter.

Bikes that are used frequently will require higher maintainence and possibly repairs.

   
## Summary 

The results from the visualizations indicate that citibikes were more popular among the male gender.\
Furthermore subscribers used the bikes more commonly than customers.
The charts show that most bikes were checked out for shorter trips, and the popular checkout and return locations of the bikes are in the hub of the city. This, along with the peak hours for bike checkout being 7-9 am, and 5-6 pm indicate that citibikes were commonly used to commute to and from work, or to public transport stations during work hours.\
Citibikes were also used thoughout the daytime hours during weekends probably for recreational purposes, or by tourists visiting the city.

The sucess of citibike bike-sharing in New York City is attributed, to a large part, in the character of the city. NYC is well connected by public trasportation, and getting to locations of interest is within 30 mins. of biking.!


### Further visualizations that may be obtained from this data:
1. Chart showing the utilization of bikes and the starting and ending locations for bike checkouts. If bikes with the highest number for utilization were rented and returned in locations in the hub of NYC, close to public transportations, then this will strongly support that bike sharing was commonly used to commute to public trasportation sites.

2. Explore the relationship between trip duration and days of the week to answer the question if shorter trips are more common during weekdays and longer trips during the weekends. 

3. Create visualization to find if any correlation exists between bikes that are used more frequently, and their average duration of trips. 





# bikesharing
[link to dashboard](https://public.tableau.com/profile/michelle.goldfinger#!/vizhome/ChallangeModule14/NYCBikeSharing)

## Overview of the analysis
One of the key stakeholders asked to see a bike trip analysis that included graphs for the following data:

* How long bikes are checked out for all riders and genders.
* How many trips are taken by the hour for each day of the week, for all riders and genders.
* A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.
* The length of time that bikes are checked out for all riders.
* The number of bike trips by weekday for each hour of the day as a heatmap.

I added an additional 2 graphs to add to the story:
* A likely concern of investors is the cost of bike upkeep. The bikes used most frequently will probably be the ones that require the most maintenance, so I added this graph in order to determine which bikes have the highest sum of "Number of Rides.”

* The number of short-term customers and annual subscribers to the Citi Bike service.  This will help determine the types of customers expected for a bike-sharing company in Des Moines.

## Results
**Check Out Times by Users**

<img width="1063" alt="Check Out Time by Users" src="https://user-images.githubusercontent.com/75905911/113477392-71f2d900-944f-11eb-832f-8309d92c3edb.png">

According to my analysis, the most number of bikes were checked for 5 minutes (146,752). Nine hundred and eighty two bikes were checked out at the hour mark of trip duration. The least amount of bikes were checked out for 2 hours (95). For trips, the number of bikes check out after the first hour is drastically reduced. Therefore, most bikes are being rented for short-term trips.


**Check Out Times by Gender**
<img width="1062" alt="Check Out Times by Gender" src="https://user-images.githubusercontent.com/75905911/113477408-846d1280-944f-11eb-80af-01d3b9aaee24.png">

This graph details check out times by gender. According to the graph, males had the most check out times at the 5 minute mark (108,087). At the five minute mark the number of females who had bikes checked out was 33,041. People of an unknown gender had the least amount of bikes checked out at the five minute mark (5,624). For all the genders, the number of bikes check out after the first hour of trip duration drastically reduced.

**Trips by Weekday for Each Hour**
<img width="1429" alt="Trips By Weekday for each Hour" src="https://user-images.githubusercontent.com/75905911/113477801-82588300-9452-11eb-94a0-0b4058b98783.png">


According to this graph, Thursdays between 5-6pm is the busiest time during the week for bike rentals. Monday, Tuesday and Friday at the same time are also fairly busy for bike rentals. The last significant time for bike rentals is Monday-Friday from 8am-9am.


**Trips by Gender (Weekday Per Hour)**
<img width="1062" alt="Trips by Gender M:F" src="https://user-images.githubusercontent.com/75905911/113477429-a6669500-944f-11eb-8a44-d488fda23dcd.png">

<img width="1053" alt="Trips by Gender M:U" src="https://user-images.githubusercontent.com/75905911/113477433-a8305880-944f-11eb-9970-3165688437a8.png">

These three heatmaps show that males rent out bikes Monday, Tuesday, Thursday and Friday between 5-6pm (same as the Map above). Females also rent bikes during the week on Mondays, Tuesdays, Thursdays and Fridays between 5-6pm but at a much lower rate than males (11,336 vs 30, 749). Rentals by the unknown gender are highest on Saturdays from 12-1pm with 5,669 riders.






**User trips by Gender by Weekday**
<img width="1057" alt="User Trips by Gender by Day" src="https://user-images.githubusercontent.com/75905911/113477449-bf6f4600-944f-11eb-8ffa-472d5ea4d0ec.png">

This graph shows usage by subscriber vs customer by gender by weekday. Overall, there are more subscriber bike renters than customers. The graph highlights that male subscribers rent bikes far more than any other category, with Thursdays being the busiest day (259,316 riders). Females subscribers rent bikes consistently over the week with the peak day being Thursday with 88,281 riders. For the unknown gender peak rental times are for regular customers on Saturdays with 55, 375 renters.


**Bike Repairs**
<img width="1057" alt="Bike Reapirs" src="https://user-images.githubusercontent.com/75905911/113477482-f3e30200-944f-11eb-9aa5-d4a16b882990.png">

This graph indicates bike usage for each bike id. Deeper reds indicate bikes that are rented more often (and therefore more likely to need repairs). Yellows indicate bikes that have less rentals logged. This graph will be important for determining plans for bike maintenance and repair.


**Customers vs Subscribers**
<img width="1054" alt="Customers vs Subscribers" src="https://user-images.githubusercontent.com/75905911/113477459-c9914480-944f-11eb-8376-c1a54f6c43cc.png">

This last chart is a pie graph that shows the proportion of customers vs subscribers.  This will help us determine the types of customers we could expect for a bike-sharing company in Des Moines.

## Summary
The result of the CitiBike data analysis is that the proportion of subscribers is higher than customers. Males tend to rent bikes more often than females and people of an unknown gender. They take short bike trips during the weekdays between the hours of 8-9am and 5-6pm (most likely to comment to and from work).

Two other graphs that could be made to analyze this data could be:
* Analysis of starting station to see what area in the city most riders are starting from.
* Analysis of ending stations to see what area in the city most riders are ending their trips.

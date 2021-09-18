# Fordgobike Data Exploration
## By Ashraf Samir Aly


## Dataset

There are 174,952 rides in the dataset with 16 features (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude,(same for end station), bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip ). Most variables are numeric in nature, but the variables member_gender(ordered factor), start_station_name, user_type and end_station_name are categorical. ordered factor variables with the following levels.

(worst) ——> (best)
member_gender: Male, Female, Other.

We made some data wrangling for the dataset like dropping NA values, duplicates, fixing data types and some formating.


## Summary of Findings

<ul>
<li>Subscribers has much higher rides than customers.</li>
<li>Males has much higher rides than Females.</li>
<li>Thursday is the higher number of rented bikes for males as also for females, while the least day was sunday for both males and femalesm with males is the highest number of renting bikes.
Thursday is the higher number of rented bikes for subscribers as also for customers, while the least day was sunday for subscribers and wednesday for customers with subscribers is the highest number of renting bikes.</li>
<li>Clearly younger people renting more bikes(more duration) than older, but there is interesting peak in birth from 1960 to 1965.</li>
<li>There is a similar pattern in the average duration second in males and females between weekdays.
Females are clearly have average duration higher than males.
Both of males and females have higher average duration in Saturday and Sunday.</li>
</ul>


## Key Insights for Presentation

In this project we investigated what features of individuals that makes more rides, what is the most time rides takes place in and how long rides takes in the dataset.
<ul>
<li>Males have rented the bikes most of the times followed by females and others.</li>
<li>Subscribers have rented the bikes most of the times followed by customers.</li>
<li>For all the age groups, weekdays are for short rides and weekends are for long rides.</li>
<li>In terms of genders, males prefer rides for shorter duration while females prefer rides for high duration</li>
</ul>
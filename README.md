# Ford GoBike System Dataset Exploration 
## by SAUD ALSHUSHAN

## Dataset



>duration_sec: Total rend duration
>start_time and end_time: Start and end duration of using the service
>start_station_id and end_station_id: Unique identifier for bike station
>start_station_name and end_station_name : Name of the station
>start_station_latitude,end_station_latitude,start_station_longitude and end_station_longitude: Used to calculate distance
>bike_id: Unique identifier for each bike
>user_type: Either subscriber or customer
>member_birth_year and member_gender: Information about the user
>bike_share_for_all_trip: Either yes the user is sharing the ride or not 


>Data wrangling
>Removed rows that had missing varibles

>> member birth year
>>member gender
>>stations start and end name
>>stations sart and end id
>converted birth year varible to be integer
>converted start and end time to datetime format



## Summary of Findings

> Plan to compare between the  user type features of subscribers and customers

>Findings

>Majority of the customers of the  GoBike System are subscribers and they represent about 90% of total users (use)
>Users of  the service typically have consistent trip durations
>Trips time is condenced for under 20 minutes trips
> Majority of users are in their 30s (use)
>Shared trips is significantly lower than the number of non-shared trips
>Majority of bike trips occur during weekdays
>There is a noticeable drop in the number of trips during the weekend(use)
>Males represent the majority of the users
>Females make up one-third of the total male users 
>Customers do not have any shared trips
>Subscribers do not show a strong preference for shared trips
>Weekends have more customer trip activity than weekdays
>Weekdays are characterized by consistent Subscriber usage
>There is a positive relationship between trip distance and duration
>There is high activity in morning hour 6-8AM and also a higher one in 15-17PM usage of the service(use)
>Different genders have similar trip distance
>Subscribers and Customers exhibit similar usage patterns in terms of trip duration and distance, particularly for shorter trips however, as trip distances increase, the behavior of Subscribers tends to diverge from that of Customers
>Both Subscribers and Customers usually do not exceed 8 kilometers in their trips with long trips being  rare
>majority of trips across all days of the week fall within the 5-10 minute and 0-5 minute duration ranges
>Thursday have the highest number of trips in the 5-10 minute range
>Few trips exeeds 120 trip across all week
>Subscribers tend to use the service for shorter durations and distances
>Customers exhibit a broader range of trip durations and distances
>The avarage trip duration of customers in weekends is higher compared to week days
>The avarage customers trips is have overall  higher duration than Subscribers
>Subscriber are dominate in each gender segment
>There is a noticeably lower density of customers across all age groups, indicating that there are fewer people  to use the service as customers
>Subscribers tend to take more long trips than Customers, especially during peak commuting hours
## Key Insights for Presentation

>Majority of users are in their 30s----> plan to  compare age by type of user
>Males represent the majority of the user---->See users precentage with their gender
>There is high activity in morning hour 6-8AM and also a higher one in 15-17PM usage of the service---->add which user type is dominated in given hour

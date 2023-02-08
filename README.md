# Ford GoBike System Data Exploration Project

## Onyeukwu Stephen


## Dataset
This dataset contains information about the Ford GoBike sharing system, a regional bike sharing service operating in the San Francisco Bay Area. The data includes information on bike rental trips, including start and end time, start and end stations, and user information.

##### Steps taken in data wrangling are as follows:
- drop all null and Missing values
- Change datatype of start_time and end_time to datatype
- Change the datatype of start_station_id, end_station_id, and bike_id to string datatype
- Change the member_gender and user_type datatype to category
- Extract rider age from the birth year
- Extract parts of the start time column to form new column(e.g year, month, days of week, hours e.t.c)



## Summary of Findings

It became obvious that the highest number of trips were taken on Thursday and Tuesday, while weeekends have the lowest number of trips. Trips count peak from 7am - 9am  during daytime and 4pm - 7pm in the evening, this make sense as it is the usual rush hours. The subscribers accounted for about 91% of the user in the Ford Gobike system, while the customer take the remaining 9%. Customers spend longer time on trips than their counterpart (subscribers). Bike sharing is not available to the customer and overall the percentage of users who used the bike sharing was low. 



## Key Insights for Presentation

The focus of the presentation was mainly on the distribution of trips and trips duration with selected key variables.

The Ford Gobike system was mostly utilized by the subscribers. Most trips were taken on Thursday and Tuesdays, while the weekends had the lowest. The frequency of rides peaks from 7am - 9am  during daytime and 4pm - 7pm in the evening. Customer spend longer time on trips compared to subscribers. subscribers travel more quickly than regular customers every day of the week. Trip time notably increases on Saturdays and Sundays for both user categories, particularly for customer. The average duration of subscriber usage was significantly more consistent than that of all customers from Monday through Friday.
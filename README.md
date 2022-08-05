# Ford Gobike Trip Data Exploratory Analysis
## by Salima Omari


## Dataset

This dataset includes information about individual rides made in a bike-sharing system by Ford covering the greater San Francisco Bay area in 2018. This dataset can be found <a href="https://s3.amazonaws.com/fordgobike-data/index.html">here</a>. Each month's data were downloaded individually and they were merged together before being used to perform analysis.The dataset have 15 variables which are the duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type, member_birth_year, member_gender and bike_share_for_all_trip. The dataset consists of about 1.86 million trip data. 

For this project, trips with users above 80 years old were dropped and missing values in member information were also dropped. Datatypes of columns were also adjusted and some new columns were created like months, day of the week, Age category.


## Summary of Findings

In the exploration, I found out that more trips were done around summer and less trips are done during winter. Also weekdays have more trips than weekends, although it was observed that trips on weekends seem to be longer. The age distribution seemed to be a bit skewed to the left and which majority of users fall between age 30-35. And most trips last between 5-10mins. The prevalent gender that partakes in trips are Males, however females tend to go for longer trips. When finding the percentage distribution of user types of which there are two user types, It was seen that customers user type are very few and they do not partake in bike_sharing_for_all_trips(which has more cheaper bike sharing fee). Trips mostly occur between **7 to 9 hours of the morning** and around **16 hours and 18hours in the evenings**. However during the weekends, It is that trips mostly take place between 11 to 18 hours of the day.


## Key Insights from Analysis
- Majority of users fall between age ranges 30-35.
- During weekdays, trips mostly occur the mornings and evenings and during weekends it occurs between late mornings and evening.
- Most trips last for about 5 to 10 mins
- The majority of users are Males.
- More trips happen during summer period and the least numbe rof trips happens during Winter.
- Female Users go on longer trips. 
- Longer trips occur during the weekends
- There are two usertypes(Customer and Subscribers) and Only subscribers can partake in bike sharing
- Customer user types go for longer trips

This project was also done as part of Udacity's Data Analyst Nanodegree certification.


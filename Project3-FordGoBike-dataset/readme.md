# FordGoBike (Bike Shares)  Data Exploration

## Dataset

The data consisted of bikes' trip records and attributes of 183412 Bikes' rental records for February 2019 in San Francisco with mainly 9 features (start_station_name, end_station_name, weekday, start_hour, bike_share_for_all_trip, member_gender, member_age(years), user_type and duration_min(min)).
Most variables are Categorical, but the variables member_age(years) and duration_min(min) are numeric variables.

## Summary of Findings

- The trip durations & memebers' Ages variable took on a large range of values with right skewed distribution. Thus, Under the log transformation, the data looked more likely normally distributed, with mean riders' ages around 32 - 34 years old, and mean of trips durations around 9 minutes.
grades.

- Day time & Week days trips among The Top 7 stations.

    **Day Time:**
       - the station with the peak/top number of trips in morning is 'San Francisco Caltrain Station 2', which seems it is more likely a perfect start point to rent a bike and ride to work place as it is near to Caltrain station.
       - while the stations with the peak/top number of trips in evening are 'Montgomery St BART Station' & 'Powell St BART Station'. I am assuming people using these stations are more likely are returning from work places.

    **Week days:**
       - 'Thursday' has the highest trips number among all weekdays on all stations.
       -  'Market St at 10th St' & 'Powell St BART Station'have higher trips number during weekends than other stations. mostly there are good places near to those station to go during holidays.

- Most of the riders for the top7 stations are subscribers(more than 95%).
- the Male riders for the top7 stations are much higher than female riders (approximatly 1.5 to 2 times the Female riders)
- Average trip duration during weekend is longer than normal week days.
- Average riders ages and it's distributions in weekends are younger than riders ages during normal week days mostly related to family trips during holidays.
- Average ages of male riders are older than female rider.
- Average Trip duration for females are slightly longer than males.

## Key Insights for Presentation

For the presentation, I focus on exploring characteristics that could have an effect or relationships with the mention features of interest(Trip records and the average trip durations). Characteristics related to time like weekdays & day time) and others related to riders like ages , gender and user Type.

- Bikes rentals on workdays are approximatly double the rentals during weekends.it is more likely it is due to working schedule. The highest Bikes rentals are on Thursday.
- Bikes rentals have 2 peak intervals during the day.
       1st Peak interval 2 hours in morning between 08:00am to 10:00am. it's more likely that riders are going to their work.
       2nd peak interval 32 hours in evening between 04:00pm to 07:00pm. it's more likely that riders are returning from their work.

- exploring Top 7 stations with the highest trip number where 'Market St at 10th St' station has the highest number of trips

- Average Trip duration for females are slightly longer than males for all weekdays. More likely that it is related to physical performance of males are better than female as nature.

- Average trip duration for customers are longer than for subscribers and more longer during weekends. Assume that families (who are mostly are customers) are enjoying riding during holidays.


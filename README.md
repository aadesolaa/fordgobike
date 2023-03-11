# FordGoBike System Dataset Exploration
## by Adegbite Moriam Adesola


## Dataset
The dataset was provided by Udacity as part of the Data Analyst Nanodegree third project on data visualization. The dataset contains information about individual rides in a bike-sharing system covering the greater San Francisco Bay area. The dataset has 183412 rows and 16 columns. To prepare the dataset for visualization, the data cleaning steps carried out include removal of rows with missing values and changing the datatypes of the bike_id, start_time and end_time. More columns were extracted as necessary and the final column names are 'duration_sec', 'start_time', 'end_time', 'start_station_id', 'start_station_name', start_station_latitude', 'start_station_longitude', 'end_station_id', 'end_station_name', 'end_station_latitude', 'end_station_longitude', 'bike_id', 'user_type', 'member_birth_year', 'member_gender', 'bike_share_for_all_trip', 'start_hr' 'start_day', 'start_month', 'start_year', 'end_hr', 'end_day', 'end_month', 'end_year'.
Click on this [link](https://www.google.com/url?q=https://www.fordgobike.com/system-data&sa=D&ust=1554484977399000) to download the dataset.

## Summary of Findings
During the univariate exploration of the bike data, the following insights were deduced:
- The data included records from February to March 2019
- Most rides were below 1000 seconds
- 90.5% of riders are subscribers
- 74.6% are males
- Most riders were born between 1985 and 1995
- Thursdays were the busiest day and 5pm, 8am, 6pm and 9am were the busiest hours

Findings from the bivariate exploration were:
- Trips are longer during weekends than during weekdays.
- Riders that are able to ride beyond 20000 seconds are born after 1960 and there are riders born between 1950 and 2001 go on trips below 3000 seconds.
- On average, females ride for longer duration that males while customers ride for longer duration than subscribers.
- The proportion of males are greater than females in each of the user type.
- Most subscribers ride on thursday while weekends are the lowest. Most customers ride on thursday while wednesday has the lowest record.

The multivaritate exploration showed that:
- Customers travel more than subscriber during each day of the week. For each user type, the trip duration is higher on Weekends than on weekdays. However, customers travel for longer periods on Sundays than on Saturdays while it is vice versa for subscribers.
- Females ride for the longest average duration on Sunday and for the least average duration on Tuesday. The 'other' gender also ride more than the males on each day of the week.

## Key Insights for Presentation
For the presentation, I'll be focusing on how customers travelled during each day of the week as well as how each gender made use of the bikes during each day of the week.
Therefore, the presentation will start by introducing individual variables of user type, member gender and start day, before going on to combine the variables to see how they relate to each other.

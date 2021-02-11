# (Ford go Bike Data Exploration)
## by (Ahmed Saeed)


## Dataset

> The dataset used for this exploratory analysis consists of month individual trip data for February 2019 in CSV format covering the greater San Francisco Bay area,
 raw data is available here https://www.fordgobike.com/system-data Visualizations below are created from wrangled and cleaned data to facilitate exploration analysis and help discover usage pattern and rider characteristics.

> There are 183412 bike trip in the dataset with 16 features  
Most variables are numeric , but the variables start_station_name , end_station_name , user_type are Strings
also start_time , end_time are considering as object

## Summary of Findings

> It's seems that most of the trips are about 10 minutes .. most users use bikes for short trips.
> Working days have the most trips especially (Thursday) >> our users maybe use bikes for going to work or school  
Sunday and Saturday are less to have trips 
> at 17 and 08 there are rush hours when people going and leaving Work
> Customer users  have more duration mins more than subscribers
> Trips from 10 to 16 usualy have higher Duration
> Trips duration increase on weekends
> Users with age of 31 and 36 seem to have the highest trip duration and as the users get older, the trip duration decrease.
> In all gender types, the age range of 10-20 and 50-60 has the longest trip duration, this could be teenagers use bikes for goning to school and university.

## Key Insights for Presentation

> For the presentation, I focused on the features that may influence the trip duration and then found when rush hours occur
also focused on the Age and how it influence the trip duration
# (Lyft Gobike Data Exploration)
## by (Smeet Chitalia)


## Dataset

> The dataset used in this project is the open sourced 2017 Ford GoBike system data. The project will be done in two parts. First part will be investigating dataset to perform exploratory data analysis. Second part will be to explore different features from the dataset based on the exploratory analysis findings and convey them to others in the form of explanatory analysis.

> A slide deck presentation will be created at the end to display the polished explanatory visualizations.

> In this dataset, there are 519700 bike share entries with 15 variables.

Here, we have 4 variables with datatype `int`
- duration_sec
- station_start_id
- end_station_id
- bike_id

We have 5 variables with datatype `float`
- start_station_latitude
- start_station_longitude
- end_station_latitude
- end_station_longitude
- member_birth_year

We have 6 variables with datatype `object`
- start_time
- end_time
- start_station_name
- end_station_name
- user_type
- member_gender

## Summary of Findings

- User Type plays a critical role in Trip Durations. Also, one interesting statistic that came to light was even though Subscribers count is very high as compared to Customers, they have a low Trip Duration count as compared to Customers.
- User Gender and Trip Duration (Duration Sec) also has a similar relationship where number of Females & Other gender have higher Trip Duration as compared to the Male gender even though males has a significantly higher count.
- Users between ages 20-45 are more inclined towards using bikes.

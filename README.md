# bikesharing

## Project Overview
This project is an analysis of New York Citi Bike data, using data visualization tools to explore the viability of a bike-sharing business in Des Moines.

## Resources
- Data Source: [Citi Bike Data](https://www.citibikenyc.com/system-data), [201908-citibike-tripdata.csv.zip](https://s3.amazonaws.com/tripdata/201908-citibike-tripdata.csv.zip)
- Software: Python 3.8.8, Anaconda Navigator 2.1.1, Conda 4.11.0, Jupyter Notebook 6.4.6, Tableau Desktop 2021.3

## Results

### Deployed Tableau Analysis
[Link to dashboard](https://public.tableau.com/views/Book1_16485105220170/CitiBikeNYCStory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

### New York Citi Bike data visualizations for August 2019

<p align="center">
    <img src="Resources/Dashboard.png"> 
</p>

- There were over 2.3 million rides for the month of August 2019.
- 81% of the users were subscribers. 65% of the users were confirmed males and 25% were confirmed females.
- There is a wide range of the age of the users. Younger users tend to use the service for longer rides.
- Top ride starting locations are in the most touristic and busy areas, as we see here in Manhattan.

<br>

#### August Peak Hours
<p align="center">
    <img src="Resources/Aug_Peak_Hours.png"> 
</p>

- Highest activity hours are from 5:00 PM to 7:00 PM and require the most resources mobilized.
- The activity from 2:00 AM to 5:00 AM is low so this would be the window for bike maintenance.

<br>

#### Checkout times for users
<p align="center">
    <img src="Resources/User_Checkout.png"> 
</p>

- Bikes are mostly checked out for 4 to 6 hours across all genders

<br>

#### Checkout times by gender
<p align="center">
    <img src="Resources/Gender_Checkout.png"> 
</p>

- Male users take approximately 3 times more rides than the female users.

<br>

#### Trips by weekday and gender
<p align="center">
    <img src="Resources/Gender_Weekday_Hour.png">
    <img src="Resources/Gender_Weekday.png">
</p>

- Most weekday rides are around 7:00 AM to 9 AM and 5:00 PM to 7:00 PM.
- Weekend rides are highest from 10:00 AM to 7:00 PM.
- Those rides are mostly taken by male users.


## Summary
The data shows high activity of the bike sharing service in New York during the month of August 2019.
The far majority of the rides were in the very busy Manhattan Island, taken by male users during morning and evening rush hours. This implies that Citi Bike services are used as an alternative to public transportation by commuting workers.

Additional analysis would be beneficial by :
- comparing data for different months to determine trends across the year,
- including weather data to find the correlation between the weather and the rides. 
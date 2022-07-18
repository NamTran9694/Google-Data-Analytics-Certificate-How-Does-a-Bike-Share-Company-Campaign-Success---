# Google Data Analytics Certificate-How Does a Bike-Share Company Campaign Success
# Introduction:
* This project is the capstone assignment for the Google Data Analytics Professional Certificate program. I applied all the knowledge, skills, and competencies I gained from earlier courses (analysis phases, analytics thinking, data processing, data cleaning, data analyzing, and visualization) to address business objectives.
* This project will analyze publicly available data sets provided by the course for a bike share program based in Chicago.

### Scenario:
* This project is belonged to the marketing analyst team at Cyclistic, a bike-share company in Chicago. Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to broad consumer segments. One approach that helped make these things possible was the flexibility of its pricing plans: single-ride passes, full-day passes,
and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members.

* The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, analytics team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, marketing team can design good marketing campaigns.

# Business Objectives:
* How do casual riders and annual memberships use Cyclistics services differently from 06/2021 to 05/2022? From these insights, the marketing team will design a new marketing strategy to convert casual riders into annual members.
* Are there any trends in history data that can help predict the future demand of customers.

# Data Collection:
* The data for the project is provided by Motivate International, Inc. under this license.
* The data was collected and downloaded from [link](https://divvy-tripdata.s3.amazonaws.com/index.html).
* For this analysis, 12 months data was used; from June 2021 to May 2022. The data was accessible in a zip folder, and downloaded to a personal computer. The data are organized monthly, and merged into only one data.

# Data Processing:
### Data Overview:
* There are 5,860,776 observations and 13 variables
* **ride_id (categorical)**: Unique number assigned to a ride trip.
* **rideable_type (categorical)**: Type of bike used during trip; standard two-wheel bike, reclining bike, hand tricycle, or cargo bike.
* **started_at (datetime)**: Start date and time for the trip
* **ended_at (datetime)**: End data and time for the trip
* **start_station_name (categorical)**: Name of the station where the trip started
* **start_station_id (categorical)**: Unique identification code assigned to the start station.
* **end_station_name (categorical)**: Name of the station where the trip ended.
* **end_station_id (categorical)**: Unique identification code assigned to the end station.
* **start_lat (numeric)**: Latitude coordinate of where the trip started.
* **start_lng (numeric)**: Longitude coordinate of where the trip started.
* **end_lat (numeric)**: Latitude coordinate of where the trip ended.
* **end_lng (numeric)**: Longitude coordinate of where the trip ended.
* **member_casual (categorical)**: Customer type; “member” = annual member, “casual” = casual rider.

### Data Cleaning and Formatting:
* Dealing with missing values, transforming data into correct data types.
* Adding **Date, Month, Day_Of_Week, Start_Service_Hour and Ride_Duration variables** to better understand data

# Analyzing Data
### Number of trips and trip duration by User Types
* The trips made by memberships was higher significantly than that of casual customers.
* However, the duration of trips made by casual user were longer than that of membership. 
### The difference between memberships and casual users in using different types of bike 
* The percentage of electric bike of casual and member user were quite equal, about 40%, while the classic bike proportion of membership was higher than casual user, 60% and 48% respectively. Memberships had no interest in docked bike, while 10% trips of cusual users were made by docked_bike.

### The total trips made by casual users and memberships within a year from June 2021 to July 2022  
* In June, July, and August of 2021, the numbers of trip made by casual user was slightly higher than memberships, while from September 2021 to May 2022, membership's rides were significant higher than casual rides.
* The number of ride drop sharply from June 2021 toward to the end of 2021. The trend reversed from January 2022 to May 2022.
* The trip average duration time of memberships were significant lower than that of casual trips.
* The average duration time of memberships changed slightly around 14 minutes per trip, while trip duration of casual users dropped from 34 mins/trip in June 2021 to 23 mins/trip in December 2021, then increase again.

### **The difference between membership and casual users by days of week**
* We can see opposite trends between membership and casual users within a week, casual users love riding bikes in weekend, while the number of trips made by memberships decreased from Monday toward to Sunday.
* The time using bike of memberships increased slight from Monday to Sunday, while the time using bike of casual users on Saturday, Sunday, and Monday were significant higher than that of the rest.

### **The difference between membership and casual users by Start time**
* The total trips made by both casual users and memberships increased from 4:00 am to 5:00 pm, then drop significantly toward midnight.
* A similar trends are seen in both casual users and membership, users having start time from 1am to 4am have longer using time rather than other start time.
* Overall, in weekend, users tend to ride longer than in the week day.
* With casual customer on week days, trips having start time from 12am to 4am have duration time significantly longer than others, while trips having start time from 5am to 8am last shortest.

# Key Insignts and Recommendations:

### Key Insignts
* Casual users ride longer than membership users.
* The trips made by memberships in the work day are more than on the weekend, while casual riders make more trips on the weekend.
* The length of trips in the weekend of casual users is significantly higher than in the weekend, while the difference in trip duration of memberships is not significant.
* The peak seasons are summer and fall.
* The demands increase from 5am to 5pm for both memberships and casual riders.
* Large proportion of casual users take rides from stations near the beaches, while memberships likely start the rides from city centers.

### Marketing Recommendations to turn casual riders into memberships
* Provide promotions or discounts on weekend rides for casual members if they upgrade to memberships.
* Provide promotions for casual riders using services in workdays, so the company can increase the trips made by casual riders.
* Provide promotions or discounts in low seasons (spring and winter)
* Partner with restaurants and attractions near beaches to provide promotions and discounts for casual riders to encourage them to upgrade memberships because casual riders often start trips from these areas.

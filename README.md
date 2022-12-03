# Bike_booking

1) Used Bike dataset which contained the information about number of bike rented according to season, year, day, holiday and various natural factors like temperature, humidity, windspeed.
2) Performed Data Cleaning and Exploratry data analysis on the data to see how many number of bikes are rented according to the condition of day. 
Inferences from Data visualization.
            1. The cnt in the year 2019 was way more than that in 2018. The 75th percentile of the cnt in 2018 is almost equivalent to 25 percentile in 2019.
            2. Number of bikes booked according to seasons in a decreasing order: Fall, Summer, Winter and Spring.
            3. The trend of increasing use of bike starts from january(lowest) till June then stays almost the same till september and then starts dropping. There's a scope to increase the bike usage in the months from january till May and from October to december. The drop of bike usage from october till December might be explained by the winter season and less bike usage from January to April might be explained by higher windspeed.
            4. Days of the week doesn't matter much. Almost similar number of bikes are rented same number of times everyday in a week but Monday and tuesday have relatively less bookings.
            5. The average count of bikes rented is more during non-public holidays.
            6. The average count of bikes rented when the weather is situation is 'Clear, Few clouds, Partly cloudy, Partly cloudy' or 'Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist' termed as 'Best' and 'Neutral' is much more compared to other situations termed as 'Bad' and 'Worse'- Wind speed during the bad weather situations is more than 'Best' and 'neautral' weather situations and hence more number of bikes are rented in such situations.
            7. The line-graph trend shows that the count of bikes rented is least from 1st-4th day, peaks from 6th-10th day in a month and again dips till 13th day and kind of stays almost constant throughout the month.
3) Created Dummy variables for season, month, weekday, weather situation as they are catagorical data and we want to predict number of bikes rented, a numerical data. So, for retrieving numerical information from categorical variables.
4) Standardizaton is done on the whole data as various features have different standardizing parameters.
5) Linear regression and Random Forest Classifier is used to predict the number of bikes rented.
   Mean squared error obtained from Linear regression model is 2.257.
   Mean squared error obtained from Random Forest Classifier is 0.292

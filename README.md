# Analysing-Bike-Sharing-data
Exploratory analysis of data from https://www.bluebikes.com/ which includes data on over 1.5 million trips made with the service. 
Exciting!!!!

# Data definition: Trips table
|Column | Definition                                     |
|------------|------------------------------------------------|
|id          | A unique integer that serves as a reference for each trip |
|duration    | The duration of the trip, measured in seconds |
|start_date  | The date and time the trip began |
|start_station | An integer that corresponds to the id column in the stations table for the station the trip started at|
|end_date | The date and time the trip ended |
|end_station | The 'id' of the station the trip ended at |
|bike_number | Hubway's unique identifier for the bike used on the trip |
|sub_type | The subscription type of the user. "Registered" for users with a membership, "Casual" for users without a membership |
|zip_code | The zip code of the user (only available for registered members)|
|birth_date | The birth year of the user (only available for registered members)|
|gender | The gender of the user (only available for registered members)|

# Interesting questions for exploratory analysis
1. What was the duration of the longest and shortest trip?
2. What was the ratio between registered and unregistered, "casual" users?
2. How many trips were taken by 'registered' users vs. 'casual' users?
3. What was the average trip duration taken ?
4. Do registered or casual users take longer trips?
5. Which bike was used for the most trips? (and maybe find out why)
6. What is the average duration of trips by users over the age of 18-30?
7. What are the most frequent times that either users have been taking rides? 

# How to access the data exploration summary
1. Click on Bike sharing data analysis file to view the fruits of my labour inside github viewer.
2. You do not need to install anything to view this summary of analysis because Jupyter Notebooks shared through GitHub are rendered, (though static. GitHub does not run the notebook(s) in a repository.)

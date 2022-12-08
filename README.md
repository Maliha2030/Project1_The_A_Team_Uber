# Project_1_The_A_Team
Repo to store our project 1 work   

Questions of Focus : 

1.Does the time/date affect how often people order Uber’s?
2. How has Uber prices changed over time?
3. What distance are people using Uber’s for?
4. What are the most common amount of passengers for an Uber

Our Datasets:
https://www.kaggle.com/datasets/yasserh/uber-fares-dataset

This link contains  csv file.

Project Outline:
Uber has become the most popular choice for travel across the
world.
•
In 2021, there were 118 million users in over 80 countries.
•
Exploration of Uber data in New York between 2009 and 2014.
•
Exploration of the consumer behaviour.

Script - jupter notebok : 
Converted csv file to database.
Clean up process : Delete column "Key", Delete rows  with 0 longitude and longitude value, Delete rows  with 0 passengers and fare amount value.
Creating new columns Month Date Day Hour Day of week.
Once our data frame is formated and filltred we are going to analysis our data.
Calculatin the distance between the pickup and drop co-ordinates using the Haversine formual for accuracy.
Delete coordinates as we've now got distance.
Create a scater plot Distance vs Fare Amount.
Calculate total amount of trips per year, month, day and hour so we can creat bar and pie chart for our data visualization .
Define a function to create Linear Regression plots.
Creating chart for Avg_distance vs. Average_fair Linear Regression Plot. 

Conclusions and Implications :
Relationships we looked at
○
Trend of
total number of trips/rides
total fares collected
fare prices adjusted for distance

Distribution of
total trips per month over 5 years
average passenger numbers
average distance travelled
Time (seasonality) variables (hour of day; day of week; month of year) with
total trips
average number of passengers
Fare price with distance travelled

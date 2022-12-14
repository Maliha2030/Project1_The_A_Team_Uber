# Project_1_The_A_Team 


Repo to store our project 1 work  


***Questions of Focus:  
  
1. Does the time/date affect how often people order Uber trips?  
2. How has Uber prices changed over time?  
3. What distance are people using Uber for?  
4. What are the most common amount of passengers for an Uber trip?.


***Introduction: 

Uber has become the most popular choice for travel across the world. In 2021, there were 118 million users in over 80 countries.  We wanted to explore what factors affect customer behaviour and fare costs for this major transport provider in a specific location.

***Methods:

We obtained a dateset from https://www.kaggle.com/datasets/yasserh/uber-fares-dataset. It contains data on Uber trips in New York City, United States of America. It has 200000 rows of data for the years 2009 to 2015, containing a unique trip identifier, the fare of those trips, pick-up time, pick-up location (via latitude and longitude) and the same for drop-off.  
We downloaded the CSV file containing the dataset. We then used the Jupyter notebook to change that file to a pandas dataframe.  


We then performed the following data clean-up and massaging process:  
*Delete column "Key",  
*Delete rows with '0' values for longitude and longitude, passengers and fare amounts,  
*Creating new columns 'Month', 'Date', 'Day', 'Hour', 'Day of week'.  
*Calculating the distance between the pickup and drop co-ordinates using the Haversine formula for accuracy.  
*Delete coordinates as we've now got distance
*Delete 2015 trips as the  year is incomplete and would not be fairly comparable to other years in the dataset.  


***Analysis:  

Once our data frame was formated and filtered we analysed our data as follows:  

*We charted as bar charts or line charts the trend over time (years) of  
*-the total number of trips  
*-total fares collected  
*-fare prices adjusted for distance  

*We charted as bar charts or pie charts the distribution of  
*- total trips per month over 5 years  
*- time (seasonality) variables (hour of day; day of week; month of year) with total trips
*- total number of trips by number of passengers
*- average number of passengers
*- average distance travelled

*We charted as correlation charts the relationship between, and measured the correlation coefficient of  
*- Fare price versus the distance travelled (as an aggregate, and specifically for 2012 as an exemplar year)  

***Results
The full results are contained in the jupyter notebook file Final Project Script.ipynb, and is summarised in the presentation slides, both listed in this repo.  

***Conclusions and Implications:  

From the companies perspective, our analyses showed several important points:  
*- The total trip numbers made over time are stable (stagnant?), and not increasing  
*- But the fares collected are increasing  
*- However, this does not seem to be through increased trips nor increased distances covered  
*- Hence, the company needs company cost data (fuel, repairs, staff, rent etc), and macroeconomic data (inflation) to assess whether this continued growth in fare   collected translates to profit, and whether the profit rate is above the levels of inflation 

From the customer's perspective, we asked whether the data shows if the service is worth-it:  
*- the fare costs per unit of distance are ever increasing  
*- more data on proportions to income is needed to assess affordibility.  

We thus identified that the company could explore the following markets to develop and grow trip numbers:  
*- Increase distance travelled  
*- Increase trips with more than one passenger

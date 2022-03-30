# World_Weather_Analysis

Task: Collect and analyze weather data across cities worldwide.

Purpose: PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.

Method: Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.
Analysis of the data will be split into three main parts, or stages.

Collect the Data

Use the NumPy module to generate more than 2000 random latitudes and longitudes.
Use the citipy module to list the nearest city to the latitudes and longitudes.
Use the OpenWeatherMap API to request the current weather data from each unique city in your list.
Parse the JSON data from the API request.
Collect the following data from the JSON file and add it to a DataFrame:
City, country, and date
Latitude and longitude
Maximum temperature
Humidity
Cloudiness
Wind speed
Exploratory Analysis with Visualization


Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences. Using these steps:

Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
Create a heatmap for the new DataFrame.
Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.
Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city. 
Provide hotels and round trip directions for all city stops on this trip. 
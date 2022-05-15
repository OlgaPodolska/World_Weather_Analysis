# World_Weather_Analysis
Visualization Weather Data

## Purpose:

Purpose of this assignment was to provide real-time suggestions for our client's ideal hotels by PlanMyTrip app. We made a few changes to take the app to the next level. We added the weather description to the weather data. Then, we filtered the data for customer weather preferences. From the list of potential travel destinations, we choosed four cities and created a travel itinerary. Finally, using the Google Maps Directions API,we created a travel route between the four cities as well as a marker layer map.

Requests Library 2.26.0 
geojson-2.5.0
gmaps-0.9.0 

## Task: 

### 1. Retrieve Weather Data

We generated a set of 2,000 random latitudes and longitudes, retrieved the nearest city, and perform an API call with the OpenWeatherMap. In addition to the city weather data we gathered in this module, we used API skills to retrieve the current weather description for each city. Then, we created a new DataFrame containing the updated weather data.

### 2. Create a Customer Travel Destinations Map

We used input statements to retrieve customer weather preferences, then used those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.

3. Create a Travel Itinerary Map




Collect and analyze weather data across cities worldwide.
* Purpose: PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.
* Method: Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.

* 1. Collect the Data
Import our dependencies and initialize counters and an empty list that will hold the weather data.
Loop through the cities list.
Group the cities in sets of 50 to log the process as we find the weather data for each city.
Two counters will be needed here: one to log the city count from 1 to 50, and another for the sets.
Build the city_url or endpoint for each city.
Log the URL and the record and set numbers.
Make an API request for each city.
Parse the JSON weather data for the following:
City, country, and date
Latitude and longitude
Maximum temperature
Humidity
Cloudiness
Wind speed
Add the data to a list in a dictionary format and then convert the list to a DataFrame.
* 2. Exploratory Analysis with Visualization
** Create scatter plots of the weather data for the following comparisons:
Latitude versus temperature
Latitude versus humidity
Latitude versus cloudiness
Latitude versus wind speed
** Determine the correlations for the following weather data:
Latitude and temperature
Latitude and humidity
Latitude and cloudiness
Latitude and wind speed
** Create a series of heatmaps using the Google Maps and Places API that showcases the following:
Latitude and temperature
Latitude and humidity
Latitude and cloudiness
Latitude and wind speed
* 3. Visualize Travel Data
Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences. Complete these steps:
Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
Create a heatmap for the new DataFrame.
Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.
Store the name of the first hotel in the DataFrame.
Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city.
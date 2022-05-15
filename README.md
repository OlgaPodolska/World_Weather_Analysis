# World_Weather_Analysis
Visualization Weather Data

## Purpose:

Purpose of this assignment was to provide real-time suggestions for our client's ideal hotels by PlanMyTrip app. We made a few changes to take the app to the next level. We added the weather description to the weather data. Then, we filtered the data for customer weather preferences. From the list of potential travel destinations, we choosed four cities and created a travel itinerary. Finally, using the Google Maps Directions API,we created a travel route between the four cities as well as a marker layer map.

Requests Library 2.26.0 
geojson-2.5.0
gmaps-0.9.0 

## Tasks: 

### 1. Retrieve Weather Data

We generated a set of 2,000 random latitudes and longitudes, retrieved the nearest city, and perform an API call with the OpenWeatherMap. In addition to the city weather data we gathered in this module, we used API skills to retrieve the current weather description for each city. Then, we created a new DataFrame containing the updated weather data.

![DataFrame.png](/Weather_Database/DataFrame.png) 

### 2. Create a Customer Travel Destinations Map

We used input statements to retrieve customer weather preferences, then used those preferences to identify potential travel destinations and nearby hotels. 

![hotels.png](/Vacation_Search/hotels.png) 

Then, show those destinations on a marker layer map with pop-up markers.

![WeatherPy_vacation_map.png](/Vacation_Search/WeatherPy_vacation_map.png) 

### 3. Create a Travel Itinerary Map

We created a marker layer map of the vacation search results.

![map.png](/Vacation_Itinerary/map.png) 

We used the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary.

![path.png](/Vacation_Itinerary/path.png) 

![WeatherPy_travel_map_markers.png](/Vacation_Itinerary/WeatherPy_travel_map_markers.png) 


# World_Weather_Analysis

## Challenge Overview

### PlanMyTrip is a top travel technology company that specializes in internet related services in the hotel and lodging industry. The company has requested: 
-	Adding the weather description to the weather data collected
-	Filtering the data based on beta testers’ weather preferences, which will then be used to identify potential travel destinations.
-	From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary, which will include a travel route between the four cities as well as a marker layer map


## Challenge Summary
## Part 1 - Retrieve Weather Data
To create a new DataFrame containing updated weather data, I first generated a set of 2,000 random latitudes and longitudes, retrieved the nearest city, and performed an API call with OpenWeatherMap. The API call retrieved:
 - Latitude and longitude
 - Maximum temperature
 - Percent humidity
 - Wind speed
 - Weather description

![](https://github.com/AB3478/World_Weather_Analysis/blob/0826a1a117b25eacb0b9e28173c8ed5c8b3f7680/Weather_Database/Weather_Database.png)

## Part 2 - Create a Customer Travel Destinations Map
I added input from beta tester's regarding their weather preferences to identify potential travel destinations and nearby hotels. The following map highlights those destinations and includes a layer map with pop-up markers including additional city and hotel-related details.

![](https://github.com/AB3478/World_Weather_Analysis/blob/66622595d823d5fda85ed385e3db6d7c7358e48a/Weather_Database/WeatherPy_vacation_map.png)

## Part 3 - Create a Travel Itinerary Map
Beta testers chose four cities from the vacation map that other customers might want to visit, including Sanary-Sur-Mer, France, Mantua, Florence, and Sestri Levante, Italy. To map this Mediterranean vacation, a directions layer map was created with a starting and ending city.

![](https://github.com/AB3478/World_Weather_Analysis/blob/b165a06554762cabc72d03e8cfda1e2a9d367f13/Vacation_Itinerary/WeatherPy_travel_map.png)

The marker layer map was updated to provide potential customers with additional details for the four cities included on the Mediterranean vacation itinerary.

![](https://github.com/AB3478/World_Weather_Analysis/blob/8a6fff20c9ec5cab2190b0d123ead1e9a51c172a/Vacation_Itinerary/Weather_travel_map_markers.png)

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

![](https://github.com/AB3478/World_Weather_Analysis/blob/c1e6f9368d70c7d4b2b955e81495935747910ce4/Resources/Weather_Database.png)

## Part 2 - Create a Customer Travel Destinations Map
I then used input statements to retrieve customer weather preferences, using those inputs to identify potential travel destinations and nearby hotels. The following map highlights those desitnations and includes a layer map with pop-up markers including additional details.

![](https://github.com/AB3478/World_Weather_Analysis/blob/66622595d823d5fda85ed385e3db6d7c7358e48a/Weather_Database/WeatherPy_vacation_map.png)
## Part 3 - Create a Travel Itinerary Map

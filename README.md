# World_Weather_Analysis

###Analysis of World Weather Information using weather and google APIs. Coding through Jupyter Notebooks

##Project Overview

This project's purpose was to build the coding for a new app "PlanMyTrip". Script allows users to input their ideal temperature preferences for a vacation destination and receive back a list of locations matching their deisres. Additionally they would receive a travel itinereary and lodging recommendations if desired. The Google Maps API, OpenWeatherApp API, and JupyterNotebooks utilizing Python were the tools used to build the code script. 

We created the following analytical deliverables:

  Retrieval of weather data.

  Generated a random set of 2,000 latitudes, and 2,000 longitudes and generated a list of cities who's coordinates fell wtithin the random coordinate-grid intersects.
  Used an API call to get the current weather statistics for each city, and placed them within a dataframe to store.
![Screenshot (108)](https://user-images.githubusercontent.com/93295751/145732457-66d89951-6298-4278-b285-f1dcb8612810.png)

Next we did the following for a custom Travel Destinations Map:

  Create input statements to retrieve customer weather preferences

  Utilize specified preferences to identify:

  potential travel destinations
  
  nearby hotels
  
  Show destinations on a marker layer map with pop-up markers
![WeatherPy_vacation_map png](https://user-images.githubusercontent.com/93295751/145732507-4c0d2d87-2c36-40ad-9581-325b87f64a7a.png)

Finally we created a travel itinerary map:

  Use Google Directions API to create travel itinerary

  Created a map showing the route between four cities chosen from the customer's possible destinations
  
  Created a marker layer map with pop-up markers for each city on itinerary

![WeatherPy_travel_map_markers png](https://user-images.githubusercontent.com/93295751/145732574-3b7c09aa-87d1-4ee9-b95e-28955387966e.png)

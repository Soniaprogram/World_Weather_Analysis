# World_Weather_Analysis

## Overview of analysis

This analysis involves using Jupyter Notebook, Pandas Library, CitiPy, Python Requests, APIs, and JSON Traversals to collect weather data from around the world. I have analyzed the data using Pandas and plotted the data using Matplotlib library and Google API. I have also performed statistical analysis using Scipy library to present a Series of plots that visually and statistically show the relationship between latitude and a variety of weather parameters. 

PlanMyTrip is a top travel technology company that specializes in Internet related services in the hotel and lodging industry. Jack is the head of analysis for the User Interface team. I will assist Jack by collecting and presenting data for customers via the Search page which users can filter based on their preferenced travel criteria, in order for them to find their preferred hotel anywhere in the world. 

I have modified the app to allow users to input statements to filter the data for their weather preferences to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the user can choose four cities to create a travel itinerary. Using Google Maps Directions API, I created a travel route between the four cities and a marker layer map as well. 

### Deliverable 1: Retrieve Weather Data
I generated a set of 2,000 random latitudes and longitudes, retrieved the nearest city, and performed an API call with the OpenWeatherMap. I updated the weather data to contain the current weather description for each city. 

### Deliverable 2: Create a Customer Travel Destinations Map
I used input statements to retrieve customer weather preferences and used these to identify potential travel destinations and nearby hotels. Finally, I showed these destinations on a marker layer map with pop-up markers as seen below.

![deliverable2-1](https://github.com/Soniaprogram/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

### Deliverable 3: Create a Travel Itinerary Map
I used Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer's possible travel destinations. I also created a marker layer map with a pop-up marker for each city on the itinerary. 

Depicted a Travel Itinerary Map of the following 4 cities in Mauritius:
![deliverable3-1](https://github.com/Soniaprogram/World_Weather_Analysis/blob/main/weather_data/deliverable34cities.PNG)


![deliverable3-2](https://github.com/Soniaprogram/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG)


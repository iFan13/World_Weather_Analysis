# World Weather & Vacation Analysis

## Overview

The purpose of this repository is to delve into APIs, taking data from OpenWeatherMap.org and Google maps, places and directions API. This collected data is then combined with extensions in python such as gmaps to produce a psuedo app that could, with further development, provide a user with a method of selecting destinations by preferred weather conditions, specifically temperature, and then plotting a trip path using selected locations. As a demonstration, a round trip starting from Nelson Bay, Australia traveling through Port Macquarie, Armindale, and Dubbo before returning to Nelson Bay can be found within the repository. 

A sample of the weather data gathering process may be seen in the code [here](/Weather_Database/Weather_Database.ipynb) and is saved in the csv of collected data [here](/Weather_Database/WeatherPy_Database.csv). (Due to the nature of the random module and methods, re-running the code will have no guarantee of producing the same results; Additionally, an API key will need to be independently acquired).

A follow up of vacation destination searching based on temperature can be seen in the code [here](/Vacation_Search/Vacation_Search.ipynb), with potential hotels being recorded [here](/Vacation_Search/WeatherPy_vacation.csv) and a sample investigation of the available locations is also depicted.

![vacationmap](/Vacation_Search/WeatherPy_vacation_map.png)


Finally, based on the four locations selected, it is possible to show a directional method of travel and specifics on where is being visited on the itinerary, whose code can be found [here](/Vacation_Itinerary/Vacation_Itinerary.ipynb)

![TravelMap](/Vacation_Itinerary/WeatherPy_travel_map.png)

![TravelInfo](/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
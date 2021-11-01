# World_Weather_Analysis

## Project Overview
Jack loves the PlanMyTrip app. Beta testers love it too. And, as with any new product, they’ve recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data you’ve already retrieved in this module. Then, you'll have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.

## Resources
- Data Source: OpenWeatherMap, Google Maps API
- Software: Matplotlib 3.3.4, Anaconda 4.10.3, Python 3.7.10, Git version 2.33.0.windows.2, Jupyter notebook.

## Process
### First 
1. Generated a set of 2,000 random latitudes and longitudes
2. Retrieved the nearest city
3. Performed an API call with the OpenWeatherMap. 
4. In addition to the city weather data gathered in this module, it was used the API skills to retrieve the current weather description for each city.
5. Finally it was created a new DataFrame containing the updated weather data.
### Second
7. Used input statements to retrieve customer weather preferences (70 min and 90 max).
8. It was used those preferences to identify potential travel destinations and nearby hotels.
9. It was showed those destinations on a marker layer map with pop-up markers.
### Third
11. Used the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations.
12. It was creared a marker layer map with a pop-up marker for each city on the itinerary.

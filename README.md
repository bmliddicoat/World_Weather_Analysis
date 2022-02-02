# World_Weather_Analysis

##  Overview
The PlanMyTrip app development has impressed the stakeholder (Jack).  Beta testers have been giving positive feedback on the progress.  Suggestions from beta tester to improve the app have been recommended.  The recommendations are adding weather description to the weather data and desire to create a travel itinerary.  These will be achieved by using Python, Pandas, Citipy, APIs (including addition of the Google Maps Direction API), and Jupyter Notebook.  The project will recreate a random set of 2000 longitudes and latitudes based off the prior beta development.  These datasets will then be used to find cities to create a data frame that includes city, longitude/latitude, maximum temperature, humidity percentage, cloudiness percentage, wind speed and weather description through an API call with the OpenWeatherMap.  This data frame will then be used to help with creating customer travel destination map.  The customer has decided that they are looking for vacation with temperatures between 70(°F) and 90(°F).  This input will be used to determine which cities meet the expectations of the customer.  After cities with coordinating temperatures are filtered, hotels will be found for each city.  The creation of a map with potential cities that have hotels that met the customer's temperature requirements will be produced.  The customer/beta tester after receiving the map has decided to travel to Brazil.  In looking at the map developed with hotels coordinating with the cities, it was determined that Trairi, Touros, Maragogi and Sobradinho are the cities which meet the client's standards.  Two maps will be created to show a travel route and map with the four cities including the pop-markers with hotel name suggestion, city, country, and current weather.  

## Results

### Customer Travel Destinations Map

Map with Pop-Up Markers
!alt text[https://github.com/bmliddicoat/World_Weather_Analysis/blob/33335a0e868238b567982ef955994e9d00ef74ed/Vacation_Search/WeatherPy_vacation_map.png]

The map created shows cities meeting the additional weather description.  This new information within the map will help clients decide which area to travel.  The random longitudes and latitudes count has been increased to 2000 to ensure a larger data frame for more choices for the client.  

### Travel Itinerary

Map Layered with Directions between cities.
!alt text
[https://github.com/bmliddicoat/World_Weather_Analysis/blob/33335a0e868238b567982ef955994e9d00ef74ed/Vacation_Itinerary/WeatherPy_travel_map.png]

The client decided that Trairi, Touros, Maragogi and Sobradinho were cities which they wanted to travel.  Trairi was assigned as the begining and ending destations.  Touros, Margogi and Sobradinho were the destinations that followed.  The map helps show a driving direction which can be taken for the trip to ensure each city is reached in correct order to increase efficiency within travel.  

Map with Pop-Up marker for each City on Travel
!alt text [https://github.com/bmliddicoat/World_Weather_Analysis/blob/33335a0e868238b567982ef955994e9d00ef74ed/Vacation_Itinerary/WeatherPy_travel_map_markers.png]
The map will give the client an easier interface to interact with the cities being traveled to for the vacation.  Cities that are not on itinerary have been removed.  The client will now have easier access to information desired for each city/hotel/weather.  

## Recommendations

During the development of PlanMyTrip, I have found areas that could improve users' experience and promote growth for that app.  Filters could be added to the app.  These filters could include hotel cost, nearby airport land possible "deals" from hotels.  This improvement could promote more user usage across multiple target markets.  PlanMyTrip could also develop business relationships with hotel companies which could promote growth for each business.  The PlanMyTrip can expand in the future to create interfaces for plane tickets, rental cars and activities associated with the city.  This expansion could promote growth for the company

# World Weather Analysis
## Overview of analysis
Jack and Beta testers love the PlanMyTrip app.  There were a few recommendations to take the app to the next level. Those recommendations were to add the weather description to the weather data that I had previously collected. In addition, I added input statement functionality so the beta testers can filter the weather data by their preferences. Their entries identify potential travel destinations and nearby hotels. From the list of potential travel destinations, beta testers chose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, I created a travel route between the four cities as well as a marker layer map.

## Results

<img src="https://user-images.githubusercontent.com/107224632/180352744-818ca0a5-175c-4fb9-acfc-f03025e636a5.png" width=80% height=80%><br />
*Figure 1: WeatherPy_Database.csv*<br />
* Created new set of 2,000 random latitudes and longitudes and got the nearest city using the citipy module.
* Performed an API call with the OpenWeatherMap to retrieve:
  * Latitude and longitude
  * Maximum temperature
  * Percent humidity
  * Percent cloudiness
  * Wind speed
  * Weather description (for example, clouds, fog, light rain, clear sky)

<img src="https://user-images.githubusercontent.com/107224632/180353302-14ebf5fc-7130-4a9d-aee7-1223406cac53.png" width=80% height=80%><br />
*Figure 2: Customer Travel Destinations Map*<br />
* Created a marker layer map with a pop-up marker for each city with the pop-up containing:
  * Hotel name
  * City
  * Country
  * Current weather description with the maximum temperature

<img src="https://user-images.githubusercontent.com/107224632/180354325-d506e310-e226-4b54-aa4a-4c184a8b894f.png" width=80% height=80%><br />
*Figure 3: Travel Itinerary Map*
* Created a directions layer map using the 4 cities chosen by the beta tester
  
<img src="https://user-images.githubusercontent.com/107224632/180354054-75b2f6cb-664d-4872-a8ab-b07d53c5de49.png" width=80% height=80%><br />
*Figure 4: Marker layer map with a pop-up marker for each city*
* Created a marker layer map with pop-up markers for each of the 4 cities chosen by the beta tester, each city with the following information on the pop-up:
  * Hotel name
  * City
  * Country
  * Current weather description with the maximum temperature

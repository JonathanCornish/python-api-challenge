# python-api-challenge
Python script that visualizes the weather across 500+ cities around the world of varying distance from the equator, using the OpenWeatherMap API &amp; Google Maps API.

The Python code randomly selects a group of 500+ cities across the world. Then, the code collects data from the OpenWeatherMap API to create a representatitve model of weather across world cities. The API data is used to graph the following relationships:

- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude

From the analysis, the following conclusions can be drawn:
Temperature seems to have a clear correlation with latitude
As expected, the weather becomes significantly warmer as one approaches the equator (0 Deg. Latitude). The southern hemisphere tends to be warmer this time of year than the northern hemisphere
There is no strong relationship between latitude and cloudiness. 
There is no strong relationship between latitude and wind speed. However, in northern hemispheres there is a flurry of cities with over 20 mph of wind
Wind speed tends to generally be betweeen 0 and 15 mph regardless of latitude
There is no strong relationship between latitude and humidity. However there is a slightly larger cluster of northern hemisphere cities with high humidity (above 60% humidity)

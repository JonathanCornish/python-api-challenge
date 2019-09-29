# python-api-challenge
Python script that visualizes the weather across 500+ cities around the world of varying distance from the equator, using the OpenWeatherMap API as well as the Python library 'citipy'.

The Python code randomly selects a group of 500+ cities from across the world. Then, the code collects data from the OpenWeatherMap API to create a representatitve model of weather across world cities. The API data is used to graph the following relationships:

- Temperature (C) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (kmph) vs. Latitude

From the analysis, the following conclusions can be drawn:
(1) Temperature is correlated with latitude - i.e the closer to the equator one is, the higher the temperature is likely to be. The weather becomes significantly warmer as one approaches the equator (0 Deg. Latitude). The southern hemisphere is perhaps marginally warmer this time of year than the northern hemisphere, although we have fewer data points for the southern hemisphere in this analysis than we do for the northern hemisphere.
(3) There is no strong relationship between latitude and cloudiness. 
(4) There is no strong relationship between latitude and wind speed.
(5) Wind speed tends to generally be betweeen 0 and 10 kmph regardless of latitude.
(6) There is no strong relationship between latitude and humidity. However most areas tend to have humidity above 40% this time of year.

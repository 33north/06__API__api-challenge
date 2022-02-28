# 06__API__api-challenge
06__API__api-challenge

For this project, random locations all-around the world were generated and weather information for each location needed to be found and logged into a dataframe.


## Part 1
The OpenWeather API was used to gather the following:
  - temperature
  - humidity
  - cloudiness
  - wind speed
Note: this data was pulled at the time of the API call so results may vary if ran in the future.

The weather data was split up between the norther and southern hemisphere.

From the weather data, linear regression was done on the relationships between
  - Northern Hemisphere - Temperature (F) vs. Latitude
  - Southern Hemisphere - Temperature (F) vs. Latitude
  - Northern Hemisphere - Humidity (%) vs. Latitude
  - Southern Hemisphere - Humidity (%) vs. Latitude
  - Northern Hemisphere - Cloudiness (%) vs. Latitude
  - Southern Hemisphere - Cloudiness (%) vs. Latitude
  - Northern Hemisphere - Wind Speed (mph) vs. Latitude
  - Southern Hemisphere - Wind Speed (mph) vs. Latitude

## Part 2
The weather data gathered in part 1 was used to help plan future vacations based on desired weather conditions.

Narrowed desired weather conditions to the following:
  - A max temperature lower than 80 degrees but higher than 70.
  - Wind speed less than 10 mph.
  - Zero cloudiness.
  - Within the United States.

From there a google heatmap was generated displaying the humidity of the locations found in part 1.
The heatmap also displays the hotels that are nearest the cities that meet the desired weather conditions.

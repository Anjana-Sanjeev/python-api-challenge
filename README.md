# python-api-challenge


# Summary of WeatherPy


* For this analysis the OpenWeatherMap API key was used along with citipy to find the different weather parameters (maximum temperature, humidity, cloudiness and wind speed) of random cities within a latitude and longitude range.


* Scatter plot and linear regression model was plotted to find the correlation between the latitude of the cities and the different weather parameters.


# Summary of VacationPy


* Using the cities cvs file created from the WeatherPy script, a map visualization is created for every city with respect to humidity.


* Then ideal weather cities are selected and using Geoapify API key, the the first hotel located within 10,000 metres of the coordinates are found. Then again a map visualization is created which shows the hotel name as well.

# Output Data


* The following figues are added into the output data folder


    1) Latitude vs. Temperature
    2) Latitude vs. Humidity
    3) Latitude vs. Cloudiness
    4) Latitude vs. Wind Speed
    5) Northern Hemisphere: Temperature (C) vs. Latitude
    6) Southern Hemisphere: Temperature (C) vs. Latitude
    7) Northern Hemisphere: Humidity (%) vs. Latitude
    8) Southern Hemisphere: Humidity (%) vs. Latitude
    9) Northern Hemisphere: Cloudiness (%) vs. Latitude
    10) Southern Hemisphere: Cloudiness (%) vs. Latitude
    11) Northern Hemisphere: Wind Speed (m/s) vs. Latitude
    12) Southern Hemisphere: Wind Speed (m/s) vs. Latitude
    13) City Map Visualization
    14) Hotel Map Visualization
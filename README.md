
# python-api-challenge 
#### Use data's true power to answer questions definitively.







## Part I - WeatherPy
Create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, you'll be utilizing a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities. Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
Perform a weather check on each of the cities using a series of successive API calls.
Include a print log of each city as it's being processed with the city number and city name.
Save a CSV of all retrieved data and a PNG image for each scatter plot.

    1. Build a series of scatter plots to showcase the following relationships:
        > Temperature (F) vs. Latitude
        > Humidity (%) vs. Latitude
        > Cloudiness (%) vs. Latitude
        > Wind Speed (mph) vs. Latitude
    2. Run linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):
        > Northern Hemisphere - Temperature (F) vs. Latitude
        > Southern Hemisphere - Temperature (F) vs. Latitude
        > Northern Hemisphere - Humidity (%) vs. Latitude
        > Southern Hemisphere - Humidity (%) vs. Latitude
        > Northern Hemisphere - Cloudiness (%) vs. Latitude
        > Southern Hemisphere - Cloudiness (%) vs. Latitude
        > Northern Hemisphere - Wind Speed (mph) vs. Latitude
        > Southern Hemisphere - Wind Speed (mph) vs. Latitude

## Part II - VacationPy
    1. Create a heat map that displays the humidity for every city generated from Part I - WeatherPy.

    2. Narrow down the DataFrame to find your ideal weather conditions below:

        > A max temperature lower than 80 degrees but higher than 70.
        > Wind speed less than 10 mph.
        > Zero cloudiness.
    3. Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.

        > Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.

## Additional tasks before project
    > Install citypy in your python environment (https://pypi.python.org/pypi/citipy)
    > OpenWeatherMap API Key (https://openweathermap.org/) as 'weather_api_key'
    > Google API Key (https://console.developers.google.com/getting-started) as 'g_key'
    > Create API Keys and store it in the 'api_keys.py' file before running the Jupyter notebooks.

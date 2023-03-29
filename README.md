# python-api-challenge

Sean Guzman

Rutgers Data Sciences Bootcamp, Module 6 Challenge (03 April 2023)

This two-part challenge showcases the use of APIs within

The first part of this challenge, WeatherPy, uses Open Weather API, where weather data is obtained from a randomly generated list of about 600 cities around the world along with each city's coordinates and then outputted to a csv file for the second part of this challenge. 

Multiple graphs are created from this data to identify trends and relationship between the following:
- Latitude vs. Temperature
- - Latitude vs. Humidity
    - Latitude vs. Cloudiness
    - Latitude vs. Wind Speed
    - Northern Hemisphere: Temperature vs. Latitude
    - Southern Hemisphere: Temperature vs. Latitude
    - Northern Hemisphere: Humidity vs. Latitude
    - Southern Hemisphere: Humidity vs. Latitude
    - Northern Hemisphere: Cloudiness vs. Latitude
    - Southern Hemisphere: Cloudiness vs. Latitude
    - Northern Hemisphere: Wind Speed vs. Latitude
    - Southern Hemisphere: Wind Speed vs. Latitude

The second part of this challenge, VacationPy, takes the outputted csv file from the first challenge and each city's coordinates on a map utilizing hvplot.pandas. The list of cities are then filtered down by "ideal" weather conditions, where Geoapify API is then used to find a hotel in each city within a 10,000 meter radius. Each city is then placed again on a map, and when hovering over each city, the country and the hotel's name is displayed.

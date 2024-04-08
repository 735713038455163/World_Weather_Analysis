# World_Weather_Analysis

## Basic Project Plan
Here's an outline of the project plan:

![TableofContent](https://github.com/735713038455163/World_Weather_Analysis/blob/master/Weather_Database/TableofContent.PNG)

In this module we are learning:
-	Perform tasks using new Python libraries and modules.
-	Retrieve and use data from an API "get" request to a server.
-	Retrieve and store values from a JSON array.
-	Use try and except blocks to resolve errors.
-	Write Python functions.
-	Create scatter plots using the Matplotlib library, and apply styles and features to a plot.
-	Perform linear regression, and add regression lines to scatter plots.
-	Create heatmaps, and add markers using the Google Maps API.

-Task: Collect and analyze weather data across cities worldwide.
-Purpose: PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.
-Method: Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.

The analysis of the data will be split into three main parts, or stages.

# Collect the Data
1[API Call](https://github.com/735713038455163/World_Weather_Analysis/blob/master/weather_data/API%20Call.PNG)
![Collect the Data_readme](https://github.com/735713038455163/World_Weather_Analysis/blob/master/Weather_Database/Collect%20the%20Data_readme.PNG)

- Use the NumPy module to generate more than 1,500 random latitudes and longitudes.
- Use the citipy module to list the nearest city to the latitudes and longitudes.
- Use the OpenWeatherMap API to request the current weather data from each unique city in your list.
- Parse the JSON data from the API request.
- Collect the following data from the JSON file and add it to a DataFrame:
- City, country, and date
- Latitude and longitude
- Maximum temperature
- Humidity
- Cloudiness
- Wind speed

# Exploratory Analysis with Visualization

# Create scatter plots of the weather data for the following comparisons:
- Latitude versus temperature
- Latitude versus humidity
- Latitude versus cloudiness
- Latitude versus wind speed

![Fig1](https://github.com/735713038455163/World_Weather_Analysis/blob/master/weather_data/Fig1.png)
![Fig2](https://github.com/735713038455163/World_Weather_Analysis/blob/master/weather_data/Fig2.png)
![Fig3](https://github.com/735713038455163/World_Weather_Analysis/blob/master/weather_data/Fig3.png)
![Fig4](https://github.com/735713038455163/World_Weather_Analysis/blob/master/weather_data/Fig4.png)
# Determine the correlations for the following weather data:

![NumPy,CityPY,OpenWeatherMap,JSON](https://github.com/735713038455163/World_Weather_Analysis/blob/master/Weather_Database/NumPy%2CCityPY%2COpenWeatherMap%2CJSON.PNG)
![loop](https://github.com/735713038455163/World_Weather_Analysis/blob/master/Weather_Database/loop.PNG)

- Latitude and temperature
- Latitude and humidity
- Latitude and cloudiness
- Latitude and wind speed


# Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences. Complete these steps:

- Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
- Create a heatmap for the new DataFrame.
- Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.
- Store the name of the first hotel in the DataFrame.
- Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city.

![WeatherPy_Vacation_Map](https://github.com/735713038455163/World_Weather_Analysis/blob/master/Vacation_Search/WeatherPy_Vacation_Map.PNG)
![WeatherPy_Travel_Map_Markers with Hotel](https://github.com/735713038455163/World_Weather_Analysis/blob/master/Vacation_Itinerary/WeatherPy_Travel_Map_Markers%20with%20Hotel.PNG)
![WeatherPy_Travel_Map_Markers](https://github.com/735713038455163/World_Weather_Analysis/blob/master/Vacation_Itinerary/WeatherPy_Travel_Map_Markers.PNG)
![WeatherPy_Travel_Map](https://github.com/735713038455163/World_Weather_Analysis/blob/master/Vacation_Itinerary/WeatherPy_Travel_Map.PNG)



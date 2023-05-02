# WeatherApp

This is a weather app created using Python, Tkinter, Geopy.geocoders, Timezonefinder, Requests, and Pytz. It allows the user to enter a location and get the current weather conditions for that location.

# Features

- Enter any location in the world and get the current weather conditions
- The app uses the Geopy.geocoders library to convert the location entered by the user into latitude and longitude coordinates
- The app uses the Timezonefinder library to determine the timezone of the location entered by the user
- The app uses the Requests library to make an API call to OpenWeatherMap to get the current weather conditions for the location entered by the user
- The app uses the Pytz library to convert the time returned by OpenWeatherMap to the local time of the location entered by the user

# Installation

1. Clone this repository 
2. Install the required packages using pip:
```shell
pip install tkinter
pip install geopy
pip install timezonefinder
pip install datetime
```

# Usage

1. Run the WeatherApp.py file.
2. Enter a location in the **Location** entry box.
3. Click the **Get Weather/Search** button to get the current weather conditions for the location entered.

# Credits

1. [OpenWeather](https://openweathermap.org/)
2. [OpenWeather Api](https://openweathermap.org/api)
3. [Tkinter](https://docs.python.org/3/library/tkinter.html)
4. [Geopy](https://geopy.readthedocs.io/en/stable/#geocoders)

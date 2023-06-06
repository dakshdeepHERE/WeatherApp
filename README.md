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

# How to run the project in local system
- First fork this repository from the option given at the top of this page.
- Now clone the forked repository by running this command in the terminal:
  - ```
    git clone https://github.com/<your-username>/OpenWeather.git
    ``` 
- Either create an android emulator or connect a physical device to run the project.
- Now get to the root of your Flutter project using :
  - ```
    cd <name of your root>
    ```
- Run this command from the root of your Flutter project or simply press Ctrl + F5:
  - ```
    flutter run
    ```
- The project is all set up now!
# How to Contribute
Now that the project is properly setup, follow these steps to make your first contribution :
- Fork this repository by clicking on the fork button on the top of this page. This will create a copy of this repository in your account.
- Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the copy to clipboard icon.
- Open a terminal and run the following git command:
  - ```
    git clone "url you just copied"
    ```
    - Above where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.
      
  - For example:
    - ```
      git clone https://github.com/your_username/WeatherApp.git
      ```
- Now create a branch using the 'git switch' command in repository directory:
  -   ```
      git switch -c your-new-branch-name
      ```
- Make necessary changes and commit those changes. Add those changes to the branch you just created using the 'git add' command:
  -   ```
      git add .
      ```
    Now commit those changes using the 'git commit' command:
      ```
      git commit -m "Add your title here"
      ```
- Push your changes using the command git push:
  -   ```
      git push -u origin your-branch-name
      ```
      replacing your-branch-name with the name of the branch you created earlier.


# Credits

1. [OpenWeather](https://openweathermap.org/)
2. [OpenWeather Api](https://openweathermap.org/api)
3. [Tkinter](https://docs.python.org/3/library/tkinter.html)
4. [Geopy](https://geopy.readthedocs.io/en/stable/#geocoders)

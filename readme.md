# 03-06 - Weather App

API Exercise for codingschule



<img src="/screenshot_wetterapp.png">

## Tasks

Modify the variable city to a city of your choice.

    To retrieve the current weather data for a city, you need to query the following URL:
    https://api.openweathermap.org/data/2.5/weather?q={city name}&appid={API key}
    To avoid errors with special characters in the city name, you should encode the city (string) using the encodeURI() method.
    You can find further details on the API query here. Use the Fetch API method to retrieve the data and process it using json(), following the example for the CatAPI.

    Replace the respective fields in the HTML template with the information from the API response. You can find more information about the icons here. Additionally, update the timestamp of the data. JavaScript provides predefined methods for this purpose.

    Implement a function to refresh the data every 10 seconds.

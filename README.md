# Android-Weather-App

This Android application provides weather information for your city. It fetches weather data from the OpenWeatherMap API, which provides real-time weather data and forecasts for various locations worldwide.

## Features

- Current Weather: The app displays the current weather conditions including temperature, humidity, wind speed, and weather description for the selected city.
- Forecast: It provides a 5-day weather forecast, showing the expected weather conditions for each day.
- Search: Users can search for their city by name to get weather information specific to their location.

## API Integration

The app integrates with the OpenWeatherMap API to retrieve weather data. The API provides a variety of endpoints to access weather information, including current weather data, forecasts, and historical data. The app sends HTTP requests to the API endpoints and receives JSON responses, which are then parsed to extract the required weather information.

To use the OpenWeatherMap API, you need to sign up for an API key on their website. This key is required to authenticate your requests and ensure that you have access to the weather data.

## Technologies Used

- Android Studio: The app is developed using Android Studio, the official integrated development environment (IDE) for Android app development.
- Java: The programming language used for developing the Android app.
- OpenWeatherMap API: The API is used to fetch weather data for the app.
- JSON Parsing: The app parses the JSON responses received from the API to extract the necessary weather information.

## Installation

To run the app on your Android device or emulator, follow these steps:

1. Clone or download the project from the repository.
2. Open the project in Android Studio.
3. Obtain an API key from OpenWeatherMap and replace the placeholder key in the code with your actual API key.
4. Build and run the app on your device or emulator.

Please note that an active internet connection is required to fetch weather data from the API.

For more information about the OpenWeatherMap API, visit their [official website](https://openweathermap.org/api).


Example:
![screen1](screen/screen1.png)
![screen2](screen/screen2.png)
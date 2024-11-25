# Weather App

A simple weather forecasting app built using React Native and Expo. It fetches weather data from the WeatherAPI and provides users with current weather conditions and forecasts for specific cities.

## Features
- View current weather data and forecasts.
- Search for cities and display relevant weather information.
- Displays weather-related images based on conditions (e.g., sunny, cloudy, rain).

## Technologies Used
- **React Native**: Framework for building native mobile apps.
- **Expo**: Development environment and toolset for React Native apps.
- **React Navigation**: For navigating between screens.
- **Axios**: For making API requests.
- **TailwindCSS**: For styling.

## Setup

1. Clone the repository:

   ```bash
   git clone <repo_url>

2. Install dependencies:

    ```bash

    npm install

3. Run the app on Android:

    ```bash

    expo start --android
    Or on iOS:

    ```bash
    Copy code
    expo start --ios

## Files Overview
- src/api/weather.js: Contains functions for fetching weather data from the WeatherAPI.
- src/constants/index.js: Stores the API key and weather-related images.
- src/navigation/AppNavigation.js: Manages the app's navigation.
- src/screens/HomeScreen.js: Displays the home screen with weather details.
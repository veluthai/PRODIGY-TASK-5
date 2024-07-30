# Weather App

A simple weather application that fetches weather data based on the user's location or a user-inputted location. The application uses the OpenWeatherMap API to retrieve and display current weather conditions.

## Features

- Fetch weather data based on the user's location.
- Fetch weather data based on a user-inputted location.
- Display current weather conditions, temperature, humidity, and wind speed.

## Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeatherMap API

## Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/weather-app.git
    cd weather-app
    ```

2. Open `index.html` in your preferred web browser.

## Usage

1. Enter a location in the input field and click the "Get Weather" button to fetch weather data for the entered location.

2. Click the "Use My Location" button to fetch weather data based on your current geographic location.

## API Key

This application uses the OpenWeatherMap API. You will need to obtain an API key from [OpenWeatherMap](https://openweathermap.org/api) and replace `YOUR_OPENWEATHERMAP_API_KEY` in the `script.js` file with your actual API key.

```javascript
const apiKey = 'YOUR_OPENWEATHERMAP_API_KEY';

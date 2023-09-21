
# React Weather App

This is a simple React weather app that allows you to search for weather information for a specific location. It fetches weather data from the OpenWeatherMap API and displays the current temperature, location, humidity, and wind speed.

## Preview

https://github.com/SimonHoefling/weather_app_1.0/assets/100227595/d4274f79-dd73-48ef-9e79-e072e9eaa71e

## Features

- Search for weather information by entering a city name.
- Display the current temperature in Celsius.
- Show the location name.
- Show humidity percentage.
- Show wind speed in kilometers per hour.


## Prerequisites
Before you start, make sure you have the following:


- Node.js installed on your machine.
- An API key from OpenWeatherMap to fetch weather data.


## Installation

1. Clone the repository:
```bash
git clone https://github.com/SimonHoefling/weather_app_1.0
```

2. Navigate to the project directory:
```bash
cd weather_app_1.0
```

3. Install the required dependencies:
```bash
npm install
```

4. Create a .env.local file in the root directory of your project and store your API key as follows:
```bash
REACT_APP_WEATHER_API_KEY=your_api_key_here
```

5. Start the development server:
```bash
npm start
```

6. Open your web browser and visit http://localhost:3000 to use the weather app.

## Usage

1. Enter the name of the city for which you want to check the weather in the search input field.

2. Click on the search icon to fetch and display the weather information.

3. The app will display the current temperature, location, humidity, and wind speed.

4. The weather icon will change based on the weather conditions.

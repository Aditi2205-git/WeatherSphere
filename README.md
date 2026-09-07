# 🌦️ WeatherSphere Pro 

A modern, responsive weather dashboard built with HTML, CSS, and JavaScript, providing real-time weather data, forecasts, air-quality information, interactive analytics, maps, and personalized weather insights.

## 🚀 Live Demo

🔗 GitHub Pages: Add your deployed link here

## 📌 Overview

WeatherSphere Pro 4.0 is a web-based weather dashboard designed to provide weather information through a clean and interactive interface.

The application uses the Open-Meteo API ecosystem to retrieve weather, geocoding, and air-quality data without requiring an API key.

The project focuses on responsive web development, API integration, dynamic UI updates, data visualization, browser storage, and interactive user features.

## ✨ Features

### 🌍 Current Weather

- Search weather by city
- Detect weather using current location
- Current temperature and feels-like temperature
- Humidity
- Wind speed and direction
- Atmospheric pressure
- Cloud cover
- Precipitation
- Visibility
- Sunrise and sunset
- UV Index
- Dynamic weather condition display

### 📅 Weather Forecast

- 24-hour hourly forecast
- 7-day forecast
- Temperature information
- Humidity levels
- Rain probability
- Weather condition indicators
- Daily maximum and minimum temperatures

### 🌫️ Air Quality

- Air Quality Index (AQI)
- PM2.5
- PM10
- Carbon monoxide
- Nitrogen dioxide
- AQI classification

### 📊 Weather Analytics

Interactive charts powered by Chart.js:

- Temperature trends
- Humidity trends
- Wind speed
- Atmospheric pressure

### 🗺️ Interactive Weather Map

Powered by Leaflet.js and OpenStreetMap.

- Location-based map
- Current weather location marker
- Interactive map navigation
- City-based location updates

### ❤️ Personalization

- Favorite cities
- Recent search history
- Local Storage based browser persistence
- Celsius/Fahrenheit temperature switching
- Dark/light theme toggle

### 🎤 Voice Search

Search for cities using the browser's Speech Recognition API where supported.

### 🌦️ Smart Weather Insights

Provides rule-based recommendations based on current weather conditions, including:

- Heat and hydration advice
- Rain preparation
- Outdoor activity suggestions
- Basic weather-related health guidance

### 🌐 Additional Features

- Weather information for selected major world cities
- Live local time and date
- Dynamic weather backgrounds
- Loading screen
- Error handling and retry functionality
- Offline/online connection indicator
- Mobile navigation
- Responsive design for different screen sizes

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Styling, animations and responsive design |
| JavaScript ES6+ | Application logic and API integration |
| Chart.js | Weather data visualization |
| Leaflet.js | Interactive maps |
| Local Storage | Favorites and search history |

## 📡 APIs

### Open-Meteo Weather API

Used for:

- Current weather conditions
- Hourly weather data
- Daily forecasts
- Temperature
- Humidity
- Wind
- Pressure
- Precipitation
- UV index
- Sunrise and sunset

### Open-Meteo Geocoding API

Used for:

- City search
- Latitude and longitude lookup
- Reverse geocoding for current location

### Open-Meteo Air Quality API

Used for:

- AQI
- PM2.5
- PM10
- Carbon monoxide
- Nitrogen dioxide

## 📱 Responsive Design

The dashboard is designed to work across:

- Desktop
- Laptop
- Tablet
- Mobile devices

## 🧪 Manual QA Testing

Manual QA testing was performed separately on WeatherSphere Pro to validate its functionality, UI behavior, input handling, responsive behavior, and user workflows.

### Test Execution Summary

| Metric | Result |
|---|---:|
| Total Test Cases | 30 |
| Passed | 28 |
| Failed | 1 |
| Needs Review | 1 |
| Confirmed Defects | 3 |

The testing cycle identified and documented three defects covering favorite button functionality, light-mode readability, and empty search input handling.

Defect severity, priority, reproduction steps, expected results, actual results, and retesting evidence were documented as part of the QA testing process.

## 📂 Project Structure

```text
WeatherSphere-Pro/
│
├── index.html
├── style.css
├── script.js
└── README.md

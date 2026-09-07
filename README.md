# 🌦️ WeatherSphere

A modern, responsive weather dashboard built with HTML, CSS, and JavaScript, providing real-time weather data, forecasts, air-quality information, interactive analytics, maps, and weather-based insights.

## 🚀 Live Demo

🔗 **GitHub Pages:** https://aditi2205-git.github.io/WeatherSphere/

---

## 📌 Overview

**WeatherSphere** is a web-based weather dashboard designed to provide detailed and interactive weather information through a clean and responsive interface.

The application integrates the **Open-Meteo API ecosystem** to retrieve weather, geocoding, and air-quality data without requiring an API key.

The project focuses on responsive web development, API integration, dynamic UI updates, data visualization, browser storage, and interactive user features.

---

## ✨ Features

### 🌍 Current Weather

- Search weather by city
- Detect weather using current location
- Current temperature
- Feels-like temperature
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

Interactive data visualization powered by **Chart.js**.

Includes:

- Temperature trends
- Humidity trends
- Wind speed
- Atmospheric pressure

### 🗺️ Interactive Weather Map

Powered by **Leaflet.js** and **OpenStreetMap**.

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

Search for cities using browser-based Speech Recognition where supported.

### 🌦️ Smart Weather Insights

Provides rule-based recommendations based on current weather conditions, including:

- Heat and hydration advice
- Rain preparation
- Outdoor activity suggestions
- Basic weather-related health guidance

### 🌐 Additional Features

- Weather information for selected major world cities
- Live clock
- Dynamic weather backgrounds
- Loading screen
- Error handling and retry functionality
- Offline/online connection indicator
- Mobile navigation
- Responsive design for different screen sizes

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Styling, animations and responsive design |
| JavaScript ES6+ | Application logic and API integration |
| Chart.js | Weather data visualization |
| Leaflet.js | Interactive maps |
| Local Storage | Favorites and search history |

---

## 📡 APIs

### Open-Meteo Weather API

Used for:

- Current weather conditions
- Hourly weather data
- Daily forecasts
- Temperature
- Humidity
- Wind
- Atmospheric pressure
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

- Air Quality Index
- PM2.5
- PM10
- Carbon monoxide
- Nitrogen dioxide

---

## 📱 Responsive Design

WeatherSphere is designed to work across:

- Desktop
- Laptop
- Tablet
- Mobile devices

The interface was also manually tested at a smaller screen size to verify layout and usability.

---

## 🧪 Manual QA Testing

Manual QA testing was performed separately on **WeatherSphere** to validate its functionality, UI behavior, input handling, responsive behavior, and user workflows.

### Test Execution Summary

| Metric | Result |
|---|---:|
| Total Test Cases | 30 |
| Passed | 28 |
| Failed | 1 |
| Needs Review | 1 |
| Confirmed Defects | 3 |

The testing cycle identified and documented **three confirmed defects** related to:

- Favorite button functionality
- Light-mode readability
- Empty search input handling

Defect severity, priority, reproduction steps, expected results, actual results, and retesting evidence were documented as part of the QA testing process.

One of the identified defects was also tracked through **Jira** and subsequently retested.

---

## 📂 Project Structure

```text
WeatherSphere/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## ▶️ Getting Started

1. Clone or download the repository.
2. Open the project folder.
3. Open `index.html` in a modern web browser.
4. Search for a city or use the current-location option.
5. Explore weather forecasts, analytics, air quality, maps, favorites, and other dashboard features.

No API key is required for the Open-Meteo APIs used by the project.

---

## 🎯 Project Purpose

WeatherSphere was developed as a portfolio web application to practice:

- Frontend development
- REST API integration
- Dynamic DOM manipulation
- Data visualization
- Browser Local Storage
- Responsive UI development
- Manual software testing
- Test case design
- Defect reporting
- QA documentation

---

## 👩‍💻 Author

**Aditi Singh**

B.Tech Computer Science Engineering Student

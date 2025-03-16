# 🌦️ Weather App

A simple weather app that provides real-time weather information based on city search or user location.

## 🚀 Features
- 🌍 Search weather by city name
- 📍 Get weather based on your location
- 🌡️ Temperature, humidity, and wind speed details
- 🎨 Responsive and user-friendly UI

## 🛠️ Technologies Used
- HTML5, CSS3, JavaScript
- OpenWeather API 🌍
- Geolocation API 📍

## 📷 Screenshots
![Weather App UI](img/screenshot.png)

## 📦 Setup & Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/weather-app.git
   ```
2. Navigate to the project folder:
   ```sh
   cd weather-app
   ```
3. Open `index.html` in a browser.

## 🔑 API Key Configuration
Replace `apiKey` in `script.js` with your OpenWeather API key:
```js
const apiKey = "your_api_key_here";
```

## 📜 Code Overview
### HTML (`index.html`)
- Structure of the weather app
- Input field for city search
- Display weather details

### CSS (`style.css`)
- Styling for a modern UI

### JavaScript (`script.js`)
- Fetches weather data from OpenWeather API
- Uses Geolocation API to get the user's location
- Dynamically updates the UI based on weather conditions

## 🖥️ Usage
1. 🔍 Enter a city name and click the search button.
2. 🌍 If geolocation is enabled, the app fetches the weather of your current location.
3. 📊 View temperature, humidity, and wind speed details.

## ❗ Troubleshooting
- Ensure you have an active internet connection 🌐.
- If the weather data doesn't appear, check the browser console for errors 🛠️.
- Make sure your API key is valid and correctly set.

## 🤝 Contributing
Pull requests are welcome! 🎉

## 📜 License
This project is licensed under the MIT License 📄.
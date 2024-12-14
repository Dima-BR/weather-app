# 🌤️ Weather App

A simple, responsive Weather App built using **HTML**, **CSS (Bootstrap 5)**, and **JavaScript**. This app fetches real-time weather data for any city entered by the user and displays a 3-day weather forecast.

![Weather App Screenshot](./screenshot.png)

---

## 🚀 Features
- **Search for a City**: Enter any city name to fetch and display weather data.
- **Default Location**: On first load, the app shows the weather in **Cairo**.
- **Current and 3-Day Forecast**: Displays temperature, weather conditions, humidity, and wind speed.
- **Responsive Design**: Works perfectly on all devices (Bootstrap 5).
- **Keyboard Shortcut**: Press `Enter` to trigger the search functionality.

---

## 🛠️ Technologies Used
- **HTML5**: Structure of the app.
- **CSS3**: Styling using Bootstrap 5 for responsiveness and layout.
- **JavaScript**: Logic to fetch and display weather data dynamically.
- **WeatherAPI**: Provides the real-time weather data. (https://www.weatherapi.com/)

---

## 🌐 Live Demo
You can view the live demo of the app here:
[Weather App Live Demo](#)

---

## 📋 Setup Instructions
To run this project locally, follow these steps:

1. **Clone the Repository**
```bash
https://github.com/your-username/weather-app.git
```

2. **Open the Project**
Navigate to the project directory and open `index.html` in your browser.

3. **Setup Weather API**
   - Create an account on [WeatherAPI](https://www.weatherapi.com/).
   - Generate an **API Key**.
   - Replace `YOUR_API_KEY` in your JavaScript file:

   ```javascript
   const API_KEY = 'YOUR_API_KEY';
   ```

4. **Enjoy!**
Start searching for your favorite cities and see their weather!

---

## 📂 Project Structure
```bash
weather-app/
├── index.html        # Main HTML file
├── style.css         # Custom CSS (Bootstrap 5 included)
├── script.js         # JavaScript for API calls and DOM manipulation
├── screenshot.png    # App screenshot
└── README.md         # Documentation
```

---

## 🖥️ How It Works
1. **Search Functionality**:
   - Input any city name in the search bar.
   - Press the **Find** button or hit **Enter** to fetch data.
2. **API Integration**:
   - Uses `WeatherAPI` to retrieve the current and next 2 days' weather forecasts.
3. **Dynamic Display**:
   - Weather data is dynamically displayed in responsive cards.

---

## 🔑 Key Highlights
- The cards are clean and compact.
- The city name dynamically appears as a title above the weather cards.
- Enter key press is linked to the **Find** button for a smoother experience.

---

## 💡 Future Enhancements
- Add user location detection using the **Geolocation API**.
- Support for hourly weather forecasts.
- Include more weather details like sunrise/sunset times.


**Enjoy Checking the Weather Anywhere in the World! 🌎**

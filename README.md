# 🌤 Weather App

A lightweight, responsive web application that displays current weather conditions for any city worldwide. Built with vanilla HTML, CSS, and JavaScript, utilizing the OpenWeatherMap API.

## ✨ Features

- **City Search**: Instantly look up weather by city name.
- **Live Data**: Displays current temperature (°C), weather description, and dynamic icons.
- **Responsive UI**: Modern, card-based interface that adapts to mobile and desktop screens.
- **User Feedback**: Handles errors gracefully (e.g., city not found) and supports "Enter" key submission.

## 🛠️ Technologies

- **Frontend**: HTML5, CSS3
- **Scripting**: JavaScript (ES6+)
- **API**: [OpenWeatherMap Current Weather Data](https://openweathermap.org/current)

## 🚀 Getting Started

1. **Download**: Clone this repository or download the `index.html` file.
2. **Run**: Simply open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
3. **Use**: Type a city name (e.g., "London", "Tokyo") and press Enter.

## 🔑 API Configuration

The file comes with a demo API key. For consistent usage or to avoid rate limits, it is recommended to use your own key:

1. Register for a free account at OpenWeatherMap.
2. Generate an API Key.
3. Open `index.html` in a code editor.
4. Replace the value of `const API_KEY` inside the script tag:
   ```javascript
   // Replace with your own OpenWeatherMap API key
   const API_KEY = "YOUR_NEW_API_KEY";
   ```

## 📸 Usage Example

1. Enter "New York" in the input field.
2. Click "Get Weather".
3. View the temperature and weather conditions instantly.

---
*Created for educational purposes.*
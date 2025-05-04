# Wingling_Weather
A responsive weather website built using JavaScript and a weather API to fetch real-time data. Allows users to search and view weather conditions for cities around the world with ease.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

- How It Works

1. **User Input**  
   The user enters a **city name** in the search bar.

2. **API Integration**  
   The app uses the [OpenWeatherMap API](https://openweathermap.org/api) to fetch weather data:
   - You register for a free API key from OpenWeatherMap.
   - The app builds a URL like:  
     ```bash
     https://api.openweathermap.org/data/2.5/weather?q={city}&appid={YOUR_API_KEY}&units=metric
     ```
   - This API returns a JSON object containing real-time weather conditions such as temperature, humidity, wind speed, and a weather description.

3. **Data Display**  
   Once the response is received:
   - The JavaScript file (`WinglingWeather.js`) parses the JSON.
   - It extracts relevant fields like temperature, weather description, and icon.
   - The HTML DOM is dynamically updated to reflect the data using JavaScript.

4. **Responsive UI**  
   The CSS file (`WinglingWeather.css`) ensures the layout adjusts gracefully across devices and screen sizes.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

- Project Structure

```bash
Wingling_Weather/
│
├── Images/                 # Contains icons or background images
├── WinglingWeather.html    # Main HTML structure
├── WinglingWeather.css     # Styling and layout for the UI
├── WinglingWeather.js      # Core JavaScript logic and API interaction
└── README.md               # Project overview and documentation
```

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

- Features

<> Real-time weather data for any **city worldwide**
<> Temperature in Celsius
<> Weather condition icons and descriptions
<> Responsive layout for mobile and desktop

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

- Tech Stack

- HTML5  
- CSS3  
- JavaScript  
- OpenWeatherMap API

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

- How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Praneeth1265/Wingling_Weather.git
   ```
2. Get your API key from [OpenWeatherMap](https://openweathermap.org/).
3. Open `WinglingWeather.js` and replace:
   ```js
   const apiKey = "YOUR_API_KEY";
   ```
4. Open `WinglingWeather.html` in your browser and test it!

# Weather Whisperer

A sleek, user-friendly weather application built with **React**, **Bootstrap**, and **Axios** that provides current weather data and a 5-day forecast for any city worldwide. The app features day and night themes, weather-specific icons, and a responsive design to ensure a seamless experience across devices.

---

## Features

1. **Real-Time Weather Updates**:

   - Displays the current temperature, weather conditions, wind speed, and location.

2. **5-Day Forecast**:

   - Showcases daily weather predictions with dates, days, temperatures, and icons representing the forecasted conditions.

3. **Dynamic Themes**:

   - Toggle between light and dark modes with smooth transitions.

4. **Interactive UI**:

   - Responsive design with hover effects, animations, and a clean, modern look.

5. **Weather-Specific Icons**:
   - Displays appropriate icons for various weather conditions like sunny, rainy, stormy, and cloudy.

---

## Tech Stack

- **Frontend**: React, Bootstrap, React Icons
- **API**: OpenWeatherMap API
- **HTTP Client**: Axios
- **Animations**: Framer Motion
- **Styling**: CSS (with a focus on dark mode and neumorphic design)

---

## Installation and Setup

### Prerequisites

Ensure you have the following installed:

- Node.js (v14 or higher)
- npm or yarn

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/weather-whisperer.git
   cd weather-whisperer
   ```

2. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

3. Get an API key from [OpenWeatherMap](https://openweathermap.org/):

   - Sign up or log in.
   - Navigate to the API section and generate an API key.

4. Create a `.env` file in the root directory and add your API key:

   ```env
   REACT_APP_WEATHER_API_KEY=your_api_key_here
   ```

5. Start the development server:

   ```bash
   npm start
   # or
   yarn start
   ```

6. Open your browser and visit: `http://localhost:3000`

---

## Usage

1. Enter the name of a city in the search bar.
2. View the current weather conditions for the city.
3. Scroll to see the 5-day forecast with dates, temperatures, and icons.
4. Toggle between light and dark themes using the theme switcher.

---

## Screenshots

### Home Page

![Home Page Screenshot](https://via.placeholder.com/600x400?text=Add+your+screenshot)

### Dark Mode

![Dark Mode Screenshot](https://via.placeholder.com/600x400?text=Add+your+screenshot)

---

## API Integration

This project uses the [OpenWeatherMap API](https://openweathermap.org/) to fetch weather data. Ensure you adhere to their usage policies and rate limits.

### Endpoints Used:

1. **Current Weather Data**:

   ```
   https://api.openweathermap.org/data/2.5/weather?q={city_name}&appid={API_KEY}&units=metric
   ```

2. **5-Day Forecast**:
   ```
   https://api.openweathermap.org/data/2.5/forecast?q={city_name}&appid={API_KEY}&units=metric
   ```

---

## Folder Structure

```
weather-whisperer/
├── public/
├── src/
│   ├── components/
│   │   └── WeatherCard.js
│   ├── styles/
│   │   └── WeatherApp.css
│   ├── App.js
│   ├── index.js
│   ├── WeatherApp.js
├── .env
├── package.json
├── README.md
```

---

## Future Enhancements

1. Add hourly weather forecasts.
2. Include additional weather parameters like humidity and UV index.
3. Support geolocation for automatic city detection.
4. Implement user authentication for personalized settings.

---

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

---



## Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/) for the API
- [Bootstrap](https://getbootstrap.com/) for UI components
- [React Icons](https://react-icons.github.io/react-icons/) for weather icons
- [Framer Motion](https://www.framer.com/motion/) for animations

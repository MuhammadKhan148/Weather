# Weather Dashboard

A modern, interactive weather dashboard application that provides real-time weather information, forecasts, and a weather-focused chatbot interface.

![Weather Dashboard Preview](/api/placeholder/800/400)

## Features

- **Real-time Weather Data**: Get current weather conditions for any city worldwide
- **Interactive Charts**: 
  - Temperature bar chart
  - Weather conditions distribution
  - Temperature trend line chart
- **5-Day Forecast**: Detailed weather predictions with temperature, conditions, humidity, and wind speed
- **Smart Weather Chatbot**: 
  - Natural language interaction for weather queries
  - Context-aware responses
  - Suggested questions and follow-ups
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Unit Toggle**: Switch between Celsius and Fahrenheit
- **Data Filtering**: Sort and filter weather data based on various conditions

## Prerequisites

Before you begin, ensure you have the following installed:
- Web browser (Chrome, Firefox, Safari, or Edge)
- Text editor or IDE
- Node.js and npm (optional, for local development server)

## API Keys Required

This application uses the following APIs:
1. OpenWeather API - Get your key at [OpenWeather](https://openweathermap.org/api)
2. Google Gemini API - Get your key at [Google AI Studio](https://makersuite.google.com/app/apikey)

## Setup Instructions

1. Clone the repository:
```bash
git clone <repository-url>
cd weather-dashboard
```

2. Update API keys:
   - Open `script.js`
   - Replace the placeholder API keys with your own:
```javascript
const OPENWEATHER_API_KEY = 'your_openweather_api_key';
const GEMINI_API_KEY = 'your_gemini_api_key';
```

3. Launch the application:
   - Option 1: Open `index.html` directly in a web browser
   - Option 2: Use a local development server:
     ```bash
     # Using Python
     python -m http.server 8000

     # Using Node.js
     npx http-server
     ```

4. Access the application:
   - If using direct file access: `file:///path/to/index.html`
   - If using local server: `http://localhost:8000`

## Project Structure

```
weather-dashboard/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── images/            
    └── usericon.jpeg   # User profile image
```

## Key Components

1. **Weather Widget**: Displays current weather conditions
2. **Charts Section**: Visual representation of weather data
3. **Forecast Table**: Detailed 5-day weather forecast
4. **Weather Chatbot**: Interactive weather assistant
5. **Navigation Sidebar**: Easy access to different sections

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Features in Detail

### Weather Data Display
- Current temperature
- Weather conditions
- Humidity levels
- Wind speed
- Weather icons
- Last updated timestamp

### Interactive Charts
- Temperature variations
- Weather conditions distribution
- Temperature trends over time

### Chatbot Capabilities
- Natural language weather queries
- Context-aware responses
- Suggested questions
- Follow-up prompts
- Weather advice and recommendations

### Data Management
- Sort temperatures (ascending/descending)
- Filter rainy days
- View highest temperatures
- Toggle temperature units

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Weather data provided by [OpenWeather API](https://openweathermap.org/api)
- Chatbot powered by [Google Gemini API](https://ai.google.dev/)
- Charts created using [Chart.js](https://www.chartjs.org/)

## Support

For support, please open an issue in the repository or contact the maintainers.

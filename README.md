# Weather

A simple weather application that shows real-time temperature of any known place.

## How to Clone This Repository

To clone this repository to your local machine, follow these steps:

### Prerequisites
- Git installed on your computer ([Download Git](https://git-scm.com/downloads))

### Cloning Steps

1. **Using HTTPS (Recommended for most users):**
   ```bash
   git clone https://github.com/vedanth5/Weather.git
   ```

2. **Using SSH (If you have SSH keys set up):**
   ```bash
   git clone git@github.com:vedanth5/Weather.git
   ```

3. **Navigate to the project directory:**
   ```bash
   cd Weather
   ```

## How to Use

1. Create an OpenWeatherMap API key:
   - Sign up or log in at [OpenWeatherMap](https://openweathermap.org/api)
   - Generate an API key from your account dashboard
   - Note that a newly created key may take a little time to become active

2. Configure the API key locally:
   - Open `index.html`
   - Find the `apiKey` value used for OpenWeatherMap requests
   - Replace it with your own API key on your local machine
   - Do **not** commit your real API key to the repository

3. Open the `index.html` file in your web browser
4. Enter any city name in the search box
5. Click the search button to see the current weather information

If the weather data does not load, double-check that your API key was copied correctly, has become active, and is valid. A missing or invalid API key will prevent requests to OpenWeatherMap from succeeding.

## Features

- Real-time weather data
- Temperature display in Celsius
- Humidity information
- Wind speed information
- Clean and responsive UI

## Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeatherMap API

# Weather App

![App Screenshot](./Screenshot%202025-02-14%20003753.png)

A small, responsive Weather App built with HTML, CSS and JavaScript. It fetches current weather information for a city using a public weather API and presents it in a clean, mobile-friendly UI.

## Demo / Preview

See the screenshot above for a quick preview of the app.

## Features

- Search weather by city name
- Shows temperature, weather description, humidity and wind speed
- Responsive and lightweight (pure HTML/CSS/JS)
- Easy to customize UI and behavior

## Tech

- HTML
- CSS
- JavaScript

## Installation & Usage

1. Clone this repository:

   git clone https://github.com/BinaryVortex/Weather-App-5.git

2. Open `index.html` in your browser (double-click or right-click -> Open With).

   - For a faster developer workflow, serve the folder with a simple local server (optional):
     - Python 3: `python -m http.server 8000`
     - Node.js: `npx http-server`

3. If the app uses a weather API that requires a key (e.g. OpenWeatherMap), add your API key in the JavaScript file where the fetch request is made. Look for a variable named like `API_KEY` or a comment mentioning "API key".

4. Type a city name in the search box and press Enter or click the search button.

## Customization

- Update the CSS files to change the look and feel.
- Modify the JavaScript to display additional data (forecast, icons, etc.).

## Troubleshooting

- If weather data doesn't appear, open the browser console (F12) and check for errors.
- If you see CORS or network errors, verify the API endpoint and your API key.

## Contributing

Contributions, suggestions and improvements are welcome. Feel free to open an issue or submit a pull request.

## Attribution

Built by BinaryVortex.

---

*This project description was auto-generated and may need small adjustments depending on how the API key and script are configured in your code.*

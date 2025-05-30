# weather-forecast

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Weather Now - Project Documentation</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 2rem;
      background-color: #f9f9f9;
      line-height: 1.6;
      color: #333;
    }
    h1, h2, h3 {
      color: #2c3e50;
    }
    code {
      background-color: #eee;
      padding: 2px 4px;
      border-radius: 4px;
    }
    pre {
      background-color: #eee;
      padding: 1rem;
      border-radius: 6px;
      overflow-x: auto;
    }
    a {
      color: #2980b9;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    ul {
      padding-left: 1.2rem;
    }
  </style>
</head>
<body>

  <h1>🌦️ Weather Now</h1>
  <p><strong>Weather Now</strong> is a sleek and responsive web application that displays real-time weather conditions and a 5-day forecast for any city worldwide. Built with HTML, CSS, and JavaScript, it fetches weather data from the <a href="https://www.weatherbit.io/" target="_blank">Weatherbit API</a> and dynamically updates the UI based on the current weather conditions.</p>

  <h2>🔥 Features</h2>
  <ul>
    <li>🌍 <strong>Automatic Geolocation</strong> – Detects user location and displays local weather on page load.</li>
    <li>🔍 <strong>City Search</strong> – Enter any city name to view its current weather and forecast.</li>
    <li>🌡️ <strong>Temperature Unit Toggle</strong> – Switch between Celsius and Fahrenheit (easily extendable).</li>
    <li>🎨 <strong>Dynamic Backgrounds</strong> – Background color changes based on weather condition.</li>
    <li>📅 <strong>5-Day Forecast</strong> – Clean view of upcoming weather with icons and temperature.</li>
    <li>⏱️ <strong>Fast & Lightweight</strong> – No heavy libraries, quick load times, cross-browser support.</li>
  </ul>

  <h2>🚀 Getting Started</h2>

  <h3>1. Clone the repository</h3>
  <pre><code>git clone https://github.com/your-username/weather-now.git
cd weather-now</code></pre>

  <h3>2. Add your Weatherbit API key</h3>
  <p>Replace the <code>API_KEY</code> in the JavaScript section:</p>
  <pre><code>const API_KEY = 'your_api_key_here';</code></pre>

  <h3>3. Open in your browser</h3>
  <p>Open <code>index.html</code> directly in a browser or serve using a local server (e.g., Live Server in VSCode).</p>

  <h2>📸 Screenshot</h2>
  <p><em>Insert your project screenshot here:</em></p>
  <img src="your-screenshot.png" alt="Weather Now UI Screenshot" width="80%" style="border-radius:10px; border:1px solid #ccc;">

  <h2>🛠️ Tech Stack</h2>
  <ul>
    <li><strong>Frontend:</strong> HTML5, CSS3, JavaScript</li>
    <li><strong>API:</strong> Weatherbit.io</li>
    <li><strong>Icons:</strong> Weatherbit Static Icon Set</li>
  </ul>

  <h2>✅ To-Do / Improvements</h2>
  <ul>
    <li>Add toggle for Celsius ↔ Fahrenheit</li>
    <li>Add multi-language support</li>
    <li>Add local storage for last searched city</li>
    <li>Add more detailed error handling</li>
    <li>Improve mobile responsiveness</li>
  </ul>

  <h2>📄 License</h2>
  <p>This project is licensed under the <strong>MIT License</strong>. Feel free to use, modify, and share.</p>

  <h2>🙌 Acknowledgements</h2>
  <ul>
    <li><a href="https://www.weatherbit.io/" target="_blank">Weatherbit.io</a> – For providing weather data APIs</li>
    <li>Open source developers and UI inspirations</li>
  </ul>

</body>
</html>

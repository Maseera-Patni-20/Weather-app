<!-- Weathy Desktop Weather Application -->

<h1>Weathy</h1>

<p>Weathy is a desktop weather application built with Python and tkinter, utilizing the OpenWeatherMap API for real-time weather data retrieval. The application offers a user-friendly graphical interface to display weather information, including temperature, wind speed, humidity, and atmospheric pressure. It also features dynamic background changes based on current weather conditions.</p>

<img src="screenshots/weathy_screenshot.png" alt="Weathy Screenshot" style="max-width: 100%;">

<h2>Table of Contents</h2>

<ul>
  <li><a href="#features">Features</a></li>
  <li><a href="#requirements">Requirements</a></li>
  <li><a href="#installation">Installation</a></li>
  <li><a href="#usage">Usage</a></li>
  <li><a href="#screenshots">Screenshots</a></li>
  <li><a href="#credits">Credits</a></li>
  <li><a href="#license">License</a></li>
</ul>

<h2 id="features">Features</h2>

<ul>
  <li><strong>Real-time Weather Updates:</strong> Retrieves weather data from OpenWeatherMap API for any city worldwide.</li>
  <li><strong>Search Functionality:</strong> Allows users to search for weather information by entering a city name.</li>
  <li><strong>Weather Description and Icons:</strong> Displays weather condition descriptions (e.g., clear, cloudy, rainy) with corresponding graphical icons.</li>
  <li><strong>Temperature:</strong> Shows temperature in Celsius.</li>
  <li><strong>Wind Speed:</strong> Displays wind speed in meters per second.</li>
  <li><strong>Humidity:</strong> Indicates relative humidity percentage.</li>
  <li><strong>Pressure:</strong> Shows atmospheric pressure in hPa (hectopascals).</li>
  <li><strong>Dynamic Background:</strong> Changes background image dynamically based on the current weather conditions.</li>
  <li><strong>Error Handling:</strong> Alerts users for no internet connection or invalid city names.</li>
</ul>

<h2 id="requirements">Requirements</h2>

<ul>
  <li>Python 3.x</li>
  <li>tkinter (standard GUI toolkit for Python)</li>
  <li>PIL (Python Imaging Library)</li>
  <li>requests (HTTP library for making API requests)</li>
</ul>

<h2 id="installation">Installation</h2>

<ol>
  <li><strong>Clone the repository:</strong></li>
  <pre><code>git clone https://github.com/your_username/Weathy.git
cd Weathy
</code></pre>

  <li><strong>Install dependencies:</strong></li>
  <pre><code>pip install -r requirements.txt
</code></pre>

  <li><strong>Obtain an API key from OpenWeatherMap:</strong></li>
  <ul>
    <li>Sign up at <a href="https://home.openweathermap.org/users/sign_up">OpenWeatherMap</a>.</li>
    <li>Copy the API key.</li>
  </ul>
</ol>

<h2 id="usage">Usage</h2>

<ol>
  <li><strong>Run the application:</strong></li>
  <pre><code>python weathy.py
</code></pre>

  <li><strong>Using the application:</strong></li>
  <ul>
    <li>Enter a city name in the search field and press Enter or click the search button to retrieve weather information.</li>
    <li>The main window displays the current weather conditions, including weather description, temperature, wind speed, humidity, and pressure.</li>
    <li>Icons represent different weather conditions (clear, cloudy, rain, etc.).</li>
    <li>The background image changes dynamically based on the current weather conditions.</li>
  </ul>
</ol>

<h2 id="screenshots">Screenshots</h2>

<p>Add more screenshots if necessary</p>

<h2 id="credits">Credits</h2>

<ul>
  <li>Icons used in the application are sourced from OpenWeatherMap and other free icon repositories under Creative Commons licenses.</li>
  <li>Background images are sourced from Unsplash and other free image repositories under appropriate licenses.</li>
</ul>

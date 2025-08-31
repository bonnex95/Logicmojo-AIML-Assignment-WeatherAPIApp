<div align="center">
  <h1>☁️ Weather App</h1>
  <p><i>A simple application to get real-time weather information for any city</i></p>
</div>

<br>

<div align="center">
  <a href="https://github.com/brej-29/Logicmojo-AIML-Assignment-WeatherAPIApp">
    <img alt="Last Commit" src="https://img.shields.io/github/last-commit/brej-29/Logicmojo-AIML-Assignment-WeatherAPIApp">
  </a>
  <img alt="Python Language" src="https://img.shields.io/badge/Language-Python-blue">
  <img alt="Requests" src="https://img.shields.io/badge/Library-Requests-brightgreen">
  <img alt="API" src="https://img.shields.io/badge/API-OpenWeatherMap-orange">
  <img alt="Django" src="https://img.shields.io/badge/Framework-Django-darkgreen">
  <img alt="HTML" src="https://img.shields.io/badge/Language-HTML-orange">
  <img alt="CSS" src="https://img.shields.io/badge/Language-CSS-blue">

</div>

<div align="center">
  <br>
  <b>Built with the tools and technologies:</b>
  <br>
  <br>
  <code>Python</code> | <code>HTML</code> | <code>requests</code> | <code>Django</code> | <code>OpenWeatherMap API</code> | <code>CSS</code>
</div>

---

## **Table of Contents**
* [Overview](#overview)
* [Features](#features)
* [Getting Started](#getting-started)
    * [Prerequisites](#prerequisites)
    * [Installation](#installation)
    * [Configuration](#configuration)
    * [Usage](#usage)
* [License](#license)
* [Contact](#contact)

---

## **Overview**

This project is a simple, user-friendly desktop Weather App built with Python. It fetches and displays real-time weather data for any 2 cities in the world by utilizing the OpenWeatherMap API. The application provides key weather details such as temperature, humidity, wind speed, and a description of the current weather conditions, all presented in a clean graphical user interface.

<br>

### **Project Highlights**

- **Real-time Data:** Fetches up-to-the-minute weather information from the reliable OpenWeatherMap service.
- **Global Coverage:** Get weather information for any city around the globe.
- **User-Friendly GUI:** A simple and intuitive interface built with Tkinter.
- **Lightweight:** Minimal dependencies and easy to set up.

---

## **Features**

- Search for weather by city name.
- Display current temperature (in Celsius).
- Show humidity percentage and wind speed.
- Visual icons representing the current weather condition (e.g., sunny, cloudy, rain).
- Error handling for invalid city names.

---

## **Getting Started**

Follow these instructions to get a copy of the project up and running on your local machine.

### **Prerequisites**
To run this application, you will need the following installed:
* Python 3.x
* The following Python libraries:
  * `requests`
  * `Django` 

### **Installation**
1. **Clone the repository (or download the source code):**  
   ```sh
   git clone https://github.com/brej-29/Logicmojo-AIML-Assignment-WeatherAPIApp
   ```
2. **Navigate to the project directory:**  
   ```sh
   cd Logicmojo-AIML-Assignment-WeatherAPIApp
   ```
3. **Install the required packages using `pip`:**
   ```sh
   pip install requests Django
   ```

### **Configuration**
The application requires an API key from OpenWeatherMap to fetch weather data.

1.  **Get an API Key:**
    *   Go to OpenWeatherMap and sign up for a free account.
    *   Navigate to the 'API keys' tab in your account to find your default key.

2.  **Set up the API Key:**
    *   In the root of the project directory, there is a file named `API_KEY`.
    *   Open this file and paste your API key into it. The file should contain only the key.

### **Usage**
1. **Run the application from the terminal:**  
   ```sh
   python manage.py runserver 
   ```

2. **Use the application:**
   - Enter the name of a city in the input field.
   - Press the 'Search' button or hit Enter.
   - The weather details for the specified city will be displayed.

---

## **License**
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## **Contact**
If you have any questions or feedback, feel free to reach out via my [LinkedIn Profile](https://www.linkedin.com/in/brejesh-balakrishnan-7855051b9/)


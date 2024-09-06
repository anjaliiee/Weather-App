# 🌤️ Weather App

## Welcome to the **Weather App** – your stylish, user-friendly, and fun way to check the weather! 🌦️  
Just type in a city name, and instantly get all the weather details you need, like temperature, humidity, and wind speed.  
Plus, watch the icons and backgrounds change dynamically to reflect the weather conditions in real-time! 🎉

---

## 🚀 Features

- 🌍 **Search for any city** and get live weather updates.
- 🌡️ **Current temperature** in Celsius.
- 💧 **Humidity and wind speed** displayed at a glance.
- 🎯 **Instant error handling** for invalid city names.
- 🎨 **Dynamic weather icons and backgrounds** that adapt based on the current conditions (sun, rain, snow? We've got you covered!).

---

## 🛠️ Setup Instructions

### Step 1: Clone the Repository

```bash
git clone https://github.com/anjaliiee/Weather-App.git
cd weather-app
```
### Step 2: Get Your Free API Key from OpenWeather

To make this weather magic happen, you'll need to grab an API key from OpenWeather. Don’t worry—it’s super simple and free! 🌟

#### 🔑 How to Get Your Own API Key:

1. Go to [**OpenWeather**](https://openweathermap.org/).
2. Sign up (or log in) to create a new account.
3. Head over to the **API Keys** section in your dashboard.
4. Generate a new key by clicking **Create Key** and give it a fun name like `"MyWeatherApp"`.
5. Copy your shiny new API key.
6. Now, open the `index.html` file and paste your API key in place of the empty string:

```javascript
const apiKey = "YOUR_API_KEY_HERE";
```
### Step 3: Start Checking Weather!
1. Open index.html in your favorite browser.
2. Type in any city name (New York, Tokyo, Paris? You decide!).
3. Hit the search button, and boom! 💥 You'll get the weather info displayed with some cool icons and details.
   
---

## 🎨 Customize It!
- Want to make it even more unique? Here’s how:

**Add your own custom weather icons!**
- Drop them into the images/ folder with names that match different weather conditions (like Clear, Clouds, Rain).
- Change the background images that load dynamically based on the weather for that extra pop! 🌈
---
  
### 📂 Project Structure

```bash
weather-app/
│
├── index.html          # The HTML magic
├── styles.css          # Stylin' with CSS
├── images/             # Folder for weather icons and backgrounds
│   ├── search.png
│   ├── Clear.png       # Customize these with your own weather icons!
│   ├── Rain.png
│   └── ...
├── README.md           # The guide you're reading!
```
---

### 🔧 Technologies Used
1. HTML/CSS/JavaScript: The building blocks of this fun weather app.
2. OpenWeather API: Pulls in real-time weather data from all over the globe!
   
---

### 🔥 Take it to the Next Level
#### Tweak the design and add more cool features like weather forecasts, background animations, or even themed music for different weather conditions! 🎶
---

### 📄 License
*This project is open-sourced under the MIT License – feel free to modify and have fun with it!*



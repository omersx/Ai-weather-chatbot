# 🌦️ Nimo - AI Weather Chatbot

Nimo is an interactive AI-powered weather assistant that helps users get real-time weather information and personalized recommendations.
It combines the OpenWeather API for live weather data with OpenRouter AI models for natural conversation and recommendations.

# 📷 UI Preview

<img width="2560" height="1440" alt="weahter" src="https://github.com/user-attachments/assets/28a417ff-f4b8-479f-8388-262bbfea1595" />

🌍 Interactive AI weather chatbot that delivers real-time forecasts and personalized advice using OpenWeather API + OpenRouter AI.

-----------------------------
#🚀 Features

🔍 Ask about weather in any city or region

🌤️ Real-time weather data (temperature, humidity, wind, pressure)

📍 Geolocation support – fetch weather based on user’s location

🤖 AI-powered recommendations & explanations

🎨 Beautiful weather cards with adaptive colors and emojis

⚡ Quick replies & smooth animations

📱 Responsive design (desktop & mobile friendly)

--------------------------

## 🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript

## APIs:

OpenWeather API
 – weather data

OpenRouter API
 – AI chat responses

AI Model (default): mistralai/mistral-7b-instruct:free (customizable)

## 📦 Setup & Installation

Clone this repository:
 ```bash
git clone https://github.com/omersx/Ai-weather-chatbot.git
cd nimo-weather-bot
 ```
Get API Keys:

🌤️ Sign up for OpenWeather
 → get your API key

🤖 Sign up for OpenRouter
 → get your API key

Configure API Keys:
Open `weather-chatbot.html` and replace placeholders inside WEATHER_CONFIG:
 ```js
const WEATHER_CONFIG = {
    OPENWEATHER_API_KEY: 'YOUR_OPENWEATHER_API_KEY_HERE',
    OPENROUTER_API_KEY: 'YOUR_OPENROUTER_API_KEY_HERE',
    MODEL: 'mistralai/mistral-7b-instruct:free'
};
 ```
--------------------------

## 🚀 How to Use in WordPress

1. Install the [Code Snippets](https://wordpress.org/plugins/code-snippets/) plugin** (or use your theme's custom HTML block).
2. Open the chatbot `weather-chatbot.html` file** (either green or blue version) in VS Code or any editor.
3. Copy the entire code and **paste it into a new HTML snippet** in WordPress.
4. Save and activate the snippet.
5. costomize the system prompt to fit your wnat 

-------------

## 🖥️ Usage

Click the floating chat button to open the chatbot.

Type:

"Weather in Dubai"

"Is it raining in London?"

"Temperature in Paris today"

Or click 📍 location button to get your local weather.

Nimo will:

Fetch weather data from OpenWeather API

Use AI (OpenRouter) to generate recommendations

Display a weather card + chat message response

----------------

## ⚠️ API Key Warning

If you forget to configure API keys, Nimo shows a warning banner:
 ```
🔧 API keys not configured. See README for setup instructions.
 ```

## 🧩 Customization

🎨 Colors & UI → edit CSS variables in :root

🌍 Weather model → change MODEL in WEATHER_CONFIG

🔔 Heat alerts → automatically shows warnings above 35°C


--------------

# 📜 License

- This project is open-source under the MIT License.

--------------------------------------------------------------

# 🤝 Contributions

- Feel free to open issues, suggest features, or submit pull requests. Let’s build smarter web experiences together!


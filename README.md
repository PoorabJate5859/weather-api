# Weather App 🌤️

A modern weather application that allows users to select a city from a dropdown and retrieve real-time weather data using the OpenWeatherMap API. The app provides essential weather details like temperature, humidity, and a description of the current weather. This repository contains the front-end code for the app, including HTML, CSS, and JavaScript files.

![image](https://github.com/user-attachments/assets/06df7ebb-4047-4fd1-913b-99401a6ba9b6)

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [API Key](#api-key)
- [Contributing](#contributing)
- [License](#license)

## Features

- 🌍 Dynamically populated list of cities.
- 🌡️ Fetches real-time weather data.
- 📊 Displays weather information such as temperature, humidity, and description.
- 🌟 Clean and modern UI design with smooth animations.
- 💻 Fully responsive for both desktop and mobile screens.

## Tech Stack

- **HTML5**: Markup for structure.
- **CSS3**: Styling with a modern, minimalist design.
- **JavaScript**: Front-end logic to interact with the OpenWeatherMap API.
- **OpenWeatherMap API**: Retrieves real-time weather data.

## Setup and Installation

### Prerequisites

- Basic knowledge of HTML, CSS, and JavaScript.
- **API Key** from [OpenWeatherMap](https://openweathermap.org/api).
  
### Steps to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/PoorabJate5859/weather-api.git
   ```

2. Navigate to the project directory:

   ```bash
   cd weather-api
   ```

3. Open the `index.html` file in a browser:

   - You can either open the file directly in your browser or use a local server (such as **Live Server** in Visual Studio Code) to run the app.

### API Key Setup

- Open the `main.js` file and replace the `apiKey` placeholder with your own API key from OpenWeatherMap:

  ```javascript
  const apiKey = 'your_api_key_here';
  ```

### JSON Setup for Cities

- The list of cities is populated from a local `cities.json` file. Make sure this file is in the root directory, and it contains a list of cities and their respective countries.

Example `cities.json` file:

```json
[
  { "name": "New York", "country": "US" },
  { "name": "London", "country": "UK" },
  { "name": "Tokyo", "country": "JP" }
]
```

## Usage

1. Open the app in your browser.
2. Select a city from the dropdown menu.
3. Click the **"See Weather"** button to get the real-time weather for the selected city.
4. The weather details (temperature, description, and humidity) will be displayed below.

## Screenshots

### 1. Home Screen:
![image](https://github.com/user-attachments/assets/d5c87003-2580-46c4-b99e-49d0f15dffd0)

### 2. Weather Data Display:
![image](https://github.com/user-attachments/assets/974beee6-4f0f-40ba-b1ab-4c11eb8e9cd5)

## API Key

You will need an API key from [OpenWeatherMap](https://openweathermap.org/) to fetch weather data. Sign up for a free account and use the provided key in your `main.js` file.

```javascript
const apiKey = 'your_api_key_here';
```

## Contributing

Contributions are welcome! If you have suggestions for improving this project, please fork the repository and create a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

---

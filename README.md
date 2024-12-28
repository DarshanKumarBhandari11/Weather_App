# Weather App 🌦️

A responsive and interactive weather application built with ReactJS that allows users to search for and view real-time weather details of any city. The app fetches data from the OpenWeatherMap API and dynamically updates the user interface with information such as temperature, humidity, and weather conditions.

---

## Features ✨

- 🌎 **City Search**: Enter the name of a city to get its current weather information.
- 📊 **Weather Details**: Displays real-time data such as:
  - Current temperature
  - Humidity
  - Minimum and maximum temperatures
  - Feels-like temperature
  - Weather description
- 🎨 **Dynamic Layout**: The app displays dynamic card layout based on the temperature and weather conditions.
- 🔄 **Error Handling**: Displays an error message if the city is not found or there's an issue with the API request.
- 💻 **Responsive Design**: Works seamlessly across devices, including mobile, tablet, and desktop.

---

## Tech Stack 🛠️

### Frontend:
- **ReactJS**: For building the user interface and managing state.
- **Material-UI**: For consistent and visually appealing UI components.
- **CSS Modules**: For scoped and maintainable styling.

### API:
- **OpenWeatherMap API**: For fetching real-time weather data.

---

## How to Run Locally 🖥️

1. **Clone the repository:**
   ```bash
   git clone https://github.com/DarshanKumarBhandari11/Weather_App.git


2. **Navigate to the project directory:**
   ```bash
   cd Weather_App

3. **Install dependencies:**
    ```bash
    npm install

4. **Set up API Key:**
    - Go to OpenWeatherMap and create a free account to obtain your API key.
    - Replace the API_KEY in SearchBox.jsx with your generated key.

5. **Run the app:**
    - For development:
    ```bash
    npm run dev
    ```
    - For production:
    ```bash
    npm start
    ```

6. **Open your browser and navigate to:**
    - For development: http://localhost:5173 (default for Vite).
    - For production: http://localhost:3000.

---

## Folder Structure 📂
   ```
   Weather_App/
   │
   ├── public/
   ├── src/
   │   ├── assets/
   │   ├── App.css
   │   ├── App.jsx
   │   ├── index.css
   │   ├── InfoBox.css
   │   ├── InfoBox.jsx
   │   ├── main.jsx
   │   ├── SearchBox.css
   │   ├── SearchBox.jsx
   │   ├── WeatherApp.css
   │   ├── WeatherApp.jsx
   ├── .gitignore
   ├── eslint.config.js
   ├── index.html
   ├── package-lock.json
   ├── package.json
   ├── README.md
   └── vite.config.js
   ```

---

## Contributing

Contributions are welcome!
If you'd like to contribute, please fork the repository and submit a pull request.

## Contact

For questions or feedback, feel free to reach out to me at darshankumarbhandari11@gmail.com .

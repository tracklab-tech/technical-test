# Weather App 

This is a simple weather forecast app used as technical test. 

## Weather App

### 1. Set Up the Project:

Fork this repo. Create a new React.js project using Create React App or your preferred setup.
Set up TypeScript if you choose TypeScript or use JavaScript if you prefer.

### 2. Create Components:

Create a WeatherApp component that will serve as the main application.
Inside the WeatherApp component, create a form to input the temperature threshold and select the city.
Create a component to display the list of upcoming days with extreme heat.

### 3. Fetch Weather Data:

Use the fetch or axios library to make a GET request to a weather API like OpenWeatherMap.
You'll be provided with an API KEY.
Retrieve the weather forecast data for Paris or any chosen city.

### 4. Process Data:

Filter the weather data for the next 15 days.
Check if each day's maximum temperature exceeds the threshold set in the form.

### 5. Display Data:

Render the list of the next 15 days in a calendar-like format.
Highlight the days with extreme heat by applying a red border or background.
Display "extreme heat" alongside the dates that meet the criteria.

### 6. Implement Bonus Features:

For bonus point #1, create an input field in the form that allows users to set the temperature threshold dynamically.
For bonus point #2, add an input field that allows users to choose a city. Implement logic to fetch weather data for the selected city.

### 7. Style the App:

Apply CSS or use a CSS-in-JS solution (like styled-components) to style the components and make the app visually appealing.

### 8. Testing:

Write tests using a testing library like Jest and React Testing Library to ensure the app works as expected.

### 9. Documentation:

Provide clear documentation on how to run the app, configure the temperature threshold, and choose a city.
Request for Implementation:

Please create a React.js application (using TypeScript or JavaScript) based on the above requirements.

### Notes :
You'll be interviewed based on your own implementation and technical questions will be asked accordingly. 
If you take some code from outside, mark it as is.

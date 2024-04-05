# Bharat Intern Projects

## WeatherWhispers App

### Project Description

Weather Whispers is a captivating web application crafted using HTML, CSS, and JavaScript that unveils the secrets of the weather in your vicinity. By harnessing the power of the OpenWeatherMap API, it retrieves real-time weather data, transforming it into an engaging and informative experience.

### Key Features

##### Location Detection: 

Leverages geolocation to pinpoint your current location, eliminating the need for manual city entry. (Optional: Allow manual location input as a fallback.)

##### Weather Data Fetching: 

Employs the OpenWeatherMap API to seamlessly acquire weather details, ensuring up-to-date information.

##### Intuitive Interface: 

Presents weather data in a visually appealing and user-friendly format, making it easy to grasp weather conditions at a glance.

##### Customizable Display: 

Provides options to personalize the display of weather information, catering to individual preferences. (Consider incorporating this in future enhancements.)

### Getting Started

#### Prerequisites:

1. A code editor (e.g., Visual Studio Code, Sublime Text)
2. Basic understanding of HTML, CSS, and JavaScript

#### Project Setup:

1. Create a project directory.
2. Within the directory, establish essential HTML, CSS, and JavaScript files (e.g., index.html, styles.css, script.js).

#### Acquire OpenWeatherMap API Key:

1. Visit https://openweathermap.org/ and register for a free API key.
2. Securely store the API key in a designated environment variable or a separate configuration file (never commit it to version control).

#### HTML Structure:

* Construct the fundamental HTML framework within index.html, encompassing elements for displaying location, weather data, and potentially, customization options.

#### CSS Styling:

* Craft an aesthetically pleasing stylesheet (styles.css) to govern the visual presentation of the app's elements.

#### JavaScript Functionality:

1. In script.js, implement the core logic:

    1.1 Utilize the Geolocation API to ascertain the user's location (with appropriate error handling).

    1.2 Construct the OpenWeatherMap API request URL, incorporating the retrieved location coordinates and your API key.

    1.3 Fetch weather data using JavaScript's fetch API or an alternative library like Axios.

    1.4 Parse the JSON response and extract pertinent weather information (e.g., temperature, humidity, wind speed, weather description).

    1.5 Dynamically update the HTML content with the fetched weather data, injecting it into the designated elements.

#### Customization (Optional - Future Enhancement)

1. Explore incorporating options for users to personalize the display of weather data (e.g., temperature units, weather icons).
2. Consider implementing local storage to remember user preferences for future visits.

#### Deployment

* Host the project files on a web server (e.g., GitHub Pages, Netlify) to make it accessible online.

#### Testing

* Thoroughly test the application across various browsers and devices to ensure consistent functionality.



## Netflix Home Page - HTML & CSS

This project is a basic clone of the Netflix home page layout built using HTML and CSS. It replicates the visual structure and design of the popular streaming service's landing page.

### Features

* **Navigation bar:** Includes links mimicking the Netflix navigation options. 
* **Hero Section:** A large banner showcasing a movie/series image with title and description.
* **Content Rows:** Multiple rows displaying "cards" representing movies or shows. (Note: This is a static layout, content is not populated dynamically)

### Technologies Used

* HTML: Creates the basic structure and content of the webpage.
* CSS: Styles the HTML elements for visual design and layout.

### Running the Project

1. Clone or download the project files.
2. Open the `index.html` file in a web browser.

### Folder Structure

* `index.html`: The main HTML file containing the page structure.
* `styles.css`: The CSS file containing all styles for the webpage.
* (Optional) `images`: Folder containing any images used in the project (e.g., logo, banner image).

### Note

* This is a basic implementation focusing on HTML and CSS for layout purposes. 
* Functionality like user sign-in, content search, or dynamic content population is not included.

# weatherForecast
Create a single page web app that leverages asynchronous javascript to display the upcoming weather in a selected city using data from a public API.

1. It should include:

-A field to enter a zip code.

-When the user submits the zip, async javascript should call an API (detailed below) to retrieve upcoming weather data.

-Using the returned data the app should display date/time, temperature and pressure in a table. City name should also appear at the top of the table.

2. API Info:

-Use the API at https://openweathermap.org/ This will require you sign up for a free account to get an API key.

-The API route to use is: https://api.openweathermap.org/data/2.5/forecast?zip=[ZIP_CODE],us&amp;APPID=[YOUR_API_KEY]

-API route documentation: https://openweathermap.org/forecast5

-Use JSON and not XML for data returns.

3. Bonus points for:

-Using a CSS framework to make it look nice (e.g. Bootstrap), or roll your own styling.

-Build in exception handling (such as entering in a malformed zip code or one that does not exist).

-Build in user feedback of application state (loading, error, etc.).

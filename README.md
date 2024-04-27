<div align="center">
  <h1>
    MY_WEATHER_APP
  </h1>
</div>

<p>&nbsp;&nbsp;&nbsp;&nbsp;This weather application was developed using HTML, CSS, and JavaScript. It allows users to input their desired city to retrieve current weather information. The aim is to provide a streamlined user experience for accessing essential weather data quickly. This project also serves as a learning opportunity for web technologies and integration of weather APIs.</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;For security reasons and to ensure the best possible experience for all users, the API key has not been included directly in the project. Instead, to set up the API key, follow the detailed steps in the 'OpenWeatherMap API Key Configuration' section of this documentation to generate and insert your own API key. It is always important to protect and hide your API keys to prevent unauthorized access and maintain data security. This way, each user will have control over access to weather data, and we will maintain service integrity for everyone. Thank you in advance for following these guidelines and contributing to data security and privacy.</p>

---

## OpenWeatherMap API Key Configuration

To use this project, you will need an API key from OpenWeatherMap. Follow the steps below to configure your API key:

1. **Create an account on OpenWeatherMap**: If you do not already have an account, go to [OpenWeatherMap](https://openweathermap.org/) and create a free account.
   
2. **Log in to your OpenWeatherMap account**: After creating your account, log in to OpenWeatherMap.

3. **Generate your API key**: After logging in, go to "API Keys" and click on "Create key." Give your key a name and click "Generate."

4. **Copy your API key**: After generating your API key, copy it to the clipboard.

   *If you already have an API key created and sent by email*, you can copy it from the email and proceed to step 5.

5. **Using the API Key in the Project**

After generating your OpenWeatherMap API key, you will need to insert it into the project's source code. Follow these steps to add your API key:

- Open the `script.js` file in your preferred code editor.
- Look for the `apiKey` variable in the `script.js` file.
- Replace `'YOURAPIKEYHERE'` with the API key you copied earlier.

Example:

```javascript
const apiKey = 'YOUR_API_KEY_HERE';
```

---
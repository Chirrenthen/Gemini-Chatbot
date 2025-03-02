# Gemini Clone Project Setup Guide

If you encounter an error like "API key not valid. Please pass a valid API key." while chatting with the Gemini, please follow these steps:

## Get Your API Key

1. Go to [Google AI Studio](https://aistudio.google.com/app/apikey).
2. Navigate to the API key section and create a new API key.

Your API key will look something like this: AIsayuxgwemx0l_gQeatYvdWvY_wOTQ

**Note:** The API is free but has a limited number of usage requests.

## Insert Your API Key
1. Copy and Enter your API key in the alert message shown while startup

## Save and Test

1. Save the `script.js` file after adding your API key.
2. Open `index.html` in your browser to verify that Gemini is working correctly.
3. If you encounter any errors make sure to test your API key with [Postman](https://www.postman.com/downloads/).

## Other Method

1. Fork this repository to your account
2. Follow the instructions given above and create a GitHub pages site for your code
3. Make sure to create the repository type 'private' as the API is confidential

## Important Information

This chatbot uses the Gemini beta model, gemini-1.5-flash, which allows more free requests within a shorter timeframe. If you need greater reliability, you can switch to the stable model, gemini-1.5-pro. While the free version of this model has stricter request limits, upgrading to a paid plan will remove these restrictions.

To switch to the gemini-1.5-pro stable model, update the API_URL in the `script.js` file as follows:
const API_URL = `https://generativelanguage.googleapis.com/v1/models/gemini-1.5-pro:generateContent?key=${API_KEY}`;

If you still get an error or get stuck, feel free to message me to my email..
chirrenthen13@gmail.com

---

Happy coding!
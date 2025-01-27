# AI Image Description & Translation App

This is a Streamlit-based web application that generates descriptions for uploaded images based on user prompts, translates them into various languages, and provides text-to-speech functionality.

## Features

- Upload an image (JPEG format)
- Enter a prompt to generate a description
- Translate the description into multiple languages
- Choose a voice for text-to-speech functionality

Install the required dependencies:
pip install streamlit pillow google-generativeai pyttsx3 googletrans

Run the Streamlit app:
streamlit run app.py

Usage
Launch the app by running the command above.

Upload an image file in JPEG format.

Enter a prompt for generating the description.

Choose a voice for the audio output.

Select a language for translation.

Notes
Ensure you have the API key for Google Generative AI configured in your script.

The app currently supports translation into English, Hindi, Odia, Telugu, Tamil, Punjabi, Malayalam, and Marathi.

Final project

# Emotion Detection Application

A web application built with Flask that analyzes text and detects emotions such as anger, disgust, fear, joy, and sadness using natural language processing logic. It identifies the dominant emotion and provides an error message for invalid or blank inputs.

## Features

- **Emotion Analysis:** Breaks down text into percentage scores for key emotions.
- **Dominant Emotion Detection:** Highlights the strongest emotion detected in the given text.
- **Input Validation:** Safely handles blank or invalid inputs with a clean warning message.
- **Web Interface:** Includes an interactive frontend connected to a Flask backend.

## Project Structure

```text
final_project/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── static/
│   └── mywebscript.js
├── templates/
│   └── index.html
├── server.py
├── test_emotion_detection.py
└── README.md


Getting Started
Prerequisites
Make sure you have Python and Flask installed in your environment:

Bash
pip install flask
Running the Application
Navigate to the project directory:

Bash
cd final_project
Start the Flask server:

Python
python3 server.py
Open your browser and navigate to the local server URL provided by Flask (typically http://localhost:5000 or via your workspace preview proxy).

Testing
Run unit tests to verify the emotion detection functionality:

Bash
python3 -m unittest test_emotion_detection.py

# Bidirectional Sign Language Detection and Generation System

## About the Project
This project is a bidirectional sign language communication system developed using computer vision and generative AI. It is designed to help bridge the communication gap between sign language users and people who are unfamiliar with sign language.

The system recognizes hand gestures through a webcam and converts them into text. It also allows users to enter text and view the corresponding sign representations as a sequence of images.

## Features
- **Sign Language Detection:** Recognizes hand gestures captured through a webcam using a trained CNN model.
- **Hand Detection:** Uses MediaPipe to detect and track hand landmarks during gesture recognition.
- **Gesture-to-Text Conversion:** Converts recognized gestures into characters and combines them into text.
- **AI-Based Text Interpretation:** Uses Google Gemini to process recognized character sequences and generate meaningful text.
- **Text-to-Sign Conversion:** Converts entered text into corresponding sign images displayed sequentially.
- **Interactive Interface:** Provides a simple interface for sign recognition and text-to-sign conversion using Streamlit.

## How It Works

### 1. Sign Language to Text
- Captures hand gestures using a webcam.
- Detects the hand using MediaPipe.
- Processes the captured hand region using OpenCV.
- Predicts the corresponding character using a trained CNN model.
- Combines recognized characters and uses Gemini AI to interpret them into text.

### 2. Text to Sign Language
- Accepts text input from the user.
- Processes the text character by character.
- Retrieves the corresponding sign images.
- Displays the images sequentially to represent the entered text.

## Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- MediaPipe
- NumPy
- Streamlit
- Google Gemini API
- Pillow (PIL)

## Project Objective
The objective of this project is to explore how computer vision and generative AI can be used to make communication more accessible by providing a simple way to convert hand gestures into text and text into visual sign representations.

---
```

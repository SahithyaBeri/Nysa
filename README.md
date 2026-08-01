

# Nysa Voice Assistant

## Overview

Nysa is a Python-based voice assistant developed in Jupyter Notebook. It uses speech recognition and text-to-speech technology to understand voice commands and perform tasks such as playing YouTube videos, searching Wikipedia, telling jokes, opening websites, sending WhatsApp messages, taking screenshots, and launching applications. The project demonstrates the integration of multiple Python libraries to build a simple desktop voice assistant. :contentReference[oaicite:0]{index=0}

---

## Features

- Voice command recognition
- Text-to-speech responses
- Play YouTube videos
- Search information from Wikipedia
- Tell the current time
- Generate random jokes
- Open Google, YouTube, and other websites
- Launch Google Chrome
- Launch Visual Studio Code
- Send WhatsApp messages
- Capture screenshots
- Exit the assistant using voice commands

---

## Technologies Used

- Python
- Jupyter Notebook
- SpeechRecognition
- PyAudio
- pyttsx3
- pywhatkit
- Wikipedia
- PyAutoGUI
- Webbrowser
- Datetime
- PyJokes

---

## Installation

Install the required libraries before running the notebook.

```bash
pip install SpeechRecognition
pip install PyAudio
pip install pyttsx3
pip install pywhatkit
pip install wikipedia
pip install pyjokes
pip install pyautogui
```

---

## Project Workflow

1. Initialize the speech recognition and text-to-speech engine.
2. Listen to the user's voice through the microphone.
3. Convert speech into text.
4. Identify the requested command.
5. Execute the corresponding action.
6. Respond using speech output.

---

## Supported Commands

- Play `<song name>`
- What's the time
- Who is `<person>`
- Joke
- Open Google
- Open YouTube
- Open Chrome
- Open VS Code
- Send WhatsApp
- Screenshot
- Exit
- Stop

---

## Output

The assistant continuously listens for voice commands and executes supported tasks. If a command is not recognized, it informs the user and waits for another command. :contentReference[oaicite:1]{index=1}

---

## Future Improvements

- Weather updates
- Email automation
- Google Calendar integration
- Reminder and alarm system
- AI chatbot integration
- Multi-language support

---

## Author

**Sahithya BR**

B.Tech in Computer Science and Engineering (Artificial Intelligence and Machine Learning)

---

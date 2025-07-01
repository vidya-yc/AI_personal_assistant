🤖 Python Personal Assistant

A voice-activated personal assistant built using Python that helps automate tasks, answer questions, and boost productivity with ease. This assistant can perform tasks such as web search, weather updates, opening applications, and more—all through simple voice commands.

🎯 Features

🔍 Web Search: Search Google, Wikipedia, or YouTube with voice input

🗕️ Date & Time: Announces the current time and date

☀️ Weather Info: Provides real-time weather updates

📂 Open Applications: Launches local apps like Notepad, Chrome, or your code editor

✉️ Send Emails: Can send pre-defined emails using SMTP

🎵 Play Music: Plays music from a specified directory

🗣️ Text-to-Speech (TTS) and Speech Recognition for smooth interaction

⚙️ Tech Stack

Python 3.x

pyttsx3 – Text-to-Speech engine

speech_recognition – Speech-to-Text conversion

datetime, os, webbrowser, smtplib – For core functionalities

Optional: requests, wolframalpha for weather or factual queries

🚀 How to Run

Clone the repository:

git clone https://github.com/yourusername/personal-assistant-python.git

Install required packages:

pip install -r requirements.txt

Run the script:

python assistant.py

🧐 How It Works

The assistant listens via the microphone.

Recognizes speech using Google’s speech API.

Responds via a TTS engine.

Executes tasks based on recognized keywords or commands.

📌 Example Commands

“What’s the weather today?”

“Open YouTube”

“Send an email to [name]”

“Play music”

“What time is it?”

🔒 Note

Make sure your microphone is working properly.

Some features like email or weather may require API keys or login credentials (not included in repo).

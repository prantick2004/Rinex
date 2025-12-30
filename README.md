🤖 Nova AI – Voice Assistant (Python)

Nova AI is a simple Python-based voice assistant that can listen to user voice commands and perform basic tasks like opening websites (YouTube, ChatGPT, WhatsApp) using voice input.
This project is created for learning Python, speech recognition, and system automation.



🚀 Features

🎤 Voice input using microphone
🗣️ Text-to-speech response using espeak
🌐 Open websites using voice commands
🔁 Continuous listening mode
💻 Works on Ubuntu/Linux


🛠️ Technologies & Libraries Used

Python 3
speech_recognition
webbrowser
os
espeak
alsa-utils (for audio support on Linux)


📥 Installation Guide

1️⃣ Clone the repository
1. git clone git@github.com:prantick2004/Rinex.git
2. cd Rinex
2️⃣ Install Python dependencies
1. pip install SpeechRecognition wikipedia openai
3️⃣ Install system audio dependencies (Ubuntu)
1. sudo apt update
2. sudo apt install espeak alsa-utils portaudio19-dev
▶️ How to Run the Project
1. python main.py

After running, speak commands like:

open youtube
open chatgpt
open whatsapp


🧠 Project Workflow

Microphone captures user voice
Speech is converted to text
Command is processed
Action is executed (open website / response)
Assistant replies using voice


📈 Development Progress
✅ Day 1: Environment setup & library installation
✅ Day 2: Basic voice input & speech output
✅ Day 3: Git & GitHub integration
✅ Day 4: Website automation using voice commands
🔄 Day 5+: System control & AI enhancements (planned)

👨‍💻 Author

Prantick Maity
BCA Student | Python & AI Enthusiast

📜 License
This project is created for educational and learning purposes.

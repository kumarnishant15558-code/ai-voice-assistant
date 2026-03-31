# 🤖 Alexa - AI Voice Assistant 🎤

Alexa is a Python-based AI Voice Assistant inspired by Amazon's Alexa, designed to interact with users through natural voice commands. It continuously listens for the wake word "Alexa", processes spoken instructions, and responds intelligently using speech synthesis.

## ✨ Features

- 🎙️ Wake-word detection ("Alexa")
- 🧠 Speech Recognition using Google API
- 🔊 Text-to-Speech responses with pyttsx3
- 🌐 Open websites like YouTube, Gmail, Spotify, ChatGPT
- 📰 Fetch latest news headlines (NewsAPI)
- 🌦️ Real-time weather updates (OpenWeatherMap API)
- 🤖 AI-powered conversations using Mistral (OpenRouter)
- 🔁 Continuous listening loop with real-time interaction

## 🛠️ Tech Stack

- Python 
- SpeechRecognition
- pyttsx3
- Requests
- Webbrowser
- OpenRouter API (Mistral AI)
- OpenWeatherMap API
- NewsAPI

## ⚙️ How It Works

1. The assistant listens for the wake word **"Alexa"**
2. Once activated, it captures the user's voice command
3. Processes the command and performs actions like:
   - Opening websites 🌐
   - Fetching news 📰
   - Providing weather updates 🌤️
   - Chatting using AI 🤖
4. Responds back with voice output

## 🚀 Run the Project

```bash
pip install speechrecognition pyttsx3 requests
python main.py

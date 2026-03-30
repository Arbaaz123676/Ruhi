# 🤖 Ruhi – AI Voice Assistant

Ruhi is a Python-based AI voice assistant inspired by systems like Alexa and Google Assistant. It can listen to voice commands, process them using AI, and respond with natural speech.

---

## 🚀 Features

* 🎤 Voice recognition using SpeechRecognition
* 🧠 AI-powered responses using OpenAI API
* 🔊 Text-to-speech output using gTTS
* 🌐 Open popular websites (Google, YouTube, LinkedIn, etc.)
* 🎵 Play music from a custom music library
* 📰 Fetch and read latest news headlines
* ⚡ Wake-word detection ("Ruhi")

---

## 🛠️ Tech Stack

* Python
* SpeechRecognition
* OpenAI API
* gTTS (Google Text-to-Speech)
* Requests (for APIs)
* Webbrowser
* (Optional) pygame / playsound

---

## 📂 Project Structure

```bash
Ruhi/
│── main.py              # Main assistant script
│── musicLibrary.py      # Custom music links
│── requirements.txt     # Dependencies
│── README.md
```

---

## Setup Instructions

### Clone the repository

```bash
git clone https://github.com/Arbaaz123676/Ruhi.git
cd Ruhi
```

### Create virtual environment (recommended)

```bash
python3 -m venv venv
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## Environment Variables

Create a `.env` file:

```env
OPENAI_API_KEY=your_openai_api_key
NEWS_API_KEY=your_news_api_key
```

---

## Run the Assistant

```bash
python3 main.py
```

Say:

```
"Ruhi"
```

Then give commands like:

* "Open Google"
* "Play song"
* "Tell me news"
* "What is AI?"

---

## How It Works

1. Listens for wake word ("Ruhi")
2. Captures voice command
3. Matches predefined commands OR
4. Sends query to OpenAI for AI response
5. Converts response to speech and plays it

---

## Known Issues

* Microphone detection may vary across systems
* pygame audio may fail on some macOS setups
* Requires stable internet connection

---
# Sunny - AI Voice Assistant

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

Sunny is an advanced AI voice assistant designed to simplify your digital life through natural voice commands. With capabilities ranging from web searches to smart home control, Sunny brings Jarvis-like functionality to your desktop.

## Features

### Voice Control
- Wake word activation ("Sunny")
- Natural language processing
- Text-to-speech responses

### Productivity
- Open applications and websites
- Google Calendar integration
- Set reminders and alarms
- Manage meetings and events

### Media Control
- Spotify integration (play/pause/skip)
- YouTube search
- Local music playback

### Smart Features
- Weather forecasts
- WolframAlpha calculations
- Wikipedia lookups
- AI-powered Q&A (HuggingFace)

### Communication
- WhatsApp messaging
- Contact management

### System Control
- Brightness adjustment
- Shutdown/restart/sleep commands
- Application launcher

## Installation
 Clone the repository:
```bash
git clone https://github.com/yourusername/sunny-voice-assistant.git
cd sunny-voice-assistant
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Configure API keys:

Rename config.example.json to config.json

Add your API keys for:

OpenWeatherMap

WolframAlpha

HuggingFace

Spotify

Setup
Microphone Configuration
Run the microphone check:

```bash
python microphone.py
```
Spotify Setup
Create a Spotify Developer application

Add your credentials to config.json

Test with:

```bash
python spotify.py
```

Google Calendar
Enable Google Calendar API

Place credentials.json in project root

Authenticate on first run

Usage
```bash
python main.py
```
Basic Commands
"Sunny open chrome"

"Sunny what's the weather in London?"

"Sunny play Imagine Dragons on Spotify"

"Sunny set reminder to call mom at 5 PM"

File Structure
text
sunny-voice-assistant/
├── main.py               # Main application
├── spotify.py            # Spotify integration
├── microphone.py         # Audio setup
├── config.json           # API configuration
├── credentials.json      # Google OAuth
├── token.json            # Auth tokens
├── requirements.txt      # Dependencies
└── README.md
Contributing
Contributions are welcome! Please follow these steps:

Fork the repository

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some amazing feature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

License
Distributed under the MIT License. See LICENSE for more information.

Contact
Your Name - saathvikk202@gmail.com
Project Link: https://github.com/sunny18-max/sunny-assistant


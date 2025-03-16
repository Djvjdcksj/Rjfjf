# Jarvis Voice Assistant 🎙️✨

Welcome to **Jarvis Voice Assistant** – your personal AI companion built with pure JavaScript! Inspired by Tony Stark's JARVIS, this voice-activated assistant listens to your commands and responds with a smooth, natural voice. Set reminders ⏰, check the time 🕒, or search YouTube 🎥 – Jarvis does it all using browser's `SpeechRecognition` and `SpeechSynthesis` APIs. No external APIs, just pure browser magic! 🚀

## Features 🌟
- **Voice Commands**: Say "What's the time now?" or "Set timer you have to go home after 5 minutes" 🎤
- **Smart Reminders**: Get reminded later – "Reminder: you have to go home" ⏳
- **YouTube Search**: "Search for funny cat videos" and Jarvis opens it! 📺
- **Wikipedia Lookup**: Ask "Who is Elon Musk?" for a quick summary 🧠
- **Song Playback**: "Play song Shape of You" – straight to YouTube 🎶
- **Sleek UI**: Round gray mic button that pulses red when listening 🎙️🔴

## Prerequisites ⚙️
- **Chrome Browser**: For `SpeechRecognition` to work 🌐
- **Hosting**: Chrome doesn’t allow mic access via `file://`, so you need to serve it over `http://` or `https://` (see options below) 🖥️

## How to Use 🛠️
`SpeechRecognition` requires a server because of Chrome’s security policy. You can either use a local server or GitHub Pages. Choose your preferred method:

### Option 1: GitHub Pages (Recommended) 🌍
No local setup needed! Host it directly on GitHub Pages:
1. Clone or fork this repo:
   ```bash
   git clone https://github.com/your-username/jarvis-voice-assistant.git
   Push to your repository if not already done:
   git push origin main
   Enable GitHub Pages:
Go to repo Settings > Pages.
Set Source to main branch and / (root) folder.
Save and wait a minute.
Visit: https://your-username.github.io/jarvis-voice-assistant/
Tap the mic button and start talking! 🎤
Option 2: Local Server 🌐
Run it locally if you prefer:

Clone the repo:
git clone https://github.com/your-username/jarvis-voice-assistant.git
cd jarvis-voice-assistant
Set up a local server:
Node.js Server
Install Node.js: Download Node.js
Install http-server:
npm install -g http-server
Run:
http-server
Open http://localhost:8080 in Chrome.
Python Server
If Python is installed:
python -m http.server 8000
Open http://localhost:8000 in Chrome.
Allow mic permissions and start using Jarvis! 🎙️
Example Commands 🎉
⏰ "Set timer you have to go home after 5 minutes"
🕒 "What's the time now?"
📅 "What's the date?"
🎥 "Search for funny cat videos"
🎵 "Play song Despacito"
Tech Stack 💻
HTML/CSS: Dark-themed UI with a stylish mic button 🎨
JavaScript: Drives speech recognition, synthesis, and logic 🧩
Browser APIs: SpeechRecognition for listening, SpeechSynthesis for talking 🗣️
Why Jarvis? 🤔
Who doesn’t want a smart assistant straight out of Iron Man? Built for fun, learning, and a touch of sci-fi! ⚡
Contribute 🌈
Found a bug? Want a new feature? Fork it, tweak it, and send a PR! Let’s make Jarvis smarter together. 🙌
License 📜
MIT – Free to use, modify, and share! 🎁

⭐ Star this repo if you like it! Follow me for more cool projects. Happy coding! 🚀✨
Next Steps:
GitHub Pages Enable Karein (agar abhi nahi kiya):
Repo ke Settings > Pages mein jayein.
Source ko main branch aur / (root) select karen.
Save karen, aur 1-2 minute baad https://your-username.github.io/jarvis-voice-assistant/ try karen.
Test Karein: URL kholen, mic button dabayein, aur commands try karen

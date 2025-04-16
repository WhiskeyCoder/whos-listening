🎧 Who's Listening?
A simple Python script to list all audio input/output devices on your system — complete with index numbers for easy reference in your audio projects.

Useful when working with audio libraries like PyAudio, sounddevice, or speech_recognition, where selecting the correct device index can be a pain in the aux.

🛠 Features
Lists all connected audio devices (microphones, speakers, virtual cables, etc.)

Displays device index and name for direct reference in your audio apps

Lightweight, no unnecessary fluff

Works on Windows, macOS, and Linux

# 🚀 Getting Started
## 📦 Installation
Make sure you have pyaudio installed:
```pip install pyaudio```

## ⚠️ Note: On some systems, PyAudio may require portaudio or build tools.
- For Windows: use precompiled wheels if needed.
- For macOS: brew install portaudio
- For Linux: sudo apt-get install portaudio19-dev


## 📄 Usage
Run the script with Python:
```python whos_listening.py```

You'll get output like this:


```
Index: 0, Name: Microsoft Sound Mapper - Input
Index: 1, Name: Microphone (Realtek Audio)
Index: 2, Name: VB-Audio Virtual Cable
Index: 3, Name: VoiceMeeter AUX Output
...
```
Use the index number in your projects to select the correct device.


## 💻 Example Use Case
Say you're building a speech recognition app or audio router, and you want to send/receive audio to a specific interface (like a USB mic or virtual cable).
Just run this tool to find your device’s index fast.

## 🧠 Why?
Because figuring out which device is "index 3" shouldn't require psychic powers.
This tool makes audio device selection dead-simple — no GUI needed.

## 🧙‍♂️ Author
Made with 💡, 🤖, and probably a few swear words by WhiskeyCoder
Aka: the guy who measured a coffee machine in Doritos

## 📜 License
MIT — because open source is love 💕

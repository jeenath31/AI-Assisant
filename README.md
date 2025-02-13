# Voice-Activated AI Assistant

A voice-controlled AI assistant powered by **OpenAI's DeepSeek-Chat**, capable of recognizing speech, generating responses, and interacting with web browsers.

## Features
- **Speech Recognition**: Converts voice commands to text using `speech_recognition`.
- **AI-Powered Responses**: Generates intelligent replies using **DeepSeek-Chat API**.
- **Text-to-Speech**: Converts AI responses into voice using `pyttsx3`.
- **Web Automation**: Opens websites like Google and YouTube with voice commands.

## Requirements
Install dependencies before running the script:
```bash
pip install openai speechrecognition pyttsx3
```

## Setup
1. **Clone the Repository**:
   ```bash
   git clone <your-repo-url>
   cd <your-repo-name>
   ```
2. **Add API Key**:
   - Open `apikey.py` and replace the placeholder with your DeepSeek API key.
3. **Run the Assistant**:
   ```bash
   python app.py
   ```
4. **Interact with the Assistant**:
   - Speak commands, and the AI will respond.
   - Say `"Open YouTube"` or `"Open Google"` to launch sites.
   - Say `"Bye"` to exit.

## Notes
- Ensure your microphone is working properly for accurate voice recognition.
- Modify `app.py` to add more voice commands as needed.

## Contributing
Feel free to fork this repository and improve the assistant by adding new features.

---
Let me know if you need modifications! 🚀


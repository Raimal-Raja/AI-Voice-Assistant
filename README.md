# Jarvis Voice Assistant

Jarvis is a Python-based voice assistant that can perform various tasks such as opening websites, playing music, reading news headlines, and answering questions using AI. It uses speech recognition to listen for commands and text-to-speech to respond.

## Features

- Voice activation using the wake word "Jarvis"
- Opens popular websites (Google, Facebook, YouTube, LinkedIn)
- Plays music from a predefined library
- Reads top news headlines
- Answers questions and performs tasks using OpenAI's GPT-3.5 model
- Text-to-speech functionality for responses

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.6+
- pip (Python package manager)
- A microphone connected to your computer

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/jarvis-voice-assistant.git
   ```
2. Navigate to the project directory:
   ```
   cd jarvis-voice-assistant
   ```
3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Configuration

Before running the assistant, you need to set up the following:

1. OpenAI API Key: Replace `"sk-proj-ruhZLbxKEyDCY4CPtc1jT3BlbkFJqcf8ppZ5Vvj0BZDD1T68"` with your actual OpenAI API key.
2. News API Key: Replace `"6e7540f473254def9e9b8be4e7717f94"` with your actual News API key from [NewsAPI.org](https://newsapi.org/).
3. Music Library: Update the `musicLibrary.py` file with your preferred music tracks and their corresponding URLs.

## Usage

Run the script:
```
python jarvis_assistant.py
```

1. Wait for Jarvis to initialize.
2. Say "Jarvis" to activate the assistant.
3. After Jarvis responds with "Ya", speak your command or question.

## Available Commands

- "Open Google/Facebook/YouTube/LinkedIn": Opens the respective website.
- "Play [song name]": Plays the specified song from your music library.
- "News": Reads out the latest news headlines.
- Any other command or question will be processed by the AI model.

## Dependencies

- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/): For converting speech to text.
- [pyttsx3](https://pypi.org/project/pyttsx3/): For text-to-speech conversion.
- [gTTS](https://pypi.org/project/gTTS/): Google Text-to-Speech API for alternative speech output.
- [pygame](https://www.pygame.org/): For playing audio files.
- [requests](https://docs.python-requests.org/en/latest/): For making HTTP requests to the News API.
- [openai](https://github.com/openai/openai-python): For interacting with OpenAI's GPT models.

## Additional Resources

1. [Python Speech Recognition Tutorial](https://realpython.com/python-speech-recognition/)
2. [OpenAI API Documentation](https://platform.openai.com/docs/api-reference)
3. [NewsAPI Documentation](https://newsapi.org/docs)
4. [Pygame Documentation](https://www.pygame.org/docs/)
5. [Text-to-Speech in Python](https://realpython.com/python-speech-recognition/)

## Troubleshooting

- If you encounter issues with speech recognition, ensure your microphone is properly connected and configured.
- For OpenAI API errors, check that your API key is correct and you have sufficient credits.
- If news headlines are not being read, verify your News API key and internet connection.

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the [issues page](https://github.com/yourusername/jarvis-voice-assistant/issues) if you want to contribute.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

This project uses various APIs and services. Ensure you comply with their respective terms of service. The authors are not responsible for any misuse or violations.

# Text-To-Speech

## Overview
This project is a **Text-To-Speech (TTS)** application that converts text into natural-sounding speech. It supports multiple languages and speakers, allowing users to generate speech output for different use cases such as accessibility tools, audiobooks, and automated announcements.

## Features
- Supports multiple languages.
- Allows selection of different speakers/voices.
- Easy-to-use Python script and web-based interface.
- Fast and efficient text-to-speech conversion.
- Simple dependency installation.

## Requirements
To run this project, install the required dependencies using:

```bash
pip install -r requirements.txt
```

## Installation and Setup
1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/text-to-speech.git
   cd text-to-speech
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   - If using the script-based approach:
     ```bash
     python tts-script.py
     ```
   - If using the web-based interface:
     ```bash
     python tts-app.py
     ```

## Usage
### Using the Script (`tts-script.py`)
- Run `tts-script.py` and enter the text you want to convert.
- Choose the language and speaker from the available options.
- The script generates an audio file that you can play.

### Using the Web Application (`tts-app.py`)
- Start the Flask-based web app by running `python tts-app.py`.
- Open your browser and go to `http://127.0.0.1:5000/`.
- Enter the text, select language and speaker, and generate speech output.
- Download or play the generated audio file.

## File Descriptions
| File | Description |
|------|-------------|
| `tts-script.py` | Standalone script for text-to-speech conversion |
| `tts-app.py` | Flask-based web application for TTS |
| `languages.py` | Contains supported languages for the TTS system |
| `speakers.py` | Lists available speakers/voices |
| `models.py` | Handles backend logic for processing TTS requests |
| `requirements.txt` | List of dependencies required to run the project |
| `README.md` | Documentation for the project |

## Contribution
Feel free to fork this repository and contribute by submitting pull requests. For major changes, open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any issues or questions, please reach out via [your-email@example.com] or open an issue on GitHub.

---
Happy Coding! 🎧🗣


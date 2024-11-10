Here's a **README.md** file for this project:

---

# Desktop Voice-Assisted Screenshot AI

This project is an advanced desktop AI assistant that combines real-time screenshot capture with voice recognition. Using OpenAI's language model, the assistant can interpret voice prompts, analyze screen content, and provide spoken responses to user queries. The application is ideal for hands-free desktop interaction, offering assistance based on visual and auditory input.

## Features
- **Real-Time Desktop Capture**: Continuously captures and processes desktop screenshots.
- **Voice Recognition**: Listens for user commands, with support for multiple languages (default: German).
- **AI-Driven Responses**: Provides intelligent answers by analyzing both voice input and screen content.
- **Text-to-Speech (TTS)**: Speaks responses aloud for a hands-free experience.

## Technologies Used
- **Python**: Core application logic
- **OpenAI Language Model**: Natural language processing and response generation
- **SpeechRecognition & PyAudio**: For audio capture and processing
- **CV2 & PIL**: For image handling and desktop screenshot capture
- **LangChain**: Customizable prompt handling and chat history

## Getting Started

### Prerequisites
- Python 3.8+
- Required libraries (install with `pip install -r requirements.txt`):
  - `numpy`, `opencv-python`, `pyaudio`, `speech_recognition`, `openai`, `langchain`, `python-dotenv`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/desktop-voice-assistant.git
   cd desktop-voice-assistant
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up your OpenAI API key in a `.env` file:
   ```
   OPENAI_API_KEY=your_openai_api_key
   ```

### Usage
1. Start the desktop screenshot capture:
   ```python
   python main.py
   ```
2. Speak into your microphone when prompted. The assistant will analyze your screen and respond audibly.

### Controls
- **Exit**: Press `ESC` or `q` to close the application.

## Project Structure
- `DesktopScreenshot`: Manages real-time desktop screenshot capture and encoding.
- `Assistant`: Handles AI prompt creation, response generation, and TTS.
- **Voice Recognition Callback**: Listens for audio commands and interacts with the assistant.

## Contributing
Contributions are welcome! Please fork the repository and open a pull request.

---

This README provides a concise overview, setup instructions, and usage information for the voice-assisted desktop AI project. Adjust as needed for additional details or dependencies.

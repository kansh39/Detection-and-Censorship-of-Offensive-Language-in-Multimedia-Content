# Speech-to-Text Transcription and Toxic Language Detection

This project performs accurate speech-to-text transcription using OpenAI's **Whisper model** and detects offensive or toxic language using a **Toxic BERT model**. It is designed to handle large audio files by splitting them into manageable chunks, transcribing them, and analyzing the text for harmful language.

## Features

- **Whisper Model Integration**: Highly accurate speech-to-text transcription, supporting multiple languages and robust against background noise.
- **Toxic Language Detection**: Implements **Toxic BERT** to identify offensive or harmful content in the transcribed text.
- **Chunk Processing**: Splits long audio files into smaller chunks for efficient processing.
- **Customizable Pipeline**: Can be extended for language detection, sentiment analysis, or other NLP tasks.

---

## Workflow

1. **Extract Audio**: Extract audio from video files (e.g., `.mp4`) or use a standalone audio file (e.g., `.wav`).
2. **Transcription**: Use the **Whisper model** to transcribe the speech into text.
3. **Chunk Processing**: Divide audio into smaller chunks for easier handling and transcription.
4. **Toxicity Detection**: Use **Toxic BERT** to analyze the transcription for toxic or offensive language.
5. **Output**: Save the transcription and toxicity analysis results to a text file.

---

## Tools and Technologies

- **Python**: Core programming language.
- **Whisper**: OpenAI's advanced speech-to-text model.
- **Toxic BERT**: Pre-trained model for toxic content detection.
- **SpeechRecognition**: Library for basic audio processing.
- **Torchaudio**: Handles audio preprocessing and manipulation.
- **MoviePy**: Extracts audio from video files.
- **Joblib**: Saves and loads models or intermediate data for faster processing.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

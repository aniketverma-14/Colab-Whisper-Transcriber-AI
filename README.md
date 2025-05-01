# Colab Whisper Transcriber AI

A simple yet powerful audio transcription tool powered by [OpenAI's Whisper](https://github.com/openai/whisper) model and hosted on Google Colab. Easily convert speech from audio files into accurate text—without installing anything locally!

## Features

- Powered by OpenAI's Whisper ASR model
-  Runs entirely on Google Colab (no local setup required)
-  Supports multiple audio formats (MP3, WAV, M4A, etc.)
-  Multilingual support
-  Lightweight UI built with Gradio
-  Free, fast, and accurate

---

##  How to Use

1. **Open the Colab Notebook**  
   [Click here to launch](https://colab.research.google.com/github/aniketverma-14/Colab-Whisper-Transcriber-AI/blob/main/Colab-Whisper-Transcriber.ipynb)

2. **Follow the Steps in Notebook**
   - Mount Google Drive (optional)
   - Install required dependencies (Whisper, FFmpeg, Gradio)
   - Upload your audio file
   - Run the transcription cell
   - Download or copy the transcribed text

---

## Under the Hood

- **Model**: OpenAI Whisper (base/medium/large, depending on settings)
- **Environment**: Python 3.x in Google Colab
- **Key Libraries**:
  - `whisper`
  - `ffmpeg-python`
  - `gradio`
  - `torch`

---

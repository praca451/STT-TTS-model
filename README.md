# STT-TTS Model

This repository provides a framework to process MP3 files for transcription, summarization, and text-to-speech synthesis.

## Features
- Convert MP3 to WAV format.
- Transcribe audio using Vosk.
- Summarize transcriptions with Hugging Face Transformers.
- Generate a voice message for the summary using Coqui Text-to-Speech (TTS).

## How It Works
- Input: MP3 audio file.
- Transcription: Converts speech in the audio to text.
- Summarization: Creates a summarized version of the transcribed text.
- Audio Output: Produces a voice message summarizing the input audio.

## Use Cases
- Podcast or lecture summaries.
- Quick overviews of meetings or discussions.
- Accessibility for audio-based content.

## Requirements
Install dependencies using:
```bash
pip install -r requirements.txt


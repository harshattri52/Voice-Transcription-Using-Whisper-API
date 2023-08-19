# Voice-Transcription-Using-Whisper-API

## Overview

This is a web application that allows users to interact with a chatbot using voice input. It integrates the Whisper API for voice transcription and the Chatgpt API for generating chatbot responses.

## Features

- Record and transcribe voice input using the Whisper API.
- Generate chatbot responses using the ChatGPT API based on transcribed text.
- User-friendly interface with a microphone button for voice input.
- Real-time display of chatbot responses.
- Responsive design for a seamless experience across devices.

## How to Use

1. Clone the repository to your local machine.
2. Set up your API keys:
   - Obtain Whisper API key from [Whisper API Documentation](link-to-whisper-api-docs).
   - Obtain ChatGPT API key from [ChatGPT API Documentation](link-to-chatgpt-api-docs).
3. In the project directory, create a `.env` file and add your API keys:
   ```plaintext
   WHISPER_API_KEY=your_whisper_api_key
   CHATGPT_API_KEY=your_chatgpt_api_key

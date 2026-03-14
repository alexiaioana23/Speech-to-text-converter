# Speech-to-text-converter
A simple Speech-to-Text web application built with **Python** and **Streamlit**.  
The application allows users to convert spoken audio into text either by uploading an audio file or by using live microphone input.

## Features

- Upload and transcribe `.wav` audio files
- Live speech recognition using microphone
- Simple web interface built with Streamlit
- Uses Google Speech Recognition API for transcription
- Progress bar while processing audio files

## Technologies Used

- Python
- Streamlit
- SpeechRecognition
- PyAudio
- tempfile
- OS and Time modules

## How It Works

The application provides two main functionalities:

### 1. Audio File Transcription
Users can upload a `.wav` audio file and the application will:
1. Save the file temporarily.
2. Process the audio.
3. Send the audio to Google Speech Recognition.
4. Display the transcribed text.

### 2. Live Speech Recognition
Users can start live speech recognition using their microphone.  
The application continuously listens and converts spoken words into text until the user says **"stop"**.

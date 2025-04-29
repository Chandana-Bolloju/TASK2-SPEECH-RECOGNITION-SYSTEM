# TASK2-SPEECH-RECOGNITION-SYSTEM

*COMPANY*  : CODTECH IT SOLUTIONS

*NAME*   : CHANDANA BOLLOJU

*INTERN ID*  : CT04WT69

*DOMAIN*  : ARTIFICIAL INTELLIGENCE

*DURATION*  : 4 WEEKS

*MENTOR*  : NEELA SANTOSH

This Python script captures audio input from a microphone and converts spoken words into text using Google's Speech Recognition API.

Key Features
✅ Real-Time Audio Capture – Listens to microphone input and processes speech.
✅ Google Speech Recognition – Uses recognize_google() for accurate transcription.
✅ Error Handling – Gracefully manages cases where:

Audio is unclear (UnknownValueError)

API requests fail (RequestError)

How It Works
Initialization

Creates a Recognizer object to process audio.

Microphone Input

Opens the default microphone (sr.Microphone()) and listens for speech.

Displays "Listening..." while waiting for input.

Speech-to-Text Conversion

Uses Google's API (recognize_google()) to transcribe audio.

Prints the recognized text with "You said:" prefix.

Error Handling

If speech is unclear → "Sorry, I could not understand the audio."

If API request fails → Displays the specific error.

*OUTPUT*  :

![Image](https://github.com/user-attachments/assets/7a9095c6-3e46-4a32-a6f7-a434edb9ceb6)


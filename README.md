# Type-talk

Type-Talk is a web and console-based application designed to improve communication by integrating:

* Text-to-Speech (TTS)
* Speech-to-Text (STT)
* Real-time Language Translation

1. Web Application Modules

    1. Text-to-Speech (TTS)

    This module converts user-entered text into speech using the Web Speech API.

    * Method:

    * User enters text in textarea
    * JavaScript uses `SpeechSynthesisUtterance`
    * Browser outputs audio

    2. Speech-to-Text (STT)

    This module converts voice input into text.

    * Method:

    * Uses Web Speech Recognition API
    * Captures audio through microphone
    * Displays converted text in textarea

2. Console Application (Python)

    Description:

    The Python script `trans.py` performs real-time voice translation.

    Method:

    1. Capture voice using `speech_recognition`
    2. Convert speech to text
    3. Translate text using `deep_translator`
    4. Convert translated text to speech using `gTTS`
    5. Play audio output

3. Technologies Used

    * HTML, CSS, JavaScript
    * Web Speech API
    * Python
    * speech_recognition
    * gTTS
    * deep-translator

4. how to Run

    Web App:

    Open `index.html` in browser (Chrome recommended)

    Python App:

    Run `trans.py` in VS Code terminal

5. Future Improvements

* Add more languages
* Improve speech accuracy
* Build mobile version

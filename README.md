# text-to-speech
A project to convert text to speech

High level architecture. 
1. first develop text to speech using python in a separate workspace
2. Enhance it to have grammar correction
3. Add a frontend (HTML editor) to receive text
4. connect the frontend and backend
5. publish the application as Web Page for public use.

## Create Python Virtual Environment  
```
python -m venv text_to_audio
.\text_to_audio\Scripts\activate
```

## Install require software
1. Flask: for the backend API.
2. language_tool_python: for grammar and spelling correction.
3. pyttsx3: for offline text-to-speech conversion.
```
pip install flask language_tool_python pyttsx3
```

## Use of Google Speech
```
pip install gTTS
```

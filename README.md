# Chatbot
Chatbot development 
VOICE CHATBOT FRAMEWORK
A.	CHATTERBOT
	ChatterBot is a Python Library consists of function to generate automatic response to user’s input. This library uses a selection of machine learning algorithm to produce different types of responses [1].
	The design of ChatterBot allows it to be trained to speak in any language and also the machine-learning nature allows it’s to improve the performance and accuracy. 
ChatterBots starts with an untrained instances which have no knowledge on how to communicate. Each time a user enters a statement, the library saves the text that they entered and the text that the statement response to. The accuracy of each response will increases as it received more input statement and responses. The program will select the closest matching response by searching the closest matching know statement that matches the input, then it will chooses a response from the selection of known responses to that statement.
	For deployment, the ChatterBot can be easily be integrated with Django.
B.	TTS(TEXT TO SPEECH)
	Text To Speech (TTS) is a process when given a text string, it will convert the text into speeches [2]. For python, there are a few library that can be use for this purposes. The list is as below;
1)	Pyttsx
This wrapper can be used in cross platform and uses the speech engines based on the operating system. In order to use this wrapper, we need to install the pyttsx module. For python3 we need to install pyttsx3 module.

nsss - NSSpeechSynthesizer on Mac OS X 10.5 and higher
sapi5 - SAPI5 on Windows XP, Windows Vista, and (untested) Windows 7
espeak - eSpeak on any distro / platform that can host the shared library (e.g., Ubuntu / Fedora Linux)

2)	gTTS
This module and command line utility to save spoken text to mp3 and uses Google Text to Speech (TTS) API. The API can be accessed by installing the gTTS module.

3)	iOS TTS
This TTS is used inside an IOS operated system

4)	Microsoft speech engine
This engine can be used by installing the module win32com and calling the module in the program.

5)	IBM Watson TTS
IBM created its own TTS that can be access freely for a number of time. This API can support many language such as English, German, Spanish, French, Italian, Japanese and Portuguese. This API can be accessed by installing the TtsWatson module.

For our chatbot, we will use pyttsx3 module as our TTS module.
C.	SPEECH RECOGNITION
	Speech recognition is a process to convert speeches into text or variable. This is the opposite function of TTS. In python there is as specific library for this purpose called PyPI [3]. In order to use this library, we need to install the SpeechRecognition module.
	In this library, we have several speech recognition engine/API that we can use.

1)	CMU Sphinx (works offline)
2)	Google Speech Recognition
3)	Google Cloud Speech API
4)	Wit.ai
5)	Microsoft Bing Voice Recognition
6)	Houndify API
7)	IBM Speech to Text
8)	Snowboy Hotword Detection (works offline)

For our chatbot, we will be using Google API due to its accuracy.

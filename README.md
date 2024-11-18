Python script uses both speech recognition and sentiment analysis to analyze the sentiment of a user-provided sentence. The script listens to the user's voice, detects the language, and performs sentiment analysis using two methods: TextBlob and VADER.

Text-to-Speech (TTS): The script uses the pyttsx3 library to convert text to speech, allowing it to speak to the user.
Speech Recognition: The speech_recognition library is used to capture audio from the microphone and convert it into text.
Language Detection: The script uses the langdetect library to detect the language of the user's input.
Sentiment Analysis: It uses both TextBlob and VADER to analyze the sentiment of the recognized text. The sentiment score is averaged from both models and classified as Positive, Negative, or Neutral.

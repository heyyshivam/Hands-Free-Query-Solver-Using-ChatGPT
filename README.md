# Hands-Free-Query-Solver-Using-ChatGPT
User can start Python Script and he/ she triggers the model by saying "Hey Alexa" and tell the query afterwards, which will be decoded by the model using ChatGPT, and Google Voice Recognization Module. Then the answer will be converted to speech using another Text-To-Speech module.

Dependencies:

from pyChatGPT import ChatGPT
import speech_recognition as sr
import pyttsx3
import time

![Gemini_Generated_Image_e9vmise9vmise9vm](https://github.com/user-attachments/assets/206edd7d-e948-4b3f-a6d0-c23651518f4b) align="left" height="48" width="48" ></a>

# NBASeer-v1
This speech-to-speech AI bot is capable of interacting with humans via spoken audio and answering basic questions about NBA teams and their statistics. It uses an SQL database to answer questions with team data. The repo contains the python notebook and the model demos as mp3 filesand
 
WRITTEN BY AYUSH TALUKDER, MCPS BLAIR HIGH SCHOOL
VERSION 1: AUGUST 2024
## Code Overview:
The code uses Whisper to conduct speech-to-text and transcribe spoken user queries

It gets data from a SQL database of NBA team statistics

The code then feeds the text prompt into a text to SQL LLM to understand the prompt and get the data.

After, it uses an SLM to convert the SQL results to text so that the response is understandable to the person who asked the question.

Finally, it uses text-to-speech to convert the final text to a spoken LLM response, answering the question.


### Models Used:
Whisper for speech-to-text

LlamaCPP sql coder for text-to-SQL

gTTS for text-to-speech

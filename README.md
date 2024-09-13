<img src="https://github.com/user-attachments/assets/09270bcb-6e78-41c6-9d64-2c0300ab4145"
align left width=25% height=25%> 
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

## Audio Examples:

https://github.com/user-attachments/assets/31657c4a-9120-48bf-b09d-bc8ac9c1bda5


https://github.com/user-attachments/assets/5e54d61e-6efd-4140-ab74-2472d09ba4ea


https://github.com/user-attachments/assets/68218f82-c247-420b-be1a-57a34ff56fac


https://github.com/user-attachments/assets/cc1af1e2-c83a-4514-ac19-0d346f39a2e9


https://github.com/user-attachments/assets/06b1f853-fda2-4a61-82f5-7a9949f8eb26




https://github.com/user-attachments/assets/54472799-0ffe-4af9-8e79-7cd36eb0f5bc




https://github.com/user-attachments/assets/370ae509-de00-46e0-aab2-78988f89b5dc


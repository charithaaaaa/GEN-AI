# GEN-AI
#Automated-meeting-notes-generator
Automated Meeting Notes Generator (Google API)

Overview:
This project is an automated system designed to generate structured meeting notes from audio recordings using Google Cloud services, Retrieval-Augmented Generation (RAG), and Natural Language Processing (NLP) techniques.

Objective:
To convert meeting audio recordings into clean and concise meeting summaries automatically.

Technologies Used:
- Google Cloud Speech-to-Text API
- Python
- Pandas
- NLTK (Natural Language Toolkit)
- Gensim (text summarization)
- Sumy (alternative summarization library)
- Retrieval-Augmented Generation (RAG)
- pydub
- wave
- SpeechRecognition
- Regular Expressions (re)
- IPython.display (for notebook interactivity)

Workflow Overview:
1. Audio Input: Convert meeting audio recordings to WAV format.
2. Transcription: Use Google Speech-to-Text API for converting audio to text.
3. Text Cleaning: Use regular expressions and NLP techniques to preprocess and clean text.
4. Summarization: Apply Gensim or Sumy for extractive summarization.
5. RAG Integration: Use Retrieval-Augmented Generation to produce context-aware summaries.
6. Output: Return a structured and well-formatted summary of the meeting.

Results:
- Efficiently converts audio to readable and structured notes
- Delivers accurate transcription for clear audio files
- Produces actionable summaries using extractive and generative methods

Future Enhancements:
- Add speaker identification (diarization)
- Integrate with conferencing platforms like Zoom and Google Meet
- Develop a real-time meeting summarization dashboard

How to Run:
1. Clone the repository and navigate to the project directory
2. Install the required Python dependencies
3. Set up Google Cloud credentials and enable the Speech-to-Text API
4. Run the Jupyter notebook provided in the repository

Dataset or Audio:
Users can test the model using their own WAV audio recordings. Clear audio improves transcription accuracy.

This project is designed to automate the process of summarizing meetings and enhance productivity using AI.


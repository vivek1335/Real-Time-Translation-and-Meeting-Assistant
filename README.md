# Real-Time-Translation-and-Meeting-Assistant

LiveTranslate is an AI-based tool that transcribes live speech, translates it into a target language, and can summarize key points for meetings. It’s perfect for international teams to collaborate in real time.

**Features**

Real-Time Speech Transcription: Converts live audio or recorded meetings into text.

Translation: Translates transcripts into a target language.

Summarization (Optional): Summarizes key points from the meeting.

Multi-Language Support: Supports multiple source and target languages.

Export Transcripts: Saves transcripts and translations to a file.

**Requirements**

pip install openai-whisper transformers torch sounddevice numpy
pip install googletrans==4.0.0-rc1  # for translation

openai-whisper → for speech-to-text transcription

transformers → for summarization (optional)

googletrans → for translation

sounddevice → for capturing live audio

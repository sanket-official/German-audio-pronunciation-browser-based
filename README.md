# German-audio-pronunciation-browser-based
A browser-based prototype that helps nurses practice spoken German. Users can select key phrases, listen to a native example, record their voice, and get instant feedback on pronunciation accuracy, tone, and intonation. The app provides a similarity score with visual progress tracking and motivating feedback, making it easier and faster for nurses.

# Tech Stack Used

Python – Core programming language

Gradio – Browser-based interface for the demo

OpenAI Whisper – Speech-to-text transcription (German phrases)

gTTS (Google Text-to-Speech) – Generate native-sounding German audio

pydub – Audio manipulation (e.g., slowing playback for clarity)

Librosa  – Audio analysis for tone, pitch, and energy feedback

difflib.SequenceMatcher – Text similarity scoring between spoken and target phrases

# Challenges Faced

Ensuring accurate transcription since large whisper module consumes lot of GPU runtime 

Designing intuitive feedback so learners understand how to improve

Making the audio sound easier to follow

# What’s Needed to Go Live

powerful modules which can track accents and phrases accurately

Persistent user accounts to track long-term learning progress

Cloud deployment for scalability and multi-user access

UI/UX refinements for seamless recording, playback, and feedback.

Multiple voice options for more natural and empathetic practice experience.



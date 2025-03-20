YouTube Video Summarizer & AI Chatbot Extension

   An AI-powered Chrome extension that extracts key points from YouTube videos and allows users to ask queries about the summary using a Gemini AI chatbot. It also supports multilingual transcript fetching for broader accessibility!

Features:
* YouTube Video Summarization – Instantly extracts key points from any YouTube video.
* AI Chatbot (Gemini Integration) – Ask video-related queries and get intelligent responses.
* Multi-Language Transcript Support – Fetches and summarizes YouTube transcripts in multiple languages.
* Persistent Chat History – Saves conversations across videos for better continuity.
* User-Friendly Interface – Designed for seamless interaction within a Chrome extension.

Tech Stack:
* Frontend: HTML, CSS, JavaScript
* Backend: Python (Flask/FastAPI)
* AI Model: Gemini API
* Libraries: youtube-transcript-api, localStorage, Chrome Extension APIs

Clone the Repository:

    git clone https://github.com/your-username/youtube-ai-summarizer.git
    cd youtube-ai-summarizer

Install Backend Dependencies:

    pip install -r requirements.txt

Run the Backend Server:

    python app.py  # or flask run

Load the Chrome Extension:
* Open Chrome and go to chrome://extensions/.
* Enable Developer Mode (top-right corner).
* Click "Load Unpacked" and select the extension/ folder from this repo.

How It Works:
* Open a YouTube video and click on the extension.
* The summarizer extracts key points from the transcript.
* Users can chat with the AI chatbot to ask questions about the video content.
* The extension supports multiple languages for better accessibility.
* Conversations are saved in localStorage for a seamless experience.

Challenges & Solutions:
* Fetching accurate multi-language transcripts → Optimized youtube-transcript-api for improved handling.
* Ensuring chatbot accuracy → Tuned Gemini API responses for video-related queries.
* Managing chat history storage → Implemented localStorage for seamless user experience.

Next Steps & Improvements:
* Transcription from Audio – If a video has no transcript, generate one from audio.
* Enhanced AI Responses – Improve chatbot accuracy with better NLP models.
* Better UX/UI Enhancements – Optimize UI for a smoother experience.

License:
This project is licensed under the MIT License – feel free to contribute and improve it!








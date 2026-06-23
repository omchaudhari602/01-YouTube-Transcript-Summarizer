# -YouTube-Transcript-Summarizer
An AI-powered web application that extracts transcripts from YouTube videos and generates concise, meaningful summaries using Large Language Models (LLMs). This tool helps users quickly understand video content without watching the entire video.

🚀 Features
🔗 Paste any YouTube video URL
📜 Automatically fetch video transcripts
🤖 Generate AI-powered summaries
⚡ Fast and user-friendly interface
🌐 Supports publicly available YouTube transcripts
📱 Responsive design for desktop and mobile devices
🛠️ Tech Stack
Frontend
HTML5
CSS3
JavaScript
Backend
Python
Flask
AI & APIs
YouTube Transcript API
Google Gemini / OpenAI API (depending on implementation)
📂 Project Structure
01-YouTube-Transcript-Summarizer/
│
├── static/
│   ├── css/
│   ├── js/
│
├── templates/
│   └── index.html
│
├── app.py
├── requirements.txt
├── README.md
└── .env
⚙️ Installation
1. Clone the Repository
git clone https://github.com/omchaudhari602/01-YouTube-Transcript-Summarizer.git

cd 01-YouTube-Transcript-Summarizer
2. Create Virtual Environment
python -m venv venv

Activate Environment:

Windows

venv\Scripts\activate

Linux/Mac

source venv/bin/activate
3. Install Dependencies
pip install -r requirements.txt
4. Configure API Key

Create a .env file:

GOOGLE_API_KEY=your_api_key_here
5. Run Application
python app.py

Open:

http://127.0.0.1:5000
🎯 How It Works
User enters a YouTube URL.
Application extracts the Video ID.
Transcript is fetched using YouTube Transcript API.
Transcript is sent to an LLM for processing.
AI generates a structured summary.
Summary is displayed to the user.

This workflow enables quick knowledge extraction from long videos.

📸 Screenshots
Home Page
[ Add Screenshot Here ]
Generated Summary
[ Add Screenshot Here ]
🔮 Future Enhancements
Multi-language summaries
PDF export functionality
Summary length customization
Timestamp-based key insights
Video metadata extraction
User authentication and history
🤝 Contributing

Contributions are welcome!

Fork the repository
Create a new branch
git checkout -b feature-name
Commit changes
git commit -m "Added new feature"
Push to branch
git push origin feature-name
Create a Pull Request

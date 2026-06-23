# 🎥 YouTube Transcript Summarizer

An AI-powered web application that extracts transcripts from YouTube videos and generates concise, meaningful summaries using Large Language Models (LLMs). This tool helps users quickly understand video content without watching the entire video.

## 🚀 Features

- 🔗 Paste any YouTube video URL
- 📜 Automatically fetch video transcripts
- 🤖 Generate AI-powered summaries
- ⚡ Fast and user-friendly interface
- 🌐 Supports publicly available YouTube transcripts
- 📱 Responsive design for desktop and mobile devices

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- Flask

### AI & APIs
- YouTube Transcript API
- Google Gemini API

## 📂 Project Structure

```bash
01-YouTube-Transcript-Summarizer/
│
├── static/
│   ├── css/
│   └── js/
│
├── templates/
│   └── index.html
│
├── app.py
├── requirements.txt
├── README.md
└── .env
```

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/omchaudhari602/01-YouTube-Transcript-Summarizer.git
cd 01-YouTube-Transcript-Summarizer
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure API Key

Create a `.env` file in the root directory:

```env
GOOGLE_API_KEY=your_api_key_here
```

### 5. Run the Application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

## 🎯 How It Works

1. Enter a YouTube video URL.
2. Extract the video transcript using YouTube Transcript API.
3. Send the transcript to Google Gemini.
4. Generate an AI-powered summary.
5. Display the summarized content to the user.

## 📸 Screenshots

### Home Page

> Add screenshot here

### Summary Output

> Add screenshot here

## 🔮 Future Enhancements

- Multi-language transcript support
- Download summary as PDF
- Timestamp-based summaries
- Summary length customization
- Video metadata extraction
- User authentication and history tracking

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Open a Pull Request

## 👨‍💻 Author

### Om Chaudhari

- GitHub: https://github.com/omchaudhari602



---

⭐ If you found this project useful, please give it a star on GitHub!

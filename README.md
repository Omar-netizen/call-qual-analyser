
# AI-Powered Sales Call Analyzer

A fast, AI-based system that processes sales and customer calls, transcribes audio, identifies speakers, calculates conversation metrics, and generates actionable insights.

---

## 🏆 Features

- **Audio Download**: Supports downloading audio from YouTube links using `yt_dlp`.
- **Audio Processing**: Converts audio to a format suitable for speech recognition using `librosa`.
- **Speech-to-Text Transcription**: Uses OpenAI's `Whisper` model for fast and accurate transcription.
- **Speaker Identification**: Distinguishes between sales representatives and customers.
- **Metrics Calculation**: Calculates talk-time ratios, questions asked, longest monologue, and sentiment analysis.
- **Actionable Insights**: Generates quick insights such as payment confirmations or positive outcomes.
- **Optimized for Speed**: Fast processing and transcription using lightweight models.

---

## 💻 Tech Stack

- **Python 3.x**
- **yt_dlp** – For audio download from YouTube  
- **librosa** – Audio processing  
- **OpenAI Whisper** – Speech-to-text transcription  
- **FFmpeg** – Audio format conversion  
- **Jupyter Notebook / Google Colab** – Development and demonstration  

---

## 📂 Project Structure


sales-call-analyzer/
├── clean_notebook.ipynb # Step-by-step notebook with explanations
├── main.py # Clean Python script for running analysis
├── README.md # Project description (this file)
└── requirements.txt # Python dependencies


---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
Install dependencies:
pip install -r requirements.txt
Run the script:
python main.py
Or open clean_notebook.ipynb in Jupyter/Colab to run step-by-step.
📊 Output

The system provides:

Talk-time ratios for each speaker
Number of questions asked
Longest monologue duration
Call sentiment (positive/neutral)
Actionable insights
Identification of sales rep and customer

Example:

Talk-time ratio: 53.8% / 46.2%
Questions asked: 2
Longest monologue: 11.3 seconds
Call sentiment: POSITIVE
Actionable insight: 😊 Positive outcome! Customer provided payment details.
Sales Rep: Speaker_A, Customer: Speaker_B
🌟 Why This Project

This project demonstrates:

AI/ML integration in real-world sales analytics
Audio processing and speech recognition skills
Practical Python development and GitHub best practices
Ability to handle large notebooks, clean metadata, and optimize code for speed
📌 Notes
Original project was developed in Google Colab.
The .ipynb is cleaned of outputs and widget metadata for GitHub rendering.
main.py provides a production-ready, runnable version of the project.

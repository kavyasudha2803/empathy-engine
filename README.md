# 🎤 Empathy Engine

## 📌 Project Description

The Empathy Engine is an AI-powered customer interaction system that detects the emotional tone of user input and generates an appropriate voice response.

It enhances user experience by making AI responses more natural, empathetic, and expressive. The system combines transformer-based emotion detection with sentiment analysis and dynamically modulates speech parameters such as rate and volume to reflect the detected emotion.

---

## 🚀 Features

- Transformer-based emotion detection
- Hybrid emotion classification (model + sentiment analysis)
- Multi-class emotions:
  - Happy
  - Frustrated
  - Sad
  - Concerned
  - Surprised
  - Neutral
- Customer-service style responses
- Dynamic voice modulation:
  - Speech Rate
  - Volume
- Intensity scaling based on confidence score
- Web interface using Flask
- Audio output generation (.mp3)

---

## ⚙️ Tech Stack

- Python
- Flask
- Transformers (Hugging Face)
- TextBlob (Sentiment analysis)
- pyttsx3 (Text-to-Speech)

---

## 📦 Project Files

> Note: The project is uploaded as a ZIP file. Please extract it before running.

After extraction, the folder structure will be:
# 🎤 Empathy Engine

## 📌 Project Description

The Empathy Engine is an AI-powered customer interaction system that detects the emotional tone of user input and generates an appropriate voice response.

It enhances user experience by making AI responses more natural, empathetic, and expressive. The system combines transformer-based emotion detection with sentiment analysis and dynamically modulates speech parameters such as rate and volume to reflect the detected emotion.

---

## 🚀 Features

- Transformer-based emotion detection
- Hybrid emotion classification (model + sentiment analysis)
- Multi-class emotions:
  - Happy
  - Frustrated
  - Sad
  - Concerned
  - Surprised
  - Neutral
- Customer-service style responses
- Dynamic voice modulation:
  - Speech Rate
  - Volume
- Intensity scaling based on confidence score
- Web interface using Flask
- Audio output generation (.mp3)

---

## ⚙️ Tech Stack

- Python
- Flask
- Transformers (Hugging Face)
- TextBlob (Sentiment analysis)
- pyttsx3 (Text-to-Speech)

---

## 📦 Project Files

> Note: The project is uploaded as a ZIP file. Please extract it before running.

After extraction, the folder structure will be:
project/
│── app.py
│── templates/
│ └── index.html
│── static/
│ └── output.mp3
│── requirements.txt


---

## 🛠️ Setup and Run Instructions

### Step 1: Extract the ZIP File

Extract the downloaded ZIP file to a folder on your system.

---

### Step 2: Open Terminal in Project Folder

Navigate to the extracted folder:

```bash
cd empathy-engine
```
pip install -r requirements.txt

python -m textblob.download_corpora
RUN
python base.py

open browser 
http://127.0.0.1:5000

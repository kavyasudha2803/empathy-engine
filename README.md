# Empathy Engine

## Project Description

The Empathy Engine is an AI-powered customer interaction system that detects the emotional tone of user input and generates an appropriate voice response.

It enhances user experience by making AI responses more natural, empathetic, and expressive. The system combines transformer-based emotion detection with sentiment analysis and dynamically modulates speech parameters such as rate and volume to reflect the detected emotion.

---

##  Features

- Transformer-based emotion detection
- Hybrid emotion classification (model + sentiment analysis)
- Multi-class emotion detection:
  - Happy
  - Frustrated
  - Sad
  - Concerned
  - Surprised
  - Neutral
- Customer-service oriented conversational responses
- Dynamic voice modulation:
  - Speech Rate
  - Volume
- Intensity scaling based on confidence score
- Web interface using Flask
- Audio output generation (.mp3)

---

##  Tech Stack

- Python
- Flask (Web framework)
- Transformers (Hugging Face)
- TextBlob (Sentiment analysis)
- pyttsx3 (Text-to-Speech)

---

##  Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/empathy-engine.git
cd empathy-engine


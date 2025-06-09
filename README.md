# 📩 Gmail Scam Filter Detection

An AI-powered email filtering system that classifies scam and phishing emails using NLP and machine learning techniques. Integrated with the Gmail API for real-time inbox scanning and threat detection.

## 🔍 Overview

This project leverages **Natural Language Processing (NLP)** and **supervised learning models** (Naive Bayes, LSTM) to identify scam emails based on content, structure, and metadata. The model connects to a user's Gmail inbox and flags suspicious messages in real time.

## 🛠️ Tech Stack

- **Languages:** Python  
- **Libraries:** scikit-learn, TensorFlow, Keras, nltk, spaCy  
- **API Integration:** Gmail API (OAuth2.0)  
- **ML Models:** Naive Bayes, LSTM  
- **Deployment (optional):** Streamlit / Flask (for UI)

## 💡 Features

- Connects securely to Gmail using OAuth2.0
- Extracts and pre-processes email content using NLP techniques
- Classifies emails as "Scam" or "Safe"
- Visualizes prediction confidence
- Can be extended to alert or auto-flag emails

## 📁 Use Cases

- Real-time inbox threat detection  
- Educational tool for phishing awareness  
- Prototype for integrating AI with email platforms

## 🚀 How to Run

1. Clone the repo  
2. Set up Gmail API & download `credentials.json`  
3. Install dependencies with `pip install -r requirements.txt`  
4. Run the model: `python scam_filter.py`

> ⚠️ For privacy: Uses OAuth2.0 token flow and accesses inbox in read-only mode.

## 🧠 Future Enhancements

- Model improvement with transformer-based embeddings (BERT)  
- UI dashboard using Streamlit  
- Real-time notifications & Gmail tagging

## 📬 Contact

Created by [Farheen Shaikh](https://www.linkedin.com/in/farheen-shaikh0509)  
Email: f_shaikh1@u.pacific.edu / farheen.s.shaikh05@gmail.com


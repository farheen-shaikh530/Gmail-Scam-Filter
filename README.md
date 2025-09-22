#  Gmail Scam Filter Detection

An academic research project focused on designing and implementing reinforcement learning (RL) algorithms in simulated environments such as OpenAI Gym and PyBullet. The project emphasizes algorithm development, result analysis, and academic deliverables including documentation, presentations, and research papers.

## Overview

This project explores reinforcement learning techniques to solve control, robotics, and decision-making problems in simulation.
Key aspects of the project include:
	•	Implementing and testing RL algorithms (e.g., Q-learning, Deep Q-Networks, Policy Gradient methods).
	•	Running experiments in OpenAI Gym and PyBullet environments.
	•	Collecting and analyzing results to evaluate performance.
	•	Preparing technical documentation, research notes, and visualizations.
	•	Supporting faculty-led academic research through weekly progress reviews.

## Tech Stack

- **Languages:** Python  
- **Libraries & Framework:** scikit-learn, TensorFlow, Keras, nltk, spaCy , PyTorch / TensorFlow, NumPy, Matplotlib, OpenAI Gym, PyBullet 
- **API Integration:** Gmail API (OAuth2.0)  
- **ML Models:** Naive Bayes, LSTM  
- **Deployment:** Streamlit / Flask (for UI)
  

## Responsibilities
- Design and implement reinforcement learning algorithms in simulation environments.
- Analyze experimental results and create detailed documentation.
- Assist in preparing research presentations and academic papers.
- Meet weekly with faculty supervisors to report progress and troubleshoot challenges.


## Features

- Connects securely to Gmail using OAuth2.0
- Extracts and pre-processes email content using NLP techniques
- Classifies emails as "Scam" or "Safe"
- Visualizes prediction confidence
- Can be extended to alert or auto-flag emails

## 📁 Use Cases

- Real-time inbox threat detection  
- Educational tool for phishing awareness  
- Prototype for integrating AI with email platforms

##  How to Run

1. Clone the repo  
2. Set up Gmail API & download `credentials.json`  
3. Install dependencies with `pip install -r requirements.txt`  
4. Run the model: `python scam_filter.py`

> For privacy: Uses OAuth2.0 token flow and accesses inbox in read-only mode.

## Future Enhancements

- Model improvement with transformer-based embeddings (BERT)  
- UI dashboard using Streamlit  
- Real-time notifications & Gmail tagging

##  Contact

Created by [Farheen Shaikh](https://www.linkedin.com/in/farheen-shaikh0509)  
Email: f_shaikh1@u.pacific.edu / farheen.s.shaikh05@gmail.com


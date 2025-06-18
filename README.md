# Real-Time Multilingual Scam Call Detection System

This project presents a real-time system for detecting scam phone calls using machine learning and natural language processing techniques. The system is capable of transcribing multilingual audio and classifying calls as either **scam** or **genuine** in real time. It combines speech-to-text transcription, text preprocessing, and predictive modeling to provide a comprehensive solution for scam detection.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage Instructions](#usage-instructions)
- [Sample Workflow](#sample-workflow)
- [Future Enhancements](#future-enhancements)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

Overview

With the rising threat of scam calls globally, this project aims to develop a scalable and intelligent scam detection system. The pipeline captures real-time audio, transcribes it using a speech recognition model (e.g., OpenAI Whisper), preprocesses the transcribed text, and classifies it using a trained machine learning model.

---

## Features

- Real-time audio input and processing
- Multilingual speech-to-text transcription
- Automated scam/genuine classification using NLP
- Scam keyword extraction and visualization via word clouds
- Modular, extensible codebase suitable for future deployments

---

## Project Structure

text
ScamDetection/
│
├── ScamDetection.ipynb       # Jupyter Notebook containing the full workflow
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
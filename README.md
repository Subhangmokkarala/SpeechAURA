# AuraSpeech: Sentiment Analysis Web App with Audio Input

AuraSpeech is a sentiment analysis web application that analyzes emotions expressed in audio recordings using Mel Frequency Components (MFCs). The project integrates machine learning models for sentiment analysis, audio processing techniques, and web development for a comprehensive solution.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
AuraSpeech combines text and audio inputs to provide real-time sentiment analysis. It captures emotional cues and nuances in speech patterns using MFCs extracted from audio recordings. The web application offers an intuitive interface for users to input text or record audio for sentiment analysis.

## Features
- Multi-modal sentiment analysis using text and audio inputs.
- Mel Frequency Components (MFCs) extraction for audio processing.
- Real-time analysis and instant feedback on emotions expressed.
- User-friendly web interface with text input and audio recording capabilities.
- Dockerized deployment for easy setup and scalability.
- CI/CD pipeline for automated testing and deployment.

## Technologies Used
- Python: Flask, TensorFlow, Scikit-Learn, Librosa
- HTML/CSS/JavaScript: Bootstrap, jQuery
- Docker: Containerization and deployment
- GitHub Actions: CI/CD pipeline
- Prometheus/Grafana: Monitoring and analytics

## Project Structure
```python
AuraSpeech/
│
├── app/
│   ├── static/
│   │   ├── css/
│   │   └── js/
│   ├── templates/
│   ├── audio_processing.py
│   ├── model.py
│   ├── routes.py
│   └── app.py
│
├── data/
│   ├── audio_samples/
│   └── models/
│
├── docs/
│   └── README.md
│
├── tests/
│   ├── unit_tests/
│   └── integration_tests/
│
├── .github/
│   └── workflows/
│       └── ci-cd.yaml
│
├── Dockerfile
├── docker-compose.yml
├── requirements.txt
├── LICENSE
└── README.md

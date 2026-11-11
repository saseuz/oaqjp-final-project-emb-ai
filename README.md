# Final project

An Emotion Detection web application developed using the Watson NLP library and Flask as part of the IBM AI Developer Professional Certificate / Embeddable AI course.

## Overview

This project implements an end-to-end emotion detection system. It extracts emotions from user-provided text using Watson NLP's emotion prediction models, processes the scores (anger, disgust, fear, joy, sadness), identifies the dominant emotion, and serves the results through a Flask-based web interface and REST API.

---

## Features

- **Watson NLP Integration:** Leverages Watson NLP emotion analysis endpoints/models.
- **Flask REST API:** Exposes endpoints to process text and return structured emotion scores.
- **Dominant Emotion Detection:** Evaluates and highlights the highest-scoring emotional tone.
- **Error Handling:** Robust handling for blank input or server errors (HTTP 400 / 500).
- **Unit Testing:** Comprehensive test suite validating output across various emotional expressions.
- **Web UI:** Interactive front-end for real-time user testing.

---

## Project Structure

```text
final_project/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── static/
│   └── mywebscript.js
├── templates/
│   └── index.html
├── test_emotion_detection.py
├── server.py
└── README.md

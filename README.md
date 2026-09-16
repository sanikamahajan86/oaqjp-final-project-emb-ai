# Emotion Detector

Final project for the IBM/Coursera Python and Flask assignment. The application sends text to the IBM Watson NLP emotion endpoint and returns scores for **anger, disgust, fear, joy, and sadness**, together with the dominant emotion.

## Project structure

```text
Emotion-Detector/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── static/
│   └── mywebscript.js
├── templates/
│   └── index.html
├── submission_evidence/
│   └── README.md
├── server.py
├── test_emotion_detection.py
├── requirements.txt
├── .gitignore
└── README.md
```

## Setup

```bash
python -m venv .venv
```

Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

macOS/Linux:

```bash
source .venv/bin/activate
```

Install dependencies:

```bash
python -m pip install -r requirements.txt
```

## Test the package

```bash
python -c "from EmotionDetection import emotion_detector; print(emotion_detector('I love this new technology'))"
```

## Run unit tests

```bash
python -m unittest test_emotion_detection.py -v
```

## Run the Flask application

```bash
python server.py
```

Then open:

```text
http://127.0.0.1:5000
```

## Run static code analysis

```bash
pylint server.py
```

For the assignment, save/capture the required terminal outputs and screenshots listed in `submission_evidence/README.md`.

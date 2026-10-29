# Final Project

## Emotion Detector

Final project for the IBM/Coursera Python and Flask assignment. This application analyzes text and returns emotion scores for anger, disgust, fear, joy, and sadness, along with the dominant emotion.

## Project Structure

- `EmotionDetection/` — Emotion detection Python package.
- `EmotionDetection/__init__.py` — Package initialization.
- `EmotionDetection/emotion_detection.py` — Emotion detection function.
- `templates/index.html` — Web application interface.
- `static/mywebscript.js` — Frontend JavaScript.
- `server.py` — Flask web server.
- `test_emotion_detection.py` — Unit tests.
- `requirements.txt` — Python dependencies.

## Setup

Install the required dependencies:

```bash
python -m pip install -r requirements.txt
```

## Test the Package

```bash
python -c "from EmotionDetection import emotion_detector; print(emotion_detector('I love this new technology'))"
```

## Run Unit Tests

```bash
python -m unittest test_emotion_detection.py -v
```

## Run the Application

```bash
python server.py
```

Open the application at:

```text
http://127.0.0.1:5000
```

## Static Code Analysis

```bash
pylint server.py
```

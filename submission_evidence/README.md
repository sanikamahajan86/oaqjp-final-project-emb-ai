# Assignment Evidence Checklist

Use this folder for the screenshots requested by the Coursera rubric.

## Task 1 — Repository
- Public GitHub repository URL to `README.md`.

## Task 2 — Emotion detection application
- Code from `EmotionDetection/emotion_detection.py` showing `emotion_detector`.
- Terminal output showing the function imports and runs without errors.

Suggested command:
```bash
python -c "from EmotionDetection import emotion_detector; print(emotion_detector('I love this new technology'))"
```

## Task 3 — Output formatting
- Code from `EmotionDetection/emotion_detection.py` showing the formatted dictionary.
- Terminal output showing anger, disgust, fear, joy, sadness, and dominant_emotion.

## Task 4 — Package validation
- Public GitHub URL to `EmotionDetection/__init__.py`.
- Terminal output proving the package imports correctly.

Suggested command:
```bash
python -c "from EmotionDetection import emotion_detector; print('EmotionDetection package imported successfully')"
```

## Task 5 — Unit tests
- Code from `test_emotion_detection.py`.
- Terminal output showing all tests passed.

Suggested command:
```bash
python -m unittest test_emotion_detection.py -v
```

## Task 6 — Flask deployment
- Code from `server.py`.
- Save browser screenshot as `6b_deployment_test.png` after testing a valid sentence.

## Task 7 — Error handling
- Code from `EmotionDetection/emotion_detection.py` showing HTTP 400 handling.
- Code from `server.py` showing blank-input handling.
- Leave the input empty, click the button, and save the browser screenshot as `7c_error_handling_interface.png`.

## Task 8 — Static code analysis
- Code from `server.py`.
- Terminal output showing the Pylint score.

Suggested command:
```bash
pylint server.py
```

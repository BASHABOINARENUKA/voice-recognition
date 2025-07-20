🗂️ How It Works
Data Upload:

Upload .wav files for both enroll and test.

Naming format:
speakername_enroll_01.wav
speakername_test_01.wav

Feature Extraction:

Extracts MFCC (Mel Frequency Cepstral Coefficients) features from audio files.

Model Training:

Trains a machine learning model (e.g., RandomForestClassifier) on enrollment features.

Authentication:

Predicts the speaker of the test sample.

Displays predicted speaker, actual speaker, and probabilities.

Returns AUTHENTICATED or FAILED AUTHENTICATION.

📌 Sample Output
yaml
Copy
Edit
--- Test Sample 1: 'renu_test_01.wav' (True speaker: renu) ---
Predicted Speaker: renu
True Speaker: renu
Probabilities per speaker:
  ashu: 34.75%
  mamu: 46.14%
  renu: 19.11%
Status: AUTHENTICATED (Correctly identified)

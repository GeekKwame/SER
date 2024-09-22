# Speech Emotion Recognition (SER)

## Overview
This project aims to develop a model that can recognize emotions from audio recordings. The model processes .wav audio files, extracts relevant features, and classifies the emotions expressed in the speech.

## Features
- Preprocessing of audio files
- Extraction of Mel-frequency cepstral coefficients (MFCCs)
- Emotion classification using machine learning algorithms
- Streamlit app for real-time emotion recognition

## Usage
1. Data Preparation: Place your .wav audio files in the data/ directory.
2. Run the Preprocessing: Execute the preprocessing script to extract features:
       python preprocess.py
    3. Train the Model: Run the training script:
       python train.py
    4. Run the Streamlit App:
       streamlit run app.py
    
## Data
The dataset used for training can be found https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess. Ensure to follow the data usage policies and citation requirements.

## Model Training
The model is trained using  MFCC and LSTM on the extracted features. Training parameters can be adjusted in the speech_emotion_recognition.ipynb file.

## Results
Upon successful training, you can evaluate the model's performance. Metrics such as accuracy, precision, and recall are reported and deployed further on.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

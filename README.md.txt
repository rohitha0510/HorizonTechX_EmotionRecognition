# Emotion Recognition from Speech

## Project Overview

This project is developed as part of the Horizon TechX Machine Learning Internship Program.

The objective of this project is to build a machine learning model capable of recognizing human emotions from speech recordings. The system analyzes audio signals, extracts speech features, and predicts the emotional state of the speaker.

## Emotions Recognized

* Happy
* Sad
* Angry
* Neutral
* Fearful
* Calm
* Disgust
* Surprised

## Dataset

Dataset Used: RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)

The dataset contains speech recordings from multiple actors expressing different emotions.

## Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Librosa
* Scikit-learn
* Matplotlib
* Joblib

## Feature Extraction

The following audio features were extracted:

* MFCC (Mel-Frequency Cepstral Coefficients)
* Speech frequency characteristics
* Acoustic patterns

Each audio file was converted into a numerical feature vector for model training.

## Machine Learning Model

Algorithm Used:

* Random Forest Classifier

The model was trained using extracted MFCC features and emotion labels.

## Project Workflow

1. Load audio dataset
2. Extract MFCC features using Librosa
3. Encode emotion labels
4. Split dataset into training and testing sets
5. Train Random Forest Classifier
6. Evaluate model performance
7. Save trained model using Joblib

## Results

Evaluation Metrics:

* Accuracy Score
* Classification Report
* Precision
* Recall
* F1-Score

Model performance was evaluated on unseen test data.

## Project Structure

HorizonTechX_EmotionRecognition

├── dataset

├── notebooks

│   └── EmotionRecognition.ipynb

├── model

│   └── emotion_model.pkl

├── requirements.txt

└── README.md

## Future Improvements

* Implement CNN and LSTM models
* Improve emotion classification accuracy
* Deploy as a web application
* Real-time speech emotion detection

## Author

Machine Learning Internship Project

Horizon TechX Internship Program
# Emotion Detection System

## Overview
This project is a real-time emotion detection system using deep learning and computer vision. It uses a trained Keras model to recognize emotions from webcam images.

## Features
- Real-time face detection using OpenCV.
- Emotion classification into 7 categories: angry, disgust, fear, happy, neutral, sad, surprise.
- Pre-trained model (`emotiondetector.h5` and `emotiondetector.json`).

## Requirements
See `requirements.txt` for all dependencies. Main packages:
- tensorflow
- keras
- pandas
- numpy
- jupyter
- notebook
- tqdm
- opencv-contrib-python
- scikit-learn

## Usage
1. Clone the repository.
2. Install dependencies:
	```
	pip install -r requirements.txt
	```
3. Run the real-time detection script:
	```
	python realtimedetection.py
	```
4. The webcam will open and display the detected emotion above each face.

## Files
- `realtimedetection.py`: Main script for real-time emotion detection.
- `emotiondetector.h5` and `emotiondetector.json`: Pre-trained Keras model.
- `requirements.txt`: List of required Python packages.
- `.gitignore`: Ignores data folders like `Data/` and `archive (25)/`.

## Data
The training and test data are not included in the repository and are ignored by `.gitignore`.

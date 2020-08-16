# Speech-Analytics-SpeechToText
This repository tells you about the basics of Speech Processing, Feature Extraction, Pre Processing of a sound wave and how to create Sound Models on it with example of a SpeechToText model.

# Introduction to Speech Analytics :-
File :- audio_preprocessing_tutorial.ipynb 

Reference :- https://medium.com/@divalicious.priya/speech-analytics-part-1-basics-of-speech-analytics-37ba6d5904e2

Step 1: Reading your sound file

Step 2: File information and Visualization

Step 3: Resampling

Step 4: Complex Feature Extraction

-Spectogram

-MelSpectrum

-MFCC

Step 5: Normalize a Wave form to apply MuLaw encoding

Step 6: Pre-Processing

-Amplification

-Low pass/ High pass Filters

-Equalizing / Normalizing

-Dither

# Speech-To-Text Classifier
File :- BasicModelAudio.ipynb

Reference :- 

Dataset : Download it from https://www.kaggle.com/c/tensorflow-speech-recognition-challenge/data?select=train.7z

Step 1: Read Data from sub folders and create input data

Step 2: Sound Wave Pre-processing

Step 3: Create Model Archietecture (CNN + Bi Directional LSTM)

Step 4: Train Model

Step 6: Record Input from user and convert it to Text

# Requirements:
Torch

TorchAudio

Keras


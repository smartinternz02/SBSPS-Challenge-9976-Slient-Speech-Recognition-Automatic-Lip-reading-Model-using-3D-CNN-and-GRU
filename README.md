# SBSPS-Challenge-9976-Slient-Speech-Recognition-Automatic-Lip-reading-Model-using-3D-CNN-and-GRU
Slient Speech Recognition : Automatic Lip reading Model using 3D CNN and GRU
# Overview
The Silent Speech Recognition project aims to develop an advanced model for automatic lip reading using a combination of 3D Convolutional Neural Networks (CNN) and Gated Recurrent Units (GRU). Traditional speech recognition heavily relies on audio input, but this project focuses on extracting information solely from lip movements, enabling speech recognition in scenarios with no audible speech or in noisy environments.

# Motivation
Traditional speech recognition systems face challenges in noisy environments and situations where audible speech is not possible. Silent speech recognition, which relies on visual cues like lip movements, has the potential to address these challenges. This project aims to build an accurate and robust silent speech recognition system using deep learning techniques.

# Features
Utilizes 3D CNN to extract spatial features from lip images.
Uses GRU for sequence modeling and capturing temporal patterns.
End-to-end deep learning pipeline for silent speech recognition.
Easy-to-use interface for training and evaluation.

# Model Architecture
The silent speech recognition model consists of two main components:

3D CNN (Convolutional Neural Network): This part of the model extracts spatial features from sequences of lip images, focusing on the visual aspect of speech.

GRU (Gated Recurrent Unit): The extracted features from the CNN are then fed into a GRU, which captures the temporal patterns and dependencies in the lip movements.

The combination of these two components creates a powerful end-to-end system for silent speech recognition.

# Dataset
To train and evaluate the model, a suitable lip reading dataset is required. You can use publicly available datasets or create your own dataset by recording videos of various speakers in different scenarios. Each video should have corresponding transcriptions for training.

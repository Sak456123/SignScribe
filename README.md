# SignScribe
SignScribe : A Raspberry Pi 4B Based Sign Language Interpreter

# Overview

Welcome to the repository for SignScribe, a project dedicated to breaking down communication barriers for the deaf and hard-of-hearing community. This project leverages the Raspberry Pi 4B and a USB camera to develop a real-time Sign Language Interpreter. SignScribe utilizes a pose-based deep learning model designed to recognize 10 Indian Sign Language (ISL) gestures through the Mediapipe framework for pose estimation. Tested in real-time, the model demonstrates promising effectiveness in identifying continuous signs.

# Objectives

Our primary objective is to create a device that translates sign language gestures into text and speech, promoting inclusivity and accessibility. This project aligns with the United Nations Sustainable Development Goals (SDGs), specifically targeting SDG 4 (Quality Education) and SDG 10 (Reduced Inequalities).

# Features

Real-time Interpretation: Uses advanced image processing and machine learning algorithms to interpret sign language gestures.
Text and Speech Output: Converts interpreted gestures into text displayed on an LCD and vocalized through text-to-speech functionality.
User-Friendly Interface: Ensures accessibility for individuals with hearing or visual impairments and those unfamiliar with sign language.

# Implementation

1] Raspberry Pi Setup
Initial setup of Raspberry Pi 4B and installation of a suitable environment for code im
2] Modelling
Creation of a dataset for Indian sign language gestures.
Importing necessary libraries for data processing.
Specifying the path for storing images.
Designing the model structure, utilizing a pose-based deep learning model with LSTM for sequential data processing.
Training the model and evaluating its performance on test data, achieving an accuracy rate of 85-90%.
3] Testing
Importing required libraries for implementation of Mediapipe.
Implementation of pose estimation using Mediapipe for real-time gesture recognition.
Integration of the trained recognition model with the system.
4] User Interface
Installation of necessary libraries for I2C LCD interfacing.
Interfacing the LCD with Raspberry Pi to visually display text output.
Installation of necessary libraries for text-to-speech (TTS) functionality.
Writing code to convert text output into speech, enabling users to hear the interpreted signs through wired earphones connected to the audio jack.

# Required Libraries
OpenCV
Mediapipe
Matplotlib
Numpy
TensorFlow
sklearn

# Contributors
Flavia Saldanha
Yash Bhavnani
Samruddhi Patil
Sakshi Rathod

# Credits
This project includes code from Swaroop Srisailam's Continuous-Indian-Sign-Language-Recognition repository.

# Facial emotion recognition using deep learning

The aim of this project is to recognize seven basic emotional states (anger, disgust, fear, happiness, neutral, sadness, surprise) based on images of human facial expressions. The classification is performed using a convolutional neural network (CNN) on the FER-2013 dataset. We then implement our model in a graphical user interface (GUI) application that will access the webcam to recognize the user’s facial expression on the live feed before mapping it with a corresponding emoji that will finally be displayed on screen in real-time. 

## Original data

The data is available on Kaggle and can be downloaded at: https://www.kaggle.com/datasets/msambare/fer2013

## Data preprocessing

Data preprocessing.ipynb

## Model

CNN model.ipynb

Trained model used in the GUI application: best_model8.h5

## GUI application

gui.py

The emojis used for the mapping are in the folder emojis2

## Report

Vu Kim-Lan - Zucchinetti Emilie - CAS-ADS Final Project Report.pdf

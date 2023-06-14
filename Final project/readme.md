# Facial emotion recognition using deep learning

The aim of this project is to recognize seven basic emotional states (anger, disgust, fear, happiness, neutral, sadness, surprise) based on images of human facial expressions. The classification is performed using a convolutional neural network (CNN) on the FER-2013 dataset. We then implement our model in a graphical user interface (GUI) application that will access the webcam to recognize the user’s facial expression on the live feed before mapping it with a corresponding emoji that will finally be displayed on screen in real-time. 

## Original data

The data is available on Kaggle and can be downloaded at: https://www.kaggle.com/datasets/msambare/fer2013

The data consists of 35’887 (training set: 28'709, test set: 7'178) grayscale images of human faces, each with a resolution of 48x48 pixels. These images represent facial expressions of seven different emotions: anger, disgust, fear, happiness, neutral, sadness, surprise.  

## Data preprocessing

As the classes are unevenly distributed, we apply data augmentation on the training set to get a balanced dataset for the model training. The augmented dataset consists of 49'000 images, 7'000 in each class.

Data preprocessing.ipynb


## Model

We train a CNN model with the preprocessed data.

CNN model.ipynb

## GUI application

We build a GUI application using Tkinter and OpenCV. The purpose of the application is to detect faces in a video stream from the webcam, predict the emotions displayed by the detected faces using our loaded CNN model, and map the predicted emotions to corresponding emoji images. 

- gui.py
- Trained model used in the GUI application: best_model8.h5
- emojis2: the emojis used for the mapping

## Report

Vu Kim-Lan - Zucchinetti Emilie - CAS-ADS Final Project Report.pdf

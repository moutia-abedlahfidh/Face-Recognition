Face Recognition with FaceNet and Logistic Regression

This project implements a face recognition system using FaceNet embeddings and Logistic Regression  in Python. It detects faces from images, extracts 512-dimensional embeddings, trains a classifier to recognize a specific person , and can classify new images as either “you” or “someone else.”

Features

Face Detection: Uses OpenCV Haarcascade to detect faces in images.

Face Embeddings: Uses FaceNet
 to generate 512-dimensional embeddings for each detected face.

Classifier Training: Trains a Logistic Regression model on your photos vs. others’ photos.

Testing: Predicts whether a new image contains your face or someone else’s, and shows bounding boxes with confidence scores.

Dataset Structure:

dataset/
  me/        # Your photos
  others/    # Other people’s photos
  test/      # Test images

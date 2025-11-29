# Predicting Handwritten Digits Using CNN

## Overview
This repository contains a Jupyter notebook for training and evaluating a Convolutional Neural Network (CNN) to classify traffic sign images using the German Traffic Sign Recognition Benchmark (GTSRB) dataset. The goal is to build a multi-class image classifier capable of recognizing a variety of road-sign classes under variable real-world conditions (lighting, sign orientation, background clutter, etc.).

The model demonstrates how to prepare data, build a CNN, and evaluate performance on the standard GTSRB test set.

## Dataset
GTSRB consists of more than 50,000 images arranged in 42 classes (traffic signs), which allows you to create a multiclass classification problem. 

## Metrics
The model achieved 99.21% accuracy on the validation set (random 20% subset of the training dataset).

## Requirements
- Python 3+
- Jupyter Notebook
- NumPy, Keras, TensorFlow
- GPU is helpful

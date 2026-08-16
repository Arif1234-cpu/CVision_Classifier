# MobileNetV2 Computer Vision Classifier

A desktop-based computer vision application that uses a pre-trained MobileNetV2 model to classify images and display the Top-3 predictions with confidence scores through a Tkinter GUI.

## Features

- Pre-trained MobileNetV2 for image classification
- Supports local image files
- Automatic image preprocessing
- Resizes images to 224 × 224
- Converts images into NumPy arrays
- Normalizes image data before inference
- Displays Top-3 predicted classes with confidence scores
- Simple desktop GUI using Tkinter

## Tech Stack

- Python
- TensorFlow / Keras
- MobileNetV2
- NumPy
- PIL (Pillow)
- Tkinter

## How It Works

```text
Select Image
     ↓
Load Image using PIL
     ↓
Resize to 224 × 224
     ↓
Convert to NumPy Array
     ↓
Preprocess Image
     ↓
MobileNetV2 Inference
     ↓
Get Prediction Probabilities
     ↓
Select Top-3 Predictions
     ↓
Display Results in Tkinter GUI


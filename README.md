# Face Recognition System

## 📌 Introduction
This is a simple face recognition system built using Python and OpenCV. The project allows users to detect, recognize, and classify faces from images and real-time video streams. It is designed for ease of use and can be customized for various applications such as attendance systems, security authentication, and more.

## 📂 Project Structure
```
Face-Recognition/
│-- data/                  # Directory for storing training and test images
│-- models/                # Directory for trained models
│-- face_recognition.py    # Main script for face recognition
│-- train_model.py         # Script for training the face recognition model
│-- utils.py               # Helper functions for image processing and model operations
│-- requirements.txt       # List of required Python dependencies
│-- README.md              # Project documentation
```

## 🛠️ Installation
To get started, follow these steps:

1. **Clone the repository:**
   ```sh
   git clone https://github.com/peekayitachi/Face-Recognition.git
   cd Face-Recognition
   ```

2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

3. **Ensure you have OpenCV installed:**
   ```sh
   pip install opencv-python
   ```

## 🚀 Usage
### Train the Model
To train the model with your dataset, run:
```sh
python train_model.py
```
Ensure that the `data/` directory contains labeled images before training.

### Perform Face Recognition
To detect and recognize faces in an image or video stream, run:
```sh
python face_recognition.py
```
This script will process the input and identify known faces.

## Features
✔ Face detection and recognition using OpenCV and dlib  
✔ Customizable dataset for training  
✔ Real-time recognition using webcam  
✔ Model storage for efficient processing  




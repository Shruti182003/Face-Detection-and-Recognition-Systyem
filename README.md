Face Detection and Recognition System

This project detects faces from a webcam/IP camera stream, collects training data, trains a CNN model, and recognizes faces in real-time.

Features
- Data collection from IP camera/webcam
- Face detection using Haar Cascade
- Model training with CNN (LeNet architecture)
- Real-time face recognition

Files
- `collect_data.py`: Capture face images for training
- `consolidated_data.py`: Process and label collected images
- `face_detection.py`: Train CNN model for face recognition
- `recognize.py`: Run real-time recognition
- `haarcascade_frontalface_default.xml`: Haar cascade model
- `final_model.h5`: Trained model file

How to Run
1. Install dependencies:
   ```bash
   pip install -r Requirements.txt

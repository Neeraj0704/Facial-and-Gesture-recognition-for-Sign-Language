# **Facial and Gesture Recognition System**

## **Overview**

This project aims to create a real-time system that can simultaneously recognize facial expressions and sign language gestures. It leverages advanced deep learning models—EfficientNet for facial recognition and YOLOv5 for sign language detection—integrated within a single Python application. The system is designed to enhance human-computer interaction by interpreting emotions and gestures in real time.

## **Features**

- **Facial Expression Recognition**: 
  - Detects and classifies facial expressions using the EfficientNet model.
  - Real-time processing of facial data captured through a webcam.
  - Supports multiple emotion categories, depending on the trained model.
  
- **Sign Language Gesture Recognition**:
  - Recognizes various sign language gestures using the YOLOv5 model.
  - Processes video input in real time to identify specific gestures.
  - Customizable for different sets of gestures based on your dataset.

- **Integrated System**:
  - Combines facial expression and sign language recognition in a unified script.
  - Real-time annotations and feedback displayed on the video stream.

## **Installation**

### **1. Clone the Repository**

```bash
git clone https://github.com/yourusername/facial-gesture-recognition.git
cd facial-gesture-recognition

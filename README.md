# Facial Emotion Recognition with Deep Learning

This project is a deep learning-based system for real-time facial emotion recognition. It detects and classifies emotions from facial expressions, offering valuable insights for applications in human-computer interaction, mental health monitoring, and user sentiment analysis.

## Problem Statement

Understanding emotions through facial expressions enhances human-computer interactions, making technology more responsive to user emotions. This project addresses this by providing an automated solution to detect emotions in real-time, which is beneficial in fields like:

- **Mental Health Monitoring**: Detect emotional cues that could indicate distress or other mental health issues.
- **Customer Sentiment Analysis**: Understand user feedback through facial expressions, valuable for market research and user experience testing.
- **Enhanced Human-Computer Interaction**: Improve responsiveness in virtual assistants, chatbots, and other interfaces by recognizing users' emotional states.

## How It Works

The project contains two main scripts:

1. **Model Training (`train.py`)**: This script trains a deep learning model on a labeled dataset of facial images to classify various emotions. The model learns from distinct facial expressions, improving its generalization to accurately identify real-world emotions.
  
2. **Real-Time Detection (`test.py`)**: This script uses the camera to detect faces in real time, applying a pre-trained model to classify the emotion displayed. It uses the `haarcascade.xml` file for face detection and displays the recognized emotion directly on the screen.

3. **Advanced Segmentation with K-means Clustering**: The project also explores using K-means clustering for facial region segmentation. This approach enhances emotion recognition accuracy by focusing on specific facial features.

## Key Features

- **Real-Time Emotion Detection**: Classifies emotions in live video feeds.
- **Accurate Facial Region Segmentation**: Uses K-means clustering to isolate facial features, enhancing model performance.
- **Multiple Applications**: Useful in fields ranging from mental health to customer experience analysis.

## Getting Started

### Prerequisites

Make sure you have Python installed along with the following libraries:

```bash
pip install -r requirements.txt

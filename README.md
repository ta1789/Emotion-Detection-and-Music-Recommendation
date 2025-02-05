# Emotion Detection and Music Recommendation System

This project provides a **Facial Emotion Detection** system combined with a **Song Recommendation** feature. The system captures the user's facial image, detects the mood using a **Convolutional Neural Network (CNN)** model, and classifies the mood into one of seven categories: Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise. In addition, the system supports **Speech Recognition** to interact with the user using voice input. Based on the detected mood, the system recommends appropriate songs.

## Features

- **Facial Emotion Detection**: Captures the user's face and detects their emotion based on facial expressions.
- **Voice Interaction**: Allows users to interact with the system through voice commands.
- **Song Recommendation**: Recommends music based on the user's emotional state.
- **Mood Classification**: Classifies the mood into one of the following categories:
  - Angry
  - Disgust
  - Fear
  - Happy
  - Neutral
  - Sad
  - Surprise

## Tech Stack

- **Programming Language**: Python
- **Libraries**:
  - **numpy**: Numerical operations and handling arrays.
  - **pandas**: Data manipulation and analysis.
  - **keras**: Building and training deep learning models (CNN).
  - **opencv (cv2)**: Image processing and facial detection.
  - **tensorflow**: For model building and training.
  - **pyttsx3**: Text-to-speech engine for voice interactions.
  - **speech_recognition**: To process voice commands.
- **Models Used**:
  - **CNN Sequential Model**: A Convolutional Neural Network for emotion detection.
  - **ResNet50**: A deep residual network used for improving the accuracy of emotion recognition.

## Dataset

The system is trained using the **FER-2013** dataset, available on Kaggle. The dataset contains around **48x48 pixel grayscale images** categorized into seven emotions: Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise.

- **Dataset Link**: [FER-2013 Dataset on Kaggle](https://www.kaggle.com/datasets/msambare/fer2013)
- **Dataset Features**:
  - Images are of size **48x48 pixels**.
  - Seven emotion categories: Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise.
  
## Installation

### Prerequisites

Before running the application, ensure you have Python 3.x installed. You will also need to install the necessary libraries and dependencies.

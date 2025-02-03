# Emotion-Detection-and-Music-Recommendation
Facial Emotion Detection and Song Recommendation system first captures picture of your face and using CNN model trained with around 20,000 datasets of 48 by pixels 
detect the mood of the user using CNN Model along with Support Vector Machine for classification.The mood of the user will be classified into 7 categories namely
angry,disgust,fear,happy,neutral,sad,surprise.The system also has speech recognition system if the user wants to interact with the systej using voice instead of 
facial image.
Libraries used are numpy,kera,pandas,cv2,tensorflow,pyttsx3,speech_recognition

# Dataset
The Dataset used were FER Datatset from Kaggle.Dataset Link- [https://www.kaggle.com/datasets/msambare/fer2013](https://www.kaggle.com/datasets/msambare/fer2013). 
The dataset set contains 48 X 48 pixel greyscale images of five emotions angry,disgust,fear,happy,neutral,sad,surprise.

# Models Used for Image Emotion Prediction
1)CNN Sequential Model 
2)Resnet50

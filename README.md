# Speech Emotion Recognition using Librosa 🎙️💬

## Table of Contents  
- [Introduction](#introduction)  
- [Features](#features)  
- [Installation](#installation)    
- [Dataset](#dataset)  
- [Model](#model)  
- [Results](#results)  
- [Contributing](#contributing)  
- [License](#license)  
- [Acknowledgements](#acknowledgements)  

## Introduction  
This project aims to classify emotions from speech signals using machine learning techniques. We use the **Librosa** library for audio feature extraction and an **MLP Classifier** for emotion recognition. Based on the tone and features extracted from the voice, the system classifies the emotion and outputs a corresponding emoji to represent the detected emotion.

## Features  
- 🎧 **Feature Extraction**: Extracts features from audio signals using Librosa.  
- 🤖 **MLP Classifier**: Classifies emotions based on the extracted audio features using an MLP classifier.  
- 😃 **Emoji-based Results**: Displays the detected emotion as an emoji, such as 😊 for happiness, 😞 for sadness, or 😠 for anger.  
- 📝 **Training and Evaluation**: Provides scripts for training and evaluating models.  
- 🚀 **Pre-Trained Models**: Includes pre-trained models for quick testing.

## Installation  
To set up the project on your local machine, follow these steps:
1. Clone the repository:
   Using VSC
   git clone https://github.com/your-username/speech-emotion-recognition-librosa.git
   
## Dataset
The dataset used for training and evaluation consists of speech samples labeled with emotional states. Popular datasets for emotion recognition in speech, such as RAVDESS or TESS, can be used. Please ensure that the dataset is in the correct format and accessible in the project directory.

## Model
The project uses an MLP Classifier (Multi-Layer Perceptron) for emotion recognition.
⚙️ MLP Classifier: A neural network-based classifier used for identifying emotions from the extracted features of the audio signal.
Pre-trained models are provided for quick testing and evaluation.

## Results
📊 The system classifies emotions and provides results in the form of emojis. Based on the detected emotion, the system will output an emoji that corresponds to the emotional state, such as:

- 😊 Happiness
- 😞 Sadness
- 😠 Anger
- 😱 Fear
- 😮 Surprise
- 😐 Neutral

## Contributing
If you'd like to contribute to this project, feel free to fork the repository, make changes, and create a pull request. Please make sure to follow the coding guidelines and include proper documentation for any new features or changes. 🙌

## License
This project is licensed under the Free To Use License. 📜

## Acknowledgements
- 🎶 Librosa: For audio feature extraction.
- 🤖 Scikit-learn: For the MLP Classifier and other machine learning algorithms.
- 🧠 TensorFlow/Keras: For deep learning models (if used).
- 🎤 RAVDESS/TESS: Datasets used for training the emotion recognition models.


### NOTICE make sure u have the dataset downloaded 

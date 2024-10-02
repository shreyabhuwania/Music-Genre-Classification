# Music Genre Classification

This project is a web-based application where users can record audio or upload pre-existing audio files to determine the genre of the music. The project leverages various machine learning models, particularly Long Short-Term Memory (LSTM), to classify music genres based on extracted features from the audio files.

## Features

- **Audio Upload/Recording**: Users can upload audio files or record directly on the website.
- **Music Genre Classification**: The website predicts the genre of the audio using machine learning models.

### Libraries and Tools Used

- **MFCC (Mel Frequency Cepstral Coefficients)**: Extracts relevant audio features for training and testing models.
- **TensorFlow**: Used for model training and deep learning.
- **Librosa**: Extracts audio features like MFCCs.
- **NumPy**: Provides mathematical operations and scientific computing.
- **Scikit-learn**: Helps in data splitting for training and testing.
- **JSON**: Used to serialize the dataset for further usage.

## Model Training

The project includes links to the notebooks for data preprocessing, model training, and testing. These steps involve feature extraction from audio files and training LSTM models for classification:

- [Data Preprocessing and Feature Extraction](#https://colab.research.google.com/drive/1JIbrvzVM3CRcM_E75q2Vb5UkWYu15EVJ)
- [Model Training using LSTM](#https://colab.research.google.com/drive/1DmWMXBUgcYeGk11KBBjxzSgpreezN-3M#scrollTo=PhlXiyZ7xMsS)
- [Model Testing and Evaluation](#https://colab.research.google.com/github/shreyabhuwania/Music-Genre-Classification/blob/main/Model_Testing.ipynb)

## Dataset

We used the **GTZAN Music Genre Dataset**, containing 1,000 audio samples, each 30 seconds long, from 10 different genres such as blues, classical, jazz, pop, and more.

---

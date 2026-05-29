# CodSoft Tasks

This repository contains three machine learning projects developed using Python, Scikit-learn, TensorFlow, and Google Colab. Each project demonstrates the application of machine learning and deep learning techniques to solve real-world problems such as text classification, text generation, and fraud detection.

# Task 1: Movie Genre Classification
### Overview

The goal of this project is to predict the genre of a movie based on its plot summary. Natural Language Processing (NLP) techniques are used to convert textual data into numerical features, which are then used to train a machine learning classifier.
### Dataset (
Dataset: [Movie Genre Classification] (https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb)

### Techniques Used
* TF-IDF Vectorization
* Linear Support Vector Machine (SVM)
* Text Preprocessing
### Workflow
* Load movie plot dataset.
* Extract plot summaries and genre labels.
* Convert text into TF-IDF feature vectors.
* Train a Linear SVM classifier.
* Evaluate model performance.
* Allow users to enter custom movie plots for genre prediction.

### Result

Achieved approximately 57.68% accuracy using TF-IDF and Linear SVM for genre classification.

# Task 2: Handwritten-Like Text Generation using Character-Level RNN
### Overview

This project implements a Character-Level Recurrent Neural Network (RNN) using LSTM to generate human-like text. The model learns writing patterns from a text dataset and generates new text based on a user-provided seed input.

### Techniques Used
* Character-Level Text Processing
* Long Short-Term Memory (LSTM)
* Deep Learning with TensorFlow/Keras
### Workflow
* Load text dataset (Tiny Shakespeare Dataset).
* Create character-to-index mappings.
* Generate character sequences for training.
* Build and train an LSTM-based RNN.
* Generate new text from user-provided seed text.
### Result

The model successfully learned Shakespeare-style writing patterns and generated new text that resembles the training data.

# Task 3: Credit Card Fraud Detection
### Overview

The objective of this project is to identify fraudulent credit card transactions using machine learning techniques. The model analyzes transaction-related features and classifies transactions as legitimate or fraudulent.
### Dataset
Dataset: [Credit Card Fraud Detection] (https://www.kaggle.com/datasets/kartik2112/fraud-detection)

### Techniques Used
* Data Preprocessing
* Label Encoding
* Random Forest Classifier
* Performance Evaluation Metrics
### Workflow
* Load training and testing datasets.
* Preprocess categorical and numerical features.
* Encode categorical variables.
* Train a Random Forest classifier.
* Evaluate model performance using accuracy and classification metrics.
* Predict whether a transaction is fraudulent or legitimate.
### Result

The model achieved high classification performance and successfully detected fraudulent transactions while handling a large-scale transaction dataset.

### Technologies Used
* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn
* TensorFlow / Keras
* Matplotlib
# Repository Structure
```text
CodSoft/
│
├── Movie_Genre_Classification/
│   ├── movie_genre_classification.ipynb
│   └── dataset/
│
├── Handwritten_Text_Generation/
│   ├── handwritten_text_generation.ipynb
│   └── dataset/
│
├── Credit_Card_Fraud_Detection/
│   ├── credit_card_fraud_detection.ipynb
│   └── dataset/
│
└── README.md
```

# Author

**Janhavi Sakore**
 Artificial Intelligence & Machine Learning (AIML) Student

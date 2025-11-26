# Movie-Poster-Genre-Prediction
Overview

This project predicts a movie’s genre using only its poster.
Using Convolutional Neural Networks (CNNs) and Transfer Learning (ResNet / MobileNet), the system learns visual patterns from thousands of movie posters and classifies them into genres such as Action, Comedy, Drama, Thriller, etc.

This project demonstrates strong skills in:

Computer Vision

Transfer Learning

Deep Learning Model Training

Exploratory Data Analysis

Image Classification Pipelines

Model Deployment (Streamlit/FastAPI optional)

🚀 Features

Predicts movie genre directly from poster image

Uses Transfer Learning (ResNet-50 / MobileNetV2) for high accuracy

Efficient preprocessing pipeline

Visualization of genre distribution

Data augmentation to boost generalization

Confusion matrix + classification report

Trained on 8,252 posters

Supports top-3 genre prediction

Includes Jupyter notebooks for:

Data exploration

Model training

Model evaluation

🗂️ Project Structure
MoviePosterGenrePrediction/
│
├── data/
│   ├── train/             # Training images (organized in subfolders by genre)
│   ├── val/               # Validation images
│   └── test/              # Test images
│
├── notebooks/             # Jupyter notebooks for EDA and experiments
│   └── exploration.ipynb
│
├── src/
│   ├── data_loader.py     # Data preprocessing & augmentation
│   ├── model.py           # CNN model architecture
│   ├── train.py           # Training pipeline
│   ├── evaluate.py        # Evaluation metrics and confusion matrix
│   ├── predict.py         # Prediction on a single poster
│   └── utils.py           # Helper functions (plots, labels, etc.)
│
├── saved_models/          # Trained model weights
│   └── best_model.h5
│
├── requirements.txt       # Python dependencies
├── README.md
└── main.py                # Entry point to run training + evaluation


Ready-to-run Streamlit UI (optional)

📊 Dataset

Total posters: 8,252
Split:
Train: 70% → 5,776 images
Validation: 15% → 1,238 images
Test: 15% → 1,238 images


🎯 Evaluation
Evaluate on the test set using:
Accuracy
Confusion Matrix
Precision/Recall/F1
Per-genre performance

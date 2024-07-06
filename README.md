Fake News Detector
Introduction
This project aims to build a model to detect fake news using machine learning techniques. The dataset consists of two categories: real news and fake news. The project involves data preprocessing, model building using Support Vector Machine (SVM), and evaluation of the model's performance.

Project Overview
This project is part of the WiDS 2023 (Winter in Data Science) organized by the Analytics Club. The primary goal is to classify news articles as real or fake based on their content.

Datasets
Two datasets are used in this project:

true.csv: Contains real news articles.
fake.csv: Contains fake news articles.
Steps
Data Loading: Load the datasets from CSV files.
Data Inspection: Inspect the datasets to ensure correctness.
Data Labeling: Add labels to the datasets (1 for real news and 0 for fake news).
Data Preprocessing: Clean the text data, remove stopwords, and perform stemming.
Feature Extraction: Use TF-IDF Vectorizer to convert text data into numerical features.
Train-Test Split: Split the data into training and testing sets.
Model Building: Build and train a Support Vector Machine (SVM) classifier.
Model Evaluation: Evaluate the model using accuracy score and confusion matrix.
Model Saving: Save the trained model and vectorizer for future use.

Acknowledgments
This project is part of the WiDS 2023 (Winter in Data Science) organized by the Analytics Club. Special thanks to the organizers and participants for their support and contributions.

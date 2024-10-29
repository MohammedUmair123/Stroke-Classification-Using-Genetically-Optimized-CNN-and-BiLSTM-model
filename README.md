# Stroke-Classification-Using-Genetically-Optimized-CNN with LSTM and BiLSTM models.


Overview:

This project focuses on classifying brain CT images as either Stroke or Normal. Using a combination of VGG19 for feature extraction, a Genetic Algorithm for optimal feature selection, and LSTM and BiLSTM models for classification, the proposed model achieves high accuracy in stroke detection.


Key Features:

Feature Extraction:

VGG19 model, pre-trained on ImageNet, is used to extract deep features from brain CT images.

Genetic Algorithm: 

Features are selected optimally using a Genetic Algorithm, improving model performance by eliminating irrelevant features.

Classification:
LSTM and BiLSTM models are implemented for classifying the extracted features.
Model output labels images as Stroke or Normal.

Comparison with Other Models: 

The proposed model's performance is compared with:
Machine Learning Models: Logistic Regression, Random Forest Classifier, Naive Bayes, SVM, and Decision Tree.
Deep Learning Models: CNN, RNN, and ANN.

Results:

The Genetically Optimized CNN with LSTM and BiLSTM model outperformed the traditional machine learning and deep learning models in terms of accuracy, establishing its robustness in detecting strokes from CT images.

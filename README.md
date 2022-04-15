# Third Year Project Code (2019/2020)

# Introduction
This repo uses a Convolutional Neural Network to classify seven emotions: 
Anger, Disgust, Fear, Happy, Sad, Surprise, Neutral. Alongside multiple Binary Classifers that classify one of the seven emotions, for example: Angry or not, Happy or not etc.

This program leverages the CNN model implemented by Keras whilst running on top of TensorFlow.

# Getting started

To run these files, make sure the following environment and libraries are up to date:
1) Python
2) TensorFlow
3) Keras
4) Numpy
5) Pandas
6) sklearn

# File Contents

The project was done using Kaggle IDE, to take advantage of google's GPUs.

The dataset folder contains the main dataset 'ferdataset' and also the code to 
convert the dataset into the multiple binary datasets required for the project.

The multiclass classifer consists of three files:

1) preprocessing.ipynb
2) creating-cnn.ipynb
3) testing-saved-cnn-model.ipynb

The binary classifiers consist of the same file structure e.g angry_binary_classifier:

1) preprocessing-angry.ipynb
2) creating-cnn-angry.ipynb
3) testing-angry-cnn.ipynb

# Results

Results are shown through confusion matrices at the end of testing, alongside the graph of training the model.

Multiclass classifier - 64% accuracy:

<img src="./confusion_matrix_results/multiclass.jpg" alt="multiclass" />

Binary 'Anger' classifier - 34.4% accuracy:

<img src="./confusion_matrix_results/binary_angry.jpg" alt="angry" />

Binary 'Disgust' classifier - 24.59% accuracy:

<img src="./confusion_matrix_results/binary_disgust.jpg" alt="disgust" />

Binary 'Fear' classifier - 27.5% accuracy:

<img src="./confusion_matrix_results/binary_fear.jpg" alt="fear" />

Binary 'Happy' classifier - 81.11% accuracy:

<img src="./confusion_matrix_results/binary_happy.jpg" alt="happy" />

Binary 'Neutral' classifier - 44.31% accuracy:

<img src="./confusion_matrix_results/binary_neutral.jpg" alt="neutral" />

Binary 'Sad' classifier - 41.45% accuracy:

<img src="./confusion_matrix_results/binary_sad.jpg" alt="sad" />

Binary 'Surprise' classifier - 57.83% accuracy:

<img src="./confusion_matrix_results/binary_surprise.jpg" alt="surprise" />




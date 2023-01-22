# Bridge Crack Detection using Deep Learning

# Description

This project aims to detect cracks in concrete surfaces in bridge engineering using a deep learning approach. The solution employs a transfer learning based approach using the VGG16 model as a base, and utilizes an open source dataset. The final layers of the VGG16 model were replaced with a dense layer and an output layer to adapt it to the problem at hand. The model's performance was evaluated using precision, recall, and F1 score as the judging metrics.

# Dataset

The dataset used in this project can be found at the following link: https://cutt.ly/PS_1_dataset

# Requirements

****TensorFlow
Keras
Numpy
Scikit-learn****

# Judging metrics

Testing Accuracy is:  0.975

Precision:  [1.         0.95238095]

Recall:  [0.95 1.  ]

F1:  [0.97435897 0.97560976]

Confusion matrix:
 
 [[ 95   5]
 
 [  0 100]]


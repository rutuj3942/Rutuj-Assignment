Detection with Basic CNN (Accuracy: 92.23%)

Overview

This project utilizes a basic Convolutional Neural Network (CNN) for detecting NEU Metal Surface Defects, achieving an accuracy of 92.23%. The model is designed to classify images into six defect categories.

Model Architecture

Conv2D Layers: Three layers with increasing filter sizes (32, 64, 128), kernel size (3,3), activation 'relu'

MaxPooling2D Layers: Pool size (2,2)

Dense Layers: A dense layer with 128 units and a dropout of 0.5, followed by a softmax layer for classification

Data Preprocessing

Images rescaled by 1./255

Train-validation split: 80%-20%

Evaluation

Test accuracy: 92.23%

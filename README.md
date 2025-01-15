# Rutuj-Assignment


Metal Surface Defect Detection Models
This repository contains various models developed and tested on the NEU Metal Surface Defects Data dataset. Each model aims to identify defects on metal surfaces with varying levels of accuracy and methodologies.

Models Overview
1. Basic CNN
Description: A simple Convolutional Neural Network (CNN) model designed to detect defects on metal surfaces.
Dataset: NEU Metal Surface Defects Data
Accuracy: 86.56%
Key Features:
Basic CNN architecture
Suitable for baseline performance comparison
2. MobileNet
Description: A lightweight deep neural network architecture optimized for mobile and embedded vision applications. This model was fine-tuned for metal surface defect detection.
Dataset: NEU Metal Surface Defects Data
Accuracy: 98.15%
Key Features:
Efficient and fast
High accuracy for defect detection
3. ResNet50
Description: A 50-layer deep convolutional network known for its residual connections, which help in training deeper networks.
Dataset: NEU Metal Surface Defects Data
Accuracy: 31.84%
Key Features:
Complex architecture
Lower performance in this specific application, possibly due to overfitting or insufficient training data
4. U-Net
Description: A convolutional network designed for biomedical image segmentation but adapted here for segmenting defects on metal surfaces.
Dataset: NEU Metal Surface Defects Data
Application: Image Segmentation
Key Features:
Efficient for segmenting small defects
Utilized for highlighting defect areas on metal surfaces
5. YOLO (You Only Look Once)
Description: A real-time object detection system capable of detecting defects on metal surfaces with high speed and accuracy.
Dataset: NEU Metal Surface Defects Data
Application: Defect Detection
Key Features:
Real-time detection
Balances accuracy and speed effectively
Usage
Installation:


Ensure the NEU Metal Surface Defects Data dataset is downloaded and placed in the appropriate directory as specified in each model's instructions.
Results and Discussion
Basic CNN: Provided a solid baseline with an accuracy of 86.56%.
MobileNet: Achieved the highest accuracy of 98.15%, making it the most effective model for this dataset.
ResNet50: Underperformed with an accuracy of 31.84%, indicating potential issues with model suitability or data processing.
U-Net: Successfully segmented images, highlighting defect regions.
YOLO: Delivered real-time defect detection with a balance of speed and accuracy.
Conclusion
This repository demonstrates the application of various neural network architectures to detect and segment defects on metal surfaces. Each model has its strengths and areas for improvement, providing a comprehensive study on metal surface defect detection.

Contact

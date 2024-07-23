1)Introduction

Alzheimer's disease is a progressive neurodegenerative disorder that affects millions of people worldwide. Early and accurate detection of the disease stages is crucial for effective treatment and management. This project utilizes deep learning techniques to predict the stages of Alzheimer's disease from MRI scans.

2)Data
dataset link-https://www.kaggle.com/datasets/tourist55/alzheimers-dataset-4-class-of-images
The dataset consists of MRI scans categorized into four classes:

Mild Demented
Moderate Demented
Non Demented
Very Mild Demented


3)Methodology

Data Preprocessing
Normalization: Standardized pixel intensities to enhance model performance.
Augmentation: Applied techniques such as rotation, flipping, and zooming to increase data diversity.
Segmentation with U-Net
Architecture: Used U-Net for its effectiveness in biomedical image segmentation.
Training: Segmented MRI images to isolate relevant brain structures.
Classification with AdaBoost
Features: Extracted features from the segmented MRI images.
Classifier: Implemented AdaBoost, an ensemble learning method, to improve prediction accuracy.
Training: Trained the classifier to differentiate between the four Alzheimer's stages.

4)Results

The combined approach of U-Net for segmentation and AdaBoost for classification achieved high accuracy and robust performance. The model's effectiveness was demonstrated through metrics such as precision, recall, and F1-score.

5)Conclusion

The integration of U-Net and AdaBoost provides a powerful framework for predicting Alzheimer's disease stages from MRI scans. This methodology offers a potential tool for early diagnosis and progression monitoring of Alzheimer's disease.

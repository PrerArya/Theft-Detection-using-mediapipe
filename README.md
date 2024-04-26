# Theft Detection Algorithm Using MediaPipe: A Comprehensive Guide

## Introduction
In this project, we aimed to develop a robust theft detection algorithm using the DCSASS dataset, focusing specifically on shoplifting scenarios. Leveraging MediaPipe, a powerful tool for building machine learning models with video data, we employed a systematic approach encompassing data preprocessing, feature engineering, model building, and evaluation.

## Data Preprocessing
We began by downloading the DCSASS dataset and filtering for videos labeled as "shoplifting." This step involved extracting relevant video clips and converting them into a suitable format compatible with MediaPipe. We opted for MediaPipe's preferred input format, which typically involves video frames represented as arrays of pixel values.

## Feature Engineering
Using MediaPipe, we extracted key features from the preprocessed videos that are indicative of shoplifting activities. MediaPipe offers a wide array of pre-trained models and modules for tasks such as object detection, pose estimation, and hand tracking, which proved invaluable for extracting meaningful features from the video frames. Specifically, we focused on features related to human pose, object interactions, and spatial-temporal patterns characteristic of shoplifting behaviors.

## Model Building
For the machine learning model, we utilized a deep learning architecture tailored for video classification tasks. MediaPipe provides seamless integration with popular deep learning frameworks such as TensorFlow and PyTorch, enabling us to build and train custom models efficiently. We designed a convolutional neural network (CNN) architecture augmented with recurrent layers to capture temporal dependencies within the video sequences.

## Evaluation
We evaluated the performance of our theft detection model using a range of metrics including accuracy, precision, recall, and F1 score. Additionally, we visualized the model's performance using a confusion matrix to gain insights into its strengths and weaknesses.

## Report
Our comprehensive report summarizes the approach undertaken, including the rationale behind data preprocessing techniques, the effectiveness of feature engineering methods, model selection justification, and evaluation results. We discuss the strengths and weaknesses of our approach, along with potential avenues for further improvement.

## Folder Structure
- **data**: Contains the DCSASS dataset and preprocessed video clips.
- **src**: Contains the source code for data preprocessing, feature engineering, model building, and evaluation.
- **models**: Contains saved model checkpoints and evaluation metrics.
- **reports**: Contains the project report summarizing the approach and results.


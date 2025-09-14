# Pneumonia Detection
## Project Overview
This project implements a deep learning approach to detect pneumonia from chest X-ray images. The notebook (main_pneumonia.ipynb) contains the full pipeline, including dataset loading, preprocessing, model training, evaluation, and prediction.

The goal of this project is to assist medical practitioners and researchers by providing an AI-based tool for pneumonia detection, which can help in early diagnosis and treatment.

## Features

1. Preprocessing of chest X-ray images (resizing, normalization, augmentation).

2. Deep learning model (CNN / transfer learning such as VGG16, ResNet, etc.).

3. Training and validation with accuracy and loss plots.

4. Model evaluation using metrics (accuracy, precision, recall, F1-score, confusion matrix).

5. Prediction function for new X-ray images.

.

## Project Structure
├── README.md

├── main_pneumonia.ipynb        

## Requirements

Make sure you have the following dependencies installed:

pip install numpy pandas matplotlib seaborn scikit-learn tensorflow keras opencv-python

## Dataset

https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

## Results
### Confusion Matrix

<img width="710" height="323" alt="image" src="https://github.com/user-attachments/assets/57ae4f30-c8f0-43a2-9523-7edb4aa14838" />

### Performance Metrics:

| Model            | Accuracy | Precision | Recall | F1 Score |
| ---------------- | -------- | --------- | ------ | -------- |
| **Inception V3** | **88%**  | 87%       | 87%    | 87%      |
| ResNet152        | 80%      | 84%       | 74%    | 76%      |
| VGG19            | 79%      | 87%       | 72%    | 74%      |
| Xception         | 83%      | 87%       | 78%    | 79%      |

Inception V3 performed best among the tested architectures, achieving 88% accuracy with balanced precision and recall.




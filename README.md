# DL Final Project - Lung Cancer Classification

## Project Overview

This project focuses on classifying lung cancer images into three categories: 'Benign cases,' 'Malignant cases,' and 'Normal cases' using deep learning techniques. The goal is to develop an accurate and efficient model for early lung cancer detection.

## Dataset

The dataset consists of medical lung cancer images labeled into the three mentioned categories. Data preprocessing techniques such as normalization, augmentation, and resizing were applied to enhance model performance.

## Model Architecture

The project implements a CNN-based deep learning model. Additionally, transfer learning was explored using pre-trained models to improve classification accuracy.

## Training Approach

- The dataset was split into training, validation, and test sets.
- A CNN model was trained initially, followed by enhancements such as early stopping and fine-tuning.
- SMOTE was applied to handle class imbalance.
- Hyperparameter tuning was conducted to optimize model performance.

## Evaluation

- The best model achieved **100% accuracy** on the test set.
- Precision, recall, and F1-score confirmed excellent classification results.
- A confusion matrix was generated to visualize model predictions.

## Results

| Class       | Precision | Recall   | F1-score | Support |
| ----------- | --------- | -------- | -------- | ------- |
| Benign      | 1.00      | 1.00     | 1.00     | 12      |
| Malignant   | 1.00      | 1.00     | 1.00     | 56      |
| Normal      | 1.00      | 1.00     | 1.00     | 42      |
| **Overall** | **1.00**  | **1.00** | **1.00** | **110** |

## Future Improvements

- Experimenting with more advanced architectures.
- Exploring different augmentation techniques.
- Deploying the model as a web application for real-time diagnosis.

## Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/NicoleDavidov/DL_finalProject.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the training script:
   ```bash
   python train.py
   ```
4. Evaluate the model:
   ```bash
   python evaluate.py
   ```

## Conclusion

This project successfully implemented deep learning techniques to classify lung cancer images with high accuracy, demonstrating the potential of AI in medical diagnosis.


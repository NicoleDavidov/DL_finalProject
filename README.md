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

- The CNN model achieved **99% accuracy** on the test set.
- The Transfer Learning model achieved **100% accuracy** on the test set.
- Precision, recall, and F1-score confirmed excellent classification results.
- A confusion matrix was generated to visualize model predictions.

## Results

### CNN Model Performance
| Class            | Precision | Recall   | F1-score | Support |
|-----------------|-----------|----------|----------|---------|
| Benign cases    | 1.00      | 0.87     | 0.93     | 23      |
| Malignant cases | 1.00      | 1.00     | 1.00     | 123     |
| Normal cases    | 0.96      | 1.00     | 0.98     | 74      |
| **Overall**     | **0.99**  | **0.99** | **0.99** | **220** |

### Transfer Learning Model Performance
| Class            | Precision | Recall   | F1-score | Support |
|-----------------|-----------|----------|----------|---------|
| Benign cases    | 1.00      | 1.00     | 1.00     | 23      |
| Malignant cases | 1.00      | 1.00     | 1.00     | 123     |
| Normal cases    | 1.00      | 1.00     | 1.00     | 74      |
| **Overall**     | **1.00**  | **1.00** | **1.00** | **220** |

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


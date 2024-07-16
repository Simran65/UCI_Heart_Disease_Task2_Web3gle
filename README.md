# UCI_Heart_Disease_Task2_Web3gle

# UCI Heart Disease Prediction

This project is part of Task 2 of my internship at Web3Gle. The aim is to implement a K-Nearest Neighbors (KNN) classification model to predict heart disease using the UCI Heart Disease dataset.

## Dataset

The dataset used is the [Heart Disease UCI](https://www.kaggle.com/ronitf/heart-disease-uci) dataset available on Kaggle. The target variable is `target`, indicating the presence of heart disease.

## Features Selection

The features were selected based on their correlation with the target variable. The threshold for correlation was set to 0.25. The selected features are:

- `age`
- `sex`
- `chest_pain_type`
- `thalch`
- `exang`
- `oldpeak`
- `ca`
- `target`

## Steps

1. **Data Preprocessing**: Handled missing values, duplicates, and standardized the features.
2. **Feature Selection**: Selected features based on a correlation threshold.
3. **Model Training**: Used K-Nearest Neighbors (KNN) classifier.
4. **Evaluation**: Evaluated the model using accuracy, precision, recall, F1-score, and confusion matrix.

## Results

### Before Feature Selection

- **Accuracy**: 83.69%
- **Precision**: 0.82
- **F1-Score**: 0.82

### After Feature Selection

- **Accuracy**: 63.83%
- **Precision**: 0.61
- **F1-Score**: 0.62

## Conclusion

The KNN model performed better before feature selection. Further tuning and feature engineering may improve the results.

## Repository Structure

- `data/`: Contains the dataset.
- `notebooks/`: Jupyter notebooks for data preprocessing, feature selection, and model training.
- `src/`: Source code for data processing and modeling.
- `results/`: Contains results and evaluation metrics.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Simran65/UCI_Heart_Disease_Task2_Web3gle.git

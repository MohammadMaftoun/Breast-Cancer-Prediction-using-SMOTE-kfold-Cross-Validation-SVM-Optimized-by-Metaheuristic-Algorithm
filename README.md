#🩺 Breast Cancer Prediction using SVM optimized by a Metaheuristic Algorithm

![BC](https://cancer-data.ecrc.ed.ac.uk/wp-content/uploads/2020/06/icon-imagery.png)

This project is aimed at creating a predictive model for breast cancer diagnosis using the sklearn breast cancer dataset. The dataset is balanced using Synthetic Minority Over-sampling Technique (SMOTE), and the model's performance is cross-validated using k-fold cross-validation. The Support Vector Machine (SVM) model is optimized using a Metaheuristic Algorithm and comparing to genetic algorithm using TPOT library.

## Features

- **Data Preprocessing**: Implement data preprocessing techniques to ensure data quality,handel imbalanced target class using SMOTE and scaling data between 0-1 using MinMaxScaler.
- **K fold cross validation**: The KCV consists in dividing the training set in k parts, each one consisting of l/k samples: k − 1 parts are used, in turn, as a training set and the remaining one is used as a validation set.This teqnique can prevent overfitting!.
- **SVM optimized by Metaheuristic Algorithm**:Machine learning model was Support vector machines which optimized by a Metaheuristic Algorithm
- **Gentic algorithm**: Apply genetic algorithms to finding best parameters and suitable algorithm in this task.

## Getting Started

To get started with this AI based system, follow these steps:

1. Clone the repository: `git clone https://github.com/MohammadMaftoun/Breast-Cancer-Prediction-using-SMOTE-kfold-Cross-Validation-SVM-Optimized-by-Metaheuristic-Algorithm.git`
2. Navigate into the cloned project directory:'cd Breast-Cancer-Prediction-using-SMOTE-kfold-Cross-Validation-SVM-Optimized-by-Metaheuristic-Algorithm'
'
3. Install the required dependencies: `pip install -r requirements.txt`

## Usage


    Load the sklearn breast cancer dataset.

    Balance the dataset using SMOTE.

    Implement k-fold cross-validation for robust performance evaluation.

    Use the SVM model for prediction, optimizing its parameters using a Metaheuristic Algorithm.

    Use TPOT for genetic based optimiztion


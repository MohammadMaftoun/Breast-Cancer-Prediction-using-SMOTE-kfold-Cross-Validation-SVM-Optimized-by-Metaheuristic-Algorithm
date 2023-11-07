# 🩺Breast Cancer Prediction by Optimization of support vector machine through the use of metaheuristic algorithm

![BC](https://cancer-data.ecrc.ed.ac.uk/wp-content/uploads/2020/06/icon-imagery.png)

This project is aimed at creating a predictive model for breast cancer diagnosis using the sklearn breast cancer dataset. The dataset is balanced using Synthetic Minority Over-sampling Technique (SMOTE), and the model's performance is cross-validated using k-fold cross-validation. The Support Vector Machine (SVM) model is optimized using a Metaheuristic Algorithm and compared to a genetic algorithm using the TPOT library.

## Features

- **Data Preprocessing**: Implement data preprocessing techniques to ensure data quality, handle imbalanced target class using SMOTE, and scale data between 0-1 using MinMaxScaler.
- **K fold cross validation**: The KCV consists of dividing the training set into k parts, each one consisting of l/k samples: k − 1 parts are used, in turn, as a training set and the remaining one is used as a validation set. This technique can prevent overfitting!
- **SVM optimized by Metaheuristic Algorithm**:Machine learning model was support vector machine which optimized by a Metaheuristic Algorithm
- **Genetic algorithm**: Apply genetic algorithms to find the best parameters and suitable algorithm for this task.

## Getting Started

To get started with this AI-based system, follow these steps:

1. Clone the repository: `git clone https://github.com/MohammadMaftoun/Breast-Cancer-Prediction-using-SMOTE-kfold-Cross-Validation-SVM-Optimized-by-Metaheuristic-Algorithm.git`
2. Navigate into the cloned project directory:'cd Breast-Cancer-Prediction-using-SMOTE-kfold-Cross-Validation-SVM-Optimized-by-Metaheuristic-Algorithm'
'
3. Install the required dependencies: `pip install -r requirements.txt`

## Usage


    Load the sklearn breast cancer dataset.

    Balance the dataset using SMOTE.

    Implement k-fold cross-validation for robust performance evaluation.

    Use the SVM model for prediction, optimizing its parameters using a Metaheuristic Algorithm.

    Use TPOT for genetic-based optimiztion


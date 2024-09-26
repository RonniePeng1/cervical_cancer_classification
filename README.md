# cervical_cancer_classification
Cervical Cancer Classification with Machine Learning

# Cervical Cancer Classification with Machine Learning

This repository contains the code and analysis for the final project by **Yupeng He** and **Martin Li**. The project focuses on the classification of cervical cancer using various machine learning models and techniques to handle class imbalance in the dataset.

## Project Overview

The dataset used in this project contains risk factors related to cervical cancer. We address the problem of class imbalance and explore different classification models such as:

- Logistic Regression
- k-Nearest Neighbors (kNN)
- Random Forest (Bagging)
- Boosting (GBM)

We employ cross-validation and adaptive synthetic sampling (ADASYN) to improve model performance and handle the imbalance in the dataset.

## Key Features:
- **Class Imbalance Handling**: Techniques like ADASYN and threshold moving were implemented to balance the dataset.
- **Model Evaluation**: Models were evaluated using accuracy, recall, precision, and F1-score, with ROC curves and AUC metrics used to measure performance.
- **Cost-Sensitive Learning**: Explored cost-sensitive learning techniques to optimize classification for imbalanced data.

## Requirements

- R (Version 4.0 or higher)
- Required packages: `tidyverse`, `caret`, `e1071`, `randomForest`, `gbm`, `pROC`, `UBL`

## Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cervical-cancer-classification.git
2. Install the required packages:
   ```bash
   source("src/cervical_cancer_analysis.R")

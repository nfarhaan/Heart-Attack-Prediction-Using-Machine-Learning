# Heart Attack Prediction Using Machine Learning

## Overview

This project focuses on predicting heart attack risks using two machine learning models: **Decision Tree** and **Multilayer Perceptron (MLP)**. By combining four public datasets and optimizing hyperparameters, we built models capable of predicting heart attack risks with high accuracy. The project is designed to improve early detection and prevention of heart disease.

## Models Used

1. **Decision Tree Classifier**
   - **Accuracy:** 98.94%
   - **Precision:** 98.95%
   - **Recall:** 98.94%
   - **F1-Score:** 98.94%
   - **Specificity:** 98.29%

2. **Multilayer Perceptron (MLP)**
   - **Accuracy:** 92.33%
   - **Precision:** 92.39%
   - **Recall:** 92.33%
   - **F1-Score:** 92.33%
   - **Specificity:** 90.53%

## Dataset

We merged four public datasets related to heart disease, containing 1,888 records and 14 key features, such as:
- Age
- Cholesterol levels
- Chest pain type
- Resting blood pressure
- Maximum heart rate achieved
- ST depression induced by exercise
- Number of major vessels colored by fluoroscopy

The initial dataset had 2,181 rows, but 293 rows with missing values were removed for data integrity.

## Preprocessing and Feature Selection

- **Data Cleaning:** Rows with missing values were dropped.
- **Standardization:** Feature names were standardized across datasets.
- **Feature Selection:** All 14 features were retained to ensure comprehensive heart disease prediction.

## Key Contributions

- **Large Dataset:** We addressed the challenge of limited dataset size by merging multiple datasets, improving the generalizability and robustness of our models.
- **Incorporation of Critical Features:** Our dataset includes essential heart disease indicators like ECG outcomes, which were missing in some previous studies.
- **Hyperparameter Tuning:** Both models underwent extensive hyperparameter tuning to achieve optimal performance.

## Future Work

To further improve model performance, we plan to integrate **Particle Swarm Optimization (PSO)** and **Genetic Algorithms (GA)** for optimization. We also aim to explore real-time applications for heart disease prediction.

## Installation and Usage

To replicate this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/HeartAttackPrediction.git


## References
Alshraideh, et al., 2024.
Chellammal & Sharmila, 2019.
Hossain, et al., 2023.
## Contributors & Authors
Farhaan Nazirkhan &
Sarwin Rajiah

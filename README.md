# Heart Attack Prediction Using Machine Learning

## Overview

This project focuses on predicting heart attack risks using two machine learning models: **Decision Tree** and **Multilayer Perceptron (MLP)**. By combining four public datasets and optimizing hyperparameters, we built models capable of predicting heart attack risks with high accuracy. The project is designed to improve early detection and prevention of heart disease.

## Models Used

1. **Decision Tree Classifier**
   - **Accuracy:** 92.33%
   - **Precision:** 92.33%
   - **Recall:** 92.33%
   - **F1-Score:** 92.33%
   - **Specificity:** 91.21%

2. **Multilayer Perceptron (MLP)**
   - **Accuracy:** 92.33%
   - **Precision:** 92.39%
   - **Recall:** 92.33%
   - **F1-Score:** 92.33%
   - **Specificity:** 90.53%

## Dataset
Provenance

Edit
Sources
The data used in this project is sourced from five publicly available datasets focused on heart disease prediction. These datasets were collected from various reliable sources, including healthcare research organizations and data science platforms. The datasets used are as follows:

Heart Attack Analysis & Prediction Dataset (Rahman, 2021) Sourced from: Kaggle Contains 304 records of patients with various heart-related attributes.

Heart Disease Dataset (Lapp, 2019) Sourced from: Kaggle A widely used dataset containing 1,026 records with features relevant to heart disease prediction.

Heart Attack Prediction (Dataset 3) (Damarla, 2020) Sourced from: Kaggle Contains 295 records focused on heart attack prediction using patient medical history.

Heart Attack Prediction (Dataset 4) (Anand, 2018) Sourced from: Kaggle Provides 271 records with essential heart disease risk factors.

Heart CSV Dataset (Nandal, 2022) Sourced from: Figshare Contains 290 records relevant to heart disease prediction.

## Collection Methodology
Data Merging: We combined the five datasets to form a larger, more robust dataset. Each dataset included similar features but with varying naming conventions, which were standardized during preprocessing. Data Cleaning: Rows with missing values were dropped to ensure data integrity. A total of 293 rows were removed, leaving 1,888 records for training and testing the machine learning models. Feature Standardization: We ensured that feature names and values were standardized across all datasets to maintain consistency. For example, chest pain types and thalassemia values were normalized across datasets.

We merged four public datasets related to heart disease, containing 1,888 records and 14 key features, such as:
Feature Descriptions:
age: Age of the patient (Numeric).
sex: Gender of the patient. Values: 1 = male, 0 = female.
cp: Chest pain type. Values: 0 = Typical angina, 1 = Atypical angina, 2 = Non-anginal pain, 3 = Asymptomatic.
trestbps: Resting Blood Pressure (in mm Hg) (Numeric).
chol: Serum Cholesterol level (in mg/dl) (Numeric).
fbs: Fasting blood sugar > 120 mg/dl. Values: 1 = true, 0 = false.
restecg: Resting electrocardiographic results. Values: 0 = Normal, 1 = ST-T wave abnormality, 2 = Left ventricular hypertrophy.
thalach: Maximum heart rate achieved (Numeric).
exang: Exercise-induced angina. Values: 1 = yes, 0 = no.
oldpeak: ST depression induced by exercise relative to rest (Numeric).
slope: Slope of the peak exercise ST segment. Values: 0 = Upsloping, 1 = Flat, 2 = Downsloping.
ca: Number of major vessels (0-3) colored by fluoroscopy. Values: 0, 1, 2, 3.
thal: Thalassemia types. Values: 1 = Normal, 2 = Fixed defect, 3 = Reversible defect.
target: Outcome variable (heart attack risk). Values: 1 = more chance of heart attack, 0 = less chance of heart attack.

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
   git clone https://github.com/nfarhaan/HeartAttackPrediction.git


## References
Alshraideh, et al., 2024.
Chellammal & Sharmila, 2019.
Hossain, et al., 2023.
## Contributors & Authors
Farhaan Nazirkhan &
Sarwin Rajiah

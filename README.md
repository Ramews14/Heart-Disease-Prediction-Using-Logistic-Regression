# Heart Disease Prediction Using Logistic Regression

This project is a machine learning solution that predicts whether a person has heart disease based on certain medical attributes. The model uses **Logistic Regression** to classify individuals into two categories: `Disease` and `No Disease`.

## Table of Contents

- [Project Description](#project-description)
- [Dataset](#dataset)
- [Installation](#installation)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

## Project Description

This project aims to predict the likelihood of heart disease in patients using various features such as age, sex, cholesterol levels, blood pressure, and other medical measurements. The model is trained using a dataset and evaluated using various performance metrics such as accuracy, confusion matrix, and classification report.

The project demonstrates the following:
- Data preprocessing
- Logistic regression model building and training
- Model evaluation and prediction on new data
- Data visualization of the results

## Dataset

The dataset used in this project is `heart.csv`, containing the following features:
- `age`: Age of the patient
- `sex`: Gender of the patient (1 = male, 0 = female)
- `cp`: Chest pain type (0, 1, 2, 3)
- `trestbps`: Resting blood pressure
- `chol`: Serum cholesterol in mg/dl
- `fbs`: Fasting blood sugar (> 120 mg/dl)
- `restecg`: Resting electrocardiographic results (0, 1, 2)
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina (1 = yes, 0 = no)
- `oldpeak`: ST depression induced by exercise relative to rest
- `slope`: Slope of the peak exercise ST segment
- `ca`: Number of major vessels (0-3) colored by fluoroscopy
- `thal`: Thalassemia (1 = normal, 2 = fixed defect, 3 = reversible defect)
- `target`: 0 = No Disease, 1 = Disease (This is the label we're trying to predict)

## Installation

To run this project on your local machine, follow these steps:

  1. Clone the repository:

   ```bash
   git clone https://github.com/kaggle/heart-disease-prediction.git
   cd heart-disease-prediction



  

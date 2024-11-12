# Heart Disease Prediction

This project uses machine learning models to predict the likelihood of heart disease based on various medical and demographic features.

## Introduction
Heart disease is a leading cause of mortality worldwide. This project aims to develop a predictive model to assess heart disease risk, assisting in early diagnosis and timely intervention. We use three machine learning models—Logistic Regression, Decision Tree, and Random Forest—and evaluate their performance.

## Dataset
The dataset used in this project is the **Indian Heart Disease Dataset**. It contains various features related to patient demographics and health metrics:
- **Age, Sex, Chest Pain Type (cp)**
- **Resting Blood Pressure (trestbps), Cholesterol Level (chol)**
- **Fasting Blood Sugar (fbs), Electrocardiographic Results (restecg)**
- **Maximum Heart Rate (thalach), Exercise Induced Angina (exang)**
- **ST Depression (oldpeak), ST Segment Slope (slope)**
- **Number of Major Vessels (ca) Colored by Fluoroscopy**

You can find the dataset [here](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset) or from other similar sources for heart disease datasets.

## Project Structure
- **Data Preparation**: Load and preprocess data by separating features and target variable and splitting it into training and test sets.
- **Model Training**: Train Logistic Regression, Decision Tree, and Random Forest models on the data.
- **Evaluation**: Calculate accuracy scores and display the classification report.
- **Visualization**: Compare model performances using a bar chart.
- **Predictive System**: Implement a predictive system that takes user input and predicts the risk of heart disease.

## Models Used
1. **Logistic Regression** - A simple linear model useful for binary classification tasks.
2. **Decision Tree** - A non-linear model that uses tree-based decision rules.
3. **Random Forest** - An ensemble of decision trees that improves prediction accuracy and generalization.

## Results
The models are evaluated on both training and test datasets. Here’s the output for model accuracy:
- **Logistic Regression**: 94% on test data
- **Decision Tree**: 95% on test data
- **Random Forest**: 97% on test data

## Usage
1. **Run Predictions**: You can enter the details of a person’s health metrics, and the Random Forest model will provide a prediction of whether the person is likely to have heart disease.
2. **Model Comparison**: Compare different models to see which performs best on this dataset.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Amithesh-VN/Heart_Disease_Prediction.git

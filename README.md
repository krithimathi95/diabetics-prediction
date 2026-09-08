# diabetics-prediction
This project uses Machine Learning to predict whether a person is likely to have diabetes based on several health-related measurements.
# Diabetes Prediction Using Machine Learning

## Project Description

This project is a Machine Learning-based Diabetes Prediction system developed using Python. The main objective of this project is to predict whether a person is likely to have diabetes based on various health-related features.

The prediction is made using medical information such as pregnancies, glucose level, blood pressure, skin thickness, insulin level, BMI, diabetes pedigree function, and age.

The project uses the Logistic Regression algorithm to classify the input data into two categories: Diabetes or No Diabetes.

## Features

The dataset contains the following features:

* Pregnancies
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age

The output feature is:

* 0 - No Diabetes
* 1 - Diabetes

## Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Machine Learning Algorithm

The project uses Logistic Regression for prediction.

Logistic Regression is used because this project is a binary classification problem where the output has only two possible classes: Diabetes and No Diabetes.

## Project Workflow

1. Load the diabetes dataset.
2. Explore and understand the dataset.
3. Check and handle missing values.
4. Separate input features and target output.
5. Split the dataset into training and testing data.
6. Standardize the feature values using StandardScaler.
7. Train the Logistic Regression model.
8. Evaluate the model using accuracy score, classification report, and confusion matrix.
9. Use the trained model to predict diabetes for new input data.
10. Visualize the relationship between important features such as Glucose and BMI.

## Installation

Clone the repository:

git clone your-repository-link

Navigate to the project directory:

cd Diabetes-Prediction

Install the required libraries:

pip install pandas matplotlib scikit-learn

## Usage

Run the Python program or Jupyter Notebook after installing the required libraries.

Enter the required health-related values, and the trained Machine Learning model will predict whether the person is likely to have diabetes.

## Model Evaluation

The performance of the model can be evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix


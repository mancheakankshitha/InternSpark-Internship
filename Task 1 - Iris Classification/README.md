# Iris Classification Using Machine Learning

## Project Overview

This project is developed as part of the InternSpark Machine Learning Internship.

The objective of this project is to build a machine learning classification system that predicts the species of an iris flower based on its sepal and petal measurements.

The project covers the complete machine learning workflow:
- Data loading
- Exploratory Data Analysis (EDA)
- Data preprocessing
- Model training
- Model comparison
- Model evaluation
- Saving the trained model
- Making predictions on new data

---

## Dataset Description

Dataset: Iris Classification Dataset

The dataset contains information about iris flowers with the following features:

### Input Features:
- sepal_length
- sepal_width
- petal_length
- petal_width

### Target Variable:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Jupyter Notebook / Google Colab

---

## Exploratory Data Analysis

The following analysis was performed:

- Dataset inspection
- Missing value checking
- Feature distribution analysis
- Class separability visualization using pair plots
- Correlation analysis

---

## Machine Learning Models Used

Three classification algorithms were trained and compared:

### 1. k-Nearest Neighbors (k-NN)

A distance-based classification algorithm used for predicting flower species.

### 2. Logistic Regression

A supervised learning algorithm used for multi-class classification.

### 3. Decision Tree Classifier

A tree-based classification algorithm that learns decision rules from data.

---

## Model Evaluation

The models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-score

### Results

| Model | Accuracy |
|-------|----------|
| k-NN | 100% |
| Logistic Regression | 100% |
| Decision Tree | 100% |

All three models achieved excellent performance on the test dataset.

The Logistic Regression model was selected as the final model.

---

## Saved Model Files

The trained model and preprocessing objects are saved using Joblib.

Files included:

iris_model.pkl
scaler.pkl
encoder.pkl


### File Description

**iris_model.pkl**
- Contains the trained Logistic Regression model.

**scaler.pkl**
- Contains the StandardScaler used for feature scaling.

**encoder.pkl**
- Contains the LabelEncoder used for converting species labels.

---

## Example Prediction

The saved model can be loaded and used for predicting a new iris flower species.

Example input:

Sepal Length: 5.1
Sepal Width: 3.5
Petal Length: 1.4
Petal Width: 0.2



Prediction:

Iris-setosa


## Project Structure


Iris Classification
│
├── Iris_Classification.ipynb
├── iris_model.pkl
├── scaler.pkl
├── encoder.pkl
├── requirements.txt
└── README.md



---

## Conclusion

This project successfully demonstrates an end-to-end machine learning classification workflow.

The trained model can accurately classify iris flowers into three different species:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

The project provides practical experience in data preprocessing, visualization, model training, evaluation, and model deployment preparation.sss
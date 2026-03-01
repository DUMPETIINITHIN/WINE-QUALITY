🍷 Wine Quality Analysis & Prediction

📌 Project Overview

The Wine Quality Analysis & Prediction project focuses on predicting the quality of wine based on its chemical properties using Machine Learning classification algorithms.
This project demonstrates how data analytics and ML can be applied to real-world problems in viticulture and food quality assessment.

The goal is to classify wine as good or bad quality by analyzing physicochemical attributes such as acidity, density, alcohol content, and pH.

🎯 Objectives

Analyze chemical features affecting wine quality

Perform Exploratory Data Analysis (EDA)

Build and compare multiple classification models

Evaluate performance using standard ML metrics

Visualize results for better insights

📂 Dataset

Source: UCI Machine Learning Repository / Kaggle

Dataset Name: Wine Quality (Red Wine)

Format: CSV

Records: 1,599 samples

Features: 11 chemical attributes

🔹 Features

Fixed Acidity

Volatile Acidity

Citric Acid

Residual Sugar

Chlorides

Free Sulfur Dioxide

Total Sulfur Dioxide

Density

pH

Sulphates

Alcohol

🔹 Target Variable

Quality (converted into binary classes):

1 → Good Quality (≥ 7)

0 → Bad Quality (< 7)

🛠️ Technologies Used

Programming Language: Python

Libraries:

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

⚙️ Machine Learning Models

The following classifiers were implemented and compared:

Random Forest Classifier

Stochastic Gradient Descent (SGD) Classifier

Support Vector Classifier (SVC)

🔄 Project Workflow

Data Collection

Data Cleaning & Preprocessing

Exploratory Data Analysis (EDA)

Feature Scaling

Model Training

Model Evaluation

Performance Comparison

Result Visualization

📊 Evaluation Metrics

Accuracy Score

Precision

Recall

F1-Score

Confusion Matrix

📈 Visualizations

Correlation Heatmap

Wine Quality Distribution

Confusion Matrices for each model

✅ Results

Random Forest showed strong performance due to ensemble learning

SVC performed well after feature scaling

SGD provided faster training with reasonable accuracy

The comparison helps in selecting the most effective model for wine quality prediction.

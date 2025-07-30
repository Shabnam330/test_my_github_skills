📄 README.md — Capstone Project: Heart Disease Classification

. Project Overview
This capstone project aims to develop and compare machine learning models to predict the presence of heart disease based on clinical and demographic features. The goal is to train and evaluate multiple classification models and select the most effective one based on performance metrics. Ultimately, K-Nearest Neighbors (KNN) provided the best results.

The project uses the [UCI Heart Disease Dataset (ID: 45)](https://archive.ics.uci.edu/dataset/45/heart+disease), which contains several patient attributes such as age, sex, chest pain type, resting blood pressure, cholesterol level, and more.

. Key Components
- Exploratory Data Analysis (EDA)
- Dimensionality Reduction (PCA, t-SNE, UMAP)
- Classification Models:
  - Logistic Regression
  - K-Nearest Neighbors
  - Decision Tree
  - Random Forest
  - Gradient Boosting
- Hyperparameter Tuning (RandomizedSearchCV)
- Model Accuracy Comparison

. Environment Setup
This project requires the following Python libraries:
pip install numpy pandas matplotlib seaborn scikit-learn umap-learn ucimlrepo

. Dataset
Dataset ID: 45 from UCI ML Repo. It is fetched using:
from ucimlrepo import fetch_ucirepo
heart_disease = fetch_ucirepo(id=45)

. How to Run
Open the Jupyter Notebook capstone_heart_disease.ipynb.

Run all cells from top to bottom. No manual intervention is needed.

The notebook performs:

Data preprocessing

Exploratory Data Analysis (EDA)

Dimensionality reduction (PCA, t-SNE, UMAP)

Model training (Logistic Regression, KNN, Random Forest, Gradient Boosting)

Hyperparameter tuning via RandomizedSearchCV

Model comparison and accuracy evaluation

. Results Summary
Best Model: K-Nearest Neighbors (KNN)

Accuracy: Highest among evaluated models after tuning

Dimensionality Reduction: Used for visual exploration of feature space








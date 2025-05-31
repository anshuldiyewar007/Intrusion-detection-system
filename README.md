Project Overview
This project implements an Intrusion Detection System using machine learning techniques to classify network traffic as normal or anomalous. The system is trained on network traffic data and evaluates three different machine learning models: Logistic Regression, K-Nearest Neighbors (KNN), and Decision Trees.

Features
Data preprocessing and feature selection

Three machine learning models for intrusion detection

Performance evaluation including accuracy, precision, recall, and F1-score

ROC curve analysis for model comparison

Hyperparameter optimization using Optuna

Requirements
Python 3.x

Required Python packages:

numpy

pandas

seaborn

matplotlib

scikit-learn

optuna

xgboost

lightgbm

tabulate

Installation
Clone the repository:

bash
git clone [repository-url]
cd intrusion-detection-system
Install the required packages:

bash
pip install -r requirements.txt
Dataset
The project uses the NSL-KDD dataset for training and testing. The dataset should be placed in the specified Google Drive path or can be modified to use local paths.

Usage
Run the Jupyter notebook CS.ipynb which contains all the code:

bash
jupyter notebook CS.ipynb
The notebook performs the following steps:

Data loading and exploration

Data preprocessing and feature selection

Model training and evaluation

Performance comparison and visualization

Models Implemented
Logistic Regression

Accuracy: 92%

AUC: 0.94

K-Nearest Neighbors (KNN)

Accuracy: 98%

AUC: 0.98

Decision Tree

Accuracy: 99%

AUC: 0.99

Results
The Decision Tree model performed best with 99% accuracy, followed by KNN at 98%, and Logistic Regression at 92%. ROC curve analysis shows that all models perform significantly better than random guessing.

Future Work
Implement more advanced models like Random Forest or Neural Networks

Add real-time detection capabilities

Improve feature engineering

Implement ensemble methods

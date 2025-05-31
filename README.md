# Intrusion Detection System - Machine Learning Models

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.2+-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

This repository contains code for building and evaluating machine learning models for intrusion detection using network traffic data.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)


## Overview

The project focuses on detecting network intrusions (anomalies) using three different machine learning models:
1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree

The implementation includes:
- Data preprocessing
- Feature selection
- Model training and evaluation
- Performance visualization

## Dataset

The dataset contains network traffic features with binary classes ("normal" or "anomaly").

**Key characteristics:**
- Training data shape: (125,973 × 42)
- Test data shape: (22,544 × 41)
- No missing values
- Class distribution:
  - Normal: [count]
  - Anomaly: [count]

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/intrusion-detection.git
cd intrusion-detection
Install requirements:

bash
pip install -r requirements.txt
Requirements:

Python 3.8+




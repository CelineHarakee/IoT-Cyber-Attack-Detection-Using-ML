# Intelligent Intrusion Detection System (IDS) for Internet of Things (IoT) Networks Using Machine Learning
Leveraging machine learning, this project focuses on identifying network intrusions and malicious behavior within IoT environments. Utilizing the CIC-IoT2023 dataset, it incorporates data preprocessing, feature engineering, class balancing, and model training to achieve accurate and real-time prediction of threats in IoT deployments.


---

## Table of Contents
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Overview](#overview)
- [Installation](#installation)
- [How to Run](#how-to-run)
- [Features](#features)
- [Results](#results)
- [Team](#team)

---
## Project Structure
- `notebook/`: Jupyter Notebook for data preprocessing, feature engineering, and model training
- `datasets/`: CSV files from CIC-IoT 2023 dataset
- `requirements.txt`: Python libraries required
- `README.md`: Project documentation
---
## Dataset

We used the [CIC-IoT2023 Dataset](https://www.unb.ca/cic/datasets/iotdataset-2023.html) which contains both benign and malicious IoT traffic. The dataset includes attacks like DDoS, Injection, Reconnaissance, etc.

---
## Overview
### Phase 1: Data Preprocessing & Feature Engineering

- Cleaned missing values (handled NaNs and infinite values)
- Feature normalization using **Z-score (StandardScaler)**
- Balanced dataset using **SMOTE** to fix class imbalance
- Reduced dimensionality using **PCA** (Principal Component Analysis)

### Tools Used:
- `pandas`, `numpy`
- `scikit-learn`
- `imbalanced-learn` (SMOTE)
- `matplotlib`, `seaborn` (for optional EDA/visualization)
- `sklearn.decomposition` (PCA)
- `PyCaret` (optional end-to-end pipeline support)

### Phase 2: ML Modeling & Evaluation

### Supervised Models Trained:
- Random Forest
- Support Vector Machine (SVM)
- XGBoost
- Multilayer Perceptron (MLP - Neural Network)
- Convolutional Neural Network (CNN)

### Tools Used:
- `scikit-learn`
- `XGBoost`, `LightGBM`
- `TensorFlow` / `Keras`

---
## Installation
1. Clone the repository:
``` bash
git clone https://github.com/CelineHarakee/IoT-Cyber-Attack-Detection-Using-ML.git
cd IoT-Cyber-Attack-Detection-Using-ML
```
2. Install dependencies:
``` bash
pip install -r requirements.txt
```
---
## How to Run
Run the notebook step by step: 
``` bash
notebooks/FINAL FILE NAME.ipynb 
```
</br> 
This notebook includes:

- Data loading
- Data cleaning
- Feature engineering
- Label encoding
- Feature scaling
- SMOTE for class balancing

  
--- 
## Features
---
## Results
---
## Team
- [Celine Al Harake](https://github.com/CelineHarakee)
- [Layal Canoe](https://github.com/layalcanoe)
- [Dana Al Rijjal](https://github.com/daaalrijjal)
- [Jouri Al Daghma](https://github.com/Jourialdagh)

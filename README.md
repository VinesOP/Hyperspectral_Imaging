# Hyperspectral_Imaging
https://colab.research.google.com/drive/1Og-qkkWcSCUQFk3pKPmqIRKweh5PqcIX?usp=sharing

## Overview
This repository contains a machine learning solution to predict Deoxynivalenol (DON) concentration in corn samples using hyperspectral imaging data. The solution uses PCA for dimensionality reduction and a Random Forest Regressor, implemented in Google Colab.

## Repository Structure
- `Hyperspectral_Imaging_Assignment.ipynb`: Jupyter Notebook with the complete code.
- `TASK-ML-INTERN.csv`: Input dataset (not included; must be uploaded).
- `rf_model.pkl`: Saved Random Forest model.
- `scaler.pkl`: Saved StandardScaler object.
- `pca.pkl`: Saved PCA object.
- `report.md`: Short report summarizing the solution.
- `README.md`: This file.

## Prerequisites
- **Environment**: Google Colab.
- **Dependencies**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `joblib` (pre-installed in Colab).
- **Dataset**: `TASK-ML-INTERN.csv`.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/<VinesOP>/<Hyperspectral_imaging>.git
Upload Hyperspectral_Imaging_Assignment.ipynb and TASK-ML-INTERN.csv to My Drive > Hyperspectral_Imaging_Assignment in Google Drive.
Open the notebook in Google Colab: File > Open Notebook > Google Drive.
Running the Code
Mount Google Drive:
python

Collapse

Wrap

Copy
from google.colab import drive
drive.mount('/content/drive')
Run all cells. If TASK-ML-INTERN.csv is not in Drive, upload it when prompted.
Outputs are saved to My Drive > Hyperspectral_Imaging_Assignment.
Outputs
Plots: Reflectance, heatmap, PCA variance, PCA scatter, prediction scatter.
Metrics: MAE, RMSE, R² (printed in the notebook).
Files: rf_model.pkl, scaler.pkl, pca.pkl, report.md, README.md.

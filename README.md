# ML-Assignment
# Machine Learning Pipeline for Predicting Mycotoxin Levels in Corn Samples

This project implements a machine learning pipeline to predict mycotoxin levels (DON concentration) in corn samples using hyperspectral imaging data. The pipeline includes data preprocessing, model training, and evaluation.

## Project Overview
The goal of this project is to develop a machine learning pipeline to predict mycotoxin levels (DON concentration) in corn samples using hyperspectral imaging data. The pipeline includes:
- Data preprocessing (handling missing values, normalization, and visualization).
- Model training (using a neural network and hyperparameter tuning).
- Model evaluation (using regression metrics like MAE, RMSE, and R²).
## Dataset Description
The dataset contains spectral reflectance data of corn samples across multiple wavelength bands. Each row represents a corn sample, and the features are the reflectance values at different wavelengths. The target variable is the DON concentration (a continuous numerical value).
- **Features**: Spectral reflectance values measured at various wavelengths.
- **Samples**: Each row represents an individual corn sample.
- **Target**: DON concentration (continuous numerical value).

## Tasks and Implementation
The project is divided into the following tasks:

### 1. Data Exploration and Preprocessing
- Load and inspect the dataset.
- Handle missing values using mean imputation.
- Normalize the spectral data using `StandardScaler`.
- Visualize the data using line plots and heatmaps.

### 2. Model Training
- Split the data into training (80%) and testing (20%) sets.
- Train a neural network using TensorFlow/Keras.
- Perform hyperparameter tuning using Optuna.

### 3. Model Evaluation
- Evaluate the model using regression metrics (MAE, RMSE, R²).
- Visualize predictions and residuals.
- Use SHAP or LIME for interpretability (optional).

---

## Installation and Setup
To set up the project, follow these steps:

1. **Clone the repository**: https://github.com/harshhhxd/ML-Assignment
   ```bash
   Create a virtual environment:
2. install your dependencies and libraries
   **python -m venv .venv
source .venv/bin/activate**  # On Windows, use `.venv\Scripts\activate`
**pip install -r requirements.txt**

# COPD Exacerbation Risk Prediction

## Authors
- Raquel Pérez Roa
- Marcos Cortizo Albiñana

## Project Overview
This project was developed as part of the Biomedical Engineering Degree at the University of Vigo.
The objective was to develop and evaluate machine learning models capable of predicting the risk of exacerbation in patients with Chronic Obstructive Pulmonary Disease (COPD) using clinical data.
The project follows a complete machine learning workflow, including data preprocessing, model training, model comparison, and external validation.

## Workflow

### 1. Data Preprocessing
- Data exploration and cleaning
- Missing value treatment
- Outlier analysis and removal
- Feature preparation and encoding
- Dataset preparation for machine learning

### 2. Machine Learning Models
Several supervised learning algorithms were trained and evaluated:
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Logistic Regression

### 3. Model Selection and Validation
The models were compared using performance metrics obtained during validation.
Random Forest was selected as the final model due to its overall predictive performance.
An external validation dataset was used to evaluate the generalization capability of the selected model.

## Repository Contents
- `1Preprocesado.ipynb` – Data preprocessing workflow
- `2AlgoritmosML.ipynb` – Model training and comparison
- `3Validación.ipynb` – External validation process
- `random_forest_media_moda_sin_outliers.pkl` – Trained Random Forest model
  
## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Google Colab
- Jupyter Notebook

---

## Academic Use Notice
This repository is intended to showcase the methodology, implementation, and machine learning workflow developed during the project.
Only a small evaluation sample and the corresponding prediction results are included for demonstration purposes.
The complete training dataset is not distributed in this repository.

---

University of Vigo  
Bachelor's Degree in Biomedical Engineering

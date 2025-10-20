# Machine Learning Exercises – Regression & Classification

This repository contains exercises applying machine learning to real-world datasets, demonstrating complete workflows from preprocessing to evaluation and visualization.

---

## 📂 Folder Structure

Exercise 1 – Regression Task
|
01-NASA-NEO-Kinetic-Energy-Prediction
| 02-Multi-Sensory-Synchronization-Delay

Exercise 2 – Classification Task
|
01-Exoplanet-Detection
| 02-Protein-Structure

---

## 🧮 Exercise 1 – Regression Tasks

### 1. NASA NEO Kinetic Energy Prediction
- **Objective:** Predict kinetic energy of near-Earth objects using orbital and physical features.  
- **Dataset:** NASA NEO database  
- **Model:** Random Forest Regression 
- **Highlights:**  
  - Preprocessing: Missing value handling and feature scaling  
  - Evaluation: RMSE, MAE, R²  
  - Demonstrates predictive modeling for continuous scientific data

### 2. Multi-Sensory Synchronization Delay
- **Objective:** Predict synchronization delays in multisensory experiments  
- **Dataset:** Experimental sensory data  
- **Model:**  Decision Tree Regressor  
- **Highlights:**  
  - Preprocessing: Standardization, encoding categorical features  
  - Evaluation: RMSE, MAE, R²  
  - Provides insights into modeling human sensory perception data

---

## 🧬 Exercise 2 – Classification Tasks

### 1. Exoplanet Detection
- **Objective:** Classify exoplanets into habitability categories  
- **Dataset:** NASA Kepler Exoplanet Archive  
- **Target Classes:**  
  - `0` – Non-Habitable  
  - `1` – Potentially Habitable  
  - `2` – False Positive / Candidate  
- **Model:** Support Vector Machine (SVM) with RBF kernel  
- **Highlights:**  
  - Derived target variable using astrophysical criteria  
  - Stratified splitting and class weighting for imbalance  
  - Evaluation: Accuracy, Precision, Recall, F1-score, Confusion Matrix, ROC & Precision-Recall curves (2D & 3D)

### 2. Protein Structure Prediction
- **Objective:** Predict secondary structure of protein fragments  
- **Dataset:** SST-3 (numeric features)  
- **Target Classes:**  
  - `0` – Coil  
  - `1` – Helix  
  - `2` – Sheet  
- **Model:** k-Nearest Neighbors (k-NN)  
- **Highlights:**  
  - Preprocessing: Missing value imputation, feature scaling  
  - Interactive 3D PCA, ROC, and Precision-Recall visualizations  
  - Analysis of misclassification patterns and class-wise performance

---

## ⚙️ Common Workflow

1. **Data Preprocessing:** Handle missing values, scale features, encode labels  
2. **Model Training:** Regression or classification models depending on task  
3. **Evaluation:**  
   - Regression: RMSE, MAE, R²  
   - Classification: Accuracy, Precision, Recall, F1-score, Confusion Matrix  
4. **Visualization:** 2D and 3D plots for interpretation

---

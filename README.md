# UEFA Football Match Outcome Prediction

As a communty college student, I was fortunate enough to find a resaerch opportunity at California State University, Fullerton and do volunteer resaerch in data science. As I was brainstorming ideas for projects, the Euros were just starting. I used this opportunity to tackle on a resaerch project on predictive modeling. 

This project predicts the outcomes of UEFA European Championship (Euros) football matches using historical match data. The goal is to classify each match result as a **home win**, **draw**, or **away win**.

In addition to Logistic Regression and XGBoost, I also experimented with Decision Trees, Random Forests, and a Neural Network built with TensorFlow/Keras.  
> **Note:** Due to file corruption during upload, the full implementations of these additional models were not preserved in the current version of the repository.

---

## Project Workflow

### 1. Data Acquisition & Cleaning
- Collected and preprocessed historical match data  
- Engineered features including dynamic team Elo ratings

### 2. Modeling
- Trained and evaluated two classification models:
  - **Logistic Regression**
  - **XGBoost Classifier**
- Experimented with:
  - **Decision Trees**
  - **Random Forest Classifier**
  - **Neural Network (TensorFlow/Keras)**

### 3. Evaluation
- Assessed performance using:
  - Classification reports
  - Confusion matrices

---

## 📁 File Overview

- **`EurosPrediction.ipynb`**  
  Contains all code for:
  - Data processing  
  - Feature engineering  
  - Model training and evaluation  
   _To understand and run the project, please refer to this notebook._

- **`results.csv`**  
  Includes model predictions and performance metrics

---

## Environment & Dependencies

### Platform
- JupyterLab

### Python Version
- 3.8+

### Required Packages
- `pandas`  
- `numpy`  
- `scikit-learn`  
- `xgboost`  
- `matplotlib`  
- `seaborn`

---

## ✅ How to Use

1. Clone the repository.
2. Open `EurosPrediction.ipynb` in JupyterLab.
3. Run the notebook to explore the data, train models, and view predictions and evaluations.


# 🧠 Titanic Survival Prediction

A complete end-to-end machine learning pipeline for solving a classification problem using Python and scikit-learn. This project covers data preprocessing, model training, evaluation, and optimization.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0%2B-yellow.svg)

## 📁 Dataset

The dataset used is `train.csv`, consisting of both numerical and categorical features. The target is a classification label predicting a specific outcome based on input features.

## 📊 Project Workflow

### 1. Data Exploration
- Loaded dataset using `pandas`.
- Inspected dataset structure with `.info()` and `.describe()`.

### 2. Data Preprocessing
- **Missing Values**:
- **Categorical Encoding**:
- **Feature Dropping**:

### 3. Pipeline Construction
A scikit-learn pipeline was used to automate the workflow:
- `SimpleImputer` for missing values
- `OneHotEncoder` for categorical features
- `StandardScaler` for numerical scaling
- `RandomForestClassifier` for classification

### 4. Model Training and Evaluation
- Trained a `RandomForestClassifier`.
- Hyperparameter tuning using `GridSearchCV`.
- Evaluated with accuracy score.

## 📈 Results

The model achieved solid performance using the default pipeline. Accuracy was used as the primary evaluation metric, and the process is fully reproducible.

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

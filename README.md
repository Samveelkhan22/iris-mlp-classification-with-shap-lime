# Iris Flower Classification using MLP with SHAP & LIME

## 📌 Project Overview

This project demonstrates a complete **machine learning workflow** on the classic **Iris dataset**, focusing on building a neural network model and explaining its predictions using modern **Explainable AI (XAI)** techniques.

The project covers:
- Data exploration and preprocessing  
- Training a **Multi-Layer Perceptron (MLP) classifier**
- Model evaluation
- Model explainability using **SHAP** and **LIME**

---

## 📊 Dataset Description

The **Iris dataset** consists of **150 samples** from three flower species:

- Iris Setosa  
- Iris Versicolor  
- Iris Virginica  

Each sample includes four numerical features:
- Sepal length  
- Sepal width  
- Petal length  
- Petal width  

---

## 🧠 Project Workflow

### 1️⃣ Data Loading & Exploration
- Loaded the Iris dataset using `sklearn.datasets`
- Converted data into a Pandas DataFrame
- Explored feature distributions and target labels

### 2️⃣ Feature & Target Separation
- Separated independent variables (`X`)
- Isolated the target variable (`y`)
- Verified dataset dimensions

### 3️⃣ Data Preprocessing
- Checked for categorical variables
- Generated a correlation matrix
- Ensured data readiness for model training

### 4️⃣ Train–Test Split
- Split data into **80% training** and **20% testing**
- Used a fixed random state for reproducibility

### 5️⃣ Model Training
- Trained a **Multi-Layer Perceptron (MLP) Classifier**
- Fit the model on training data
- Generated predictions on test data

### 6️⃣ Sample Prediction
- Selected a random test sample
- Predicted the flower species using the trained model

### 7️⃣ Model Explainability (XAI)

#### 🔍 SHAP (SHapley Additive exPlanations)
- Used `KernelExplainer`
- Explained feature contributions to predictions
- Generated SHAP summary plots for global interpretability

#### 🔍 LIME (Local Interpretable Model-agnostic Explanations)
- Explained individual predictions
- Identified feature influence at the instance level
- Provided local model interpretation

### 8️⃣ SHAP vs LIME
- **SHAP** provides consistent global and local explanations
- **LIME** offers fast, local, instance-based explanations
- Both techniques help improve trust in black-box models

---

## 🛠️ Technologies Used

- Python  
- Pandas & NumPy  
- Scikit-learn  
- Matplotlib & Seaborn  
- SHAP  
- LIME  



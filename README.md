# 🧠 Breast Cancer Classification with Machine Learning  
### A Data Science Project using Python, Scikit-Learn, TensorFlow, and Exploratory Data Analysis

This repository contains a complete end-to-end machine learning workflow for **breast cancer classification**, including data exploration, preprocessing, model training, evaluation, and insights.  
The goal is to build a robust model capable of predicting whether a tumor is **benign or malignant** based on clinical features.

---

## 📌 Project Overview

This notebook walks through all the key steps of a professional ML pipeline:

- ✔ Data loading and inspection  
- ✔ Exploratory Data Analysis (EDA)  
- ✔ Data cleaning and preprocessing  
- ✔ Feature engineering  
- ✔ Model training using classical ML algorithms  
- ✔ Optional deep learning approach (TensorFlow)  
- ✔ Model evaluation with accuracy, precision, recall, F1-score, confusion matrix  
- ✔ Final conclusions and next steps  

The project uses the **Wisconsin Breast Cancer Dataset**, widely used in research and medical ML applications.

---

## 🛠️ Technologies Used

| Category | Tools |
|---------|-------|
| Language | Python |
| Data Handling | pandas, numpy |
| Visualization | matplotlib, seaborn |
| ML Models | scikit-learn |
| Deep Learning (Optional) | TensorFlow / Keras |
| Model Evaluation | scikit-learn metrics |

---

## 📊 Dataset Description

The dataset contains numerical features extracted from breast mass cell nuclei.  
Each row represents a clinical case with attributes such as:

- Radius  
- Texture  
- Perimeter  
- Smoothness  
- Compactness  
- Symmetry  
- Fractal dimension  
- …and others.

**Target variable:**  
- `0` → Malignant  
- `1` → Benign  

---

## 🚀 Workflow Summary

### **1. Exploratory Data Analysis (EDA)**
- Inspecting dataset shape and structure  
- Detecting missing values  
- Visualizing distributions  
- Correlation heatmap  
- Checking class balance  

### **2. Data Preprocessing**
- Scaling features with StandardScaler  
- Splitting into train/test  
- Optional PCA or feature selection  

### **3. Model Training**
Models trained and compared:

- Logistic Regression  
- Random Forest  
- Support Vector Machine (SVM)  
- KNN  
- Gradient Boosting  
- Optional: Deep Neural Networks (TensorFlow)

### **4. Model Evaluation**
- Confusion Matrix  
- Accuracy  
- Precision & Recall  
- F1-score  
- ROC Curve  
- Feature Importance (if applicable)

---

## 🏆 Results

The top-performing models typically reach:

- **Accuracy:** 95%–99%  
- **High precision/recall**, crucial for detecting malignant tumors  
- Minimal **false negatives**, ideal in medical diagnostics  

Your exact metric outputs are visible inside the notebook.

---

## ▶ How to Run the Project

### **1. Clone the repository**
```bash
git clone https://github.com/your-username/breast-cancer-classification.git
cd breast-cancer-classification
```
### **2. Install dependencies**
```bash
pip install -r requirements.txt
```
### **3. Start Jupyter Notebook**
```bash
jupyter notebook
```
### **4. Open the project**
```bash
breast-cancer-classification.ipynb
```



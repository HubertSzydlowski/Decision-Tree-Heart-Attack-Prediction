# Decision Tree: Heart Attack Prediction

## **🧑‍💻 Author**

### Hubert Szydłowski

---

## 🎯 Project Goal

The goal of this project is to create an artificial intelligence system using decision tree and random forest algorithms. The development process includes data acquisition, exploratory data analysis, data transformation and preparation for modeling, model training, and evaluation of prediction performance using appropriate metrics.

---

## 📂 Dataset Description

### Link: [Heart Disease Dataset on Kaggle](https://www.kaggle.com/datasets/mfarhaannazirkhan/heart-dataset/data)

### Dataset for Heart Disease Prediction

This dataset contains 1,888 records merged from five publicly available heart disease datasets. It includes 14 features that are crucial for predicting the risk of heart attack and stroke, covering both medical and demographic factors.

---

### 🧾 Features

- **age**: age of the patient (numerical value)
- **sex**: gender of the patient (values: 1 = male, 0 = female)
- **cp**: type of chest pain  
  - 0 = typical angina, 1 = atypical angina, 2 = non-anginal pain, 3 = asymptomatic
- **trestbps**: resting blood pressure (numerical value in mm Hg)
- **chol**: serum cholesterol level (numerical value in mg/dl)
- **fbs**: fasting blood sugar > 120 mg/dl? (values: 1 = yes, 0 = no)
- **restecg**: resting electrocardiographic results  
  - 0 = normal, 1 = ST-T wave abnormality, 2 = left ventricular hypertrophy
- **thalach**: maximum heart rate achieved (numerical value)
- **exang**: exercise-induced angina (values: 1 = yes, 0 = no)
- **oldpeak**: ST depression induced by exercise relative to rest (numerical value)
- **slope**: slope of the peak ST segment during exercise  
  - 0 = upsloping, 1 = flat, 2 = downsloping
- **ca**: number of major vessels colored by fluoroscopy (values: 0, 1, 2, 3)
- **thal**: types of thalassemia  
  - 1 = normal, 2 = fixed defect, 3 = reversible defect
- **target**: target variable – risk of heart attack  
  - 1 = higher risk of heart attack, 0 = lower risk of heart attack

---

### 📊 Dataset Details

The dataset is a combination of five publicly available heart disease datasets, totaling 1,888 records. Merging these sources provides a strong foundation for training machine learning models to predict heart attack risk.

---

### 💾 Datasets Used:

1. **Heart Attack Analysis & Prediction Dataset**
   - Number of records: 304  
   - Source: Rahman, 2021

2. **Heart Disease Dataset**
   - Number of records: 1,026  
   - Source: Lapp, 2019

3. **Heart Attack Prediction (Dataset 3)**
   - Number of records: 295  
   - Source: Damarla, 2020

4. **Heart Attack Prediction (Dataset 4)**
   - Number of records: 271  
   - Source: Anand, 2018

5. **Heart CSV Dataset**
   - Number of records: 290  
   - Source: Nandal, 2022

---

## 🛠 Techniques Used

During the implementation of this project, the following techniques were applied:

- Preliminary data preparation (data cleaning, feature transformation)
- Feature engineering (selection of the most relevant features)
- Model training using decision tree and random forest algorithms
- Hyperparameter tuning with RandomizedSearchCV
- Cross-validation
- Evaluation of results on both training and test datasets
- Feature importance analysis

---

## 🧠 Conclusions

Using the techniques above, I was able to achieve good results on both datasets (training ang test). The project involved initial data preparation, feature engineering, and parameter optimization using RandomizedSearchCV. Additionally, I performed cross-validation, evaluated results on both datasets, and conducted feature importance analysis.

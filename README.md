# 🎬 IMDb Data Mining Project  

**Machine Learning / Explainable AI / Time Series Analysis**

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?logo=scikit-learn)](https://scikit-learn.org/)
[![LightGBM](https://img.shields.io/badge/LightGBM-boosting-lightgreen?logo=lightgbm)](https://lightgbm.readthedocs.io/)
[![XAI](https://img.shields.io/badge/XAI-Explainable%20AI-purple)](#)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

---

### 🧠 Overview  
A complete **data mining pipeline** on the IMDb dataset, from preprocessing and anomaly detection to advanced classification, explainability, and time-series modeling.  
The project explores both **tabular** and **temporal** perspectives of film data, revealing patterns in ratings, genres, and audience behavior.

---

### 📚 Main Topics

#### 🔹 Data Preprocessing & Outlier Detection  
Feature engineering, normalization, and anomaly detection using **PCA**, **t-SNE**, **Isolation Forest**, **LMDD**, **HBOS**, and **DBSCAN**

#### 🔹 Imbalanced Learning  
Binary classification tasks addressing ****rare class imbalance****
- **Decision Trees**
- **Edited Nearest Neighbours (ENN)**  
- **SMOTE**
- **Tomek Links**
- **ADASYN**

#### 🔹 Advanced Classification  
Multiclass IMDb ****rating prediction**** using a full spectrum of machine learning models.
- **Logistic Regression**  
- **Support Vector Machine**
- **Multilayer Perceptron**
- **Bagging Classifier**  
- **Random Forest**  
- **AdaBoost**
- **Gradient Boosting**  
- **Histogram-Based Gradient Boosting**  
- **XGBoost**  
- **LightGBM**  
- **CatBoost**  

#### 🔹 Explainable AI (XAI)  
Model interpretation through **black-box explainability** tools
- **SHAP**
- **LIME**
- **LORE**
- **Counterfactual Explainer**

#### 🔹 Regression  
Continuous rating prediction
- **Random Forest Regressor**  
- **AdaBoost Regressor**

#### 🔹 Time Series Analysis  
Analysis of **daily box-office revenues**
- frequency-domain analysis (**FFT**)  
- **Motif** & **discord discovery**  
- **Outlier detection**
- **Clustering** with **DTW**, **PCA**, **TSFRESH**

#### 🔹 Time Series Classification  
Predicting **rating categories** from revenue trajectories

- **k-Nearest Neighbors**
- **k-Nearest Neighbors** with **Dynamic Time Warping**
- **Random Forest**  
- **Random Forest** + **Catch22**
- **Proximity Tree**
- **Canonical Interval Forest**
- **BOSSEnsemble**
- **SFAFast** + **k-NN**
- **Shapelet Transform Classifier**  
- **Random Interval Spectral Ensemble**
- **Multilayer Perceptron**
- **RocketClassifier**
- **MiniRocket**  
- **InceptionTime**  
- **ResNet**  
- **CNN**
- **RNN**

#### 🔹 Sequential Pattern Mining  
Discovering **frequent sequential behaviors** and rating evolution patterns across movie data

---

### 🎯 Goal  
To extract actionable insights and predictive structures from the IMDb dataset using **Machine Learning** and **Explainable AI**, combining statistical rigor with transparent interpretability.

---

### 🧰 Tech Stack  
- **Python** (NumPy, Pandas, Matplotlib, scikit-learn, LightGBM, XGBoost, CatBoost)  
- **XAI Libraries:** SHAP, LIME, LORE, FAT-Forensics  
- **Time Series Libraries:** tslearn, TSFRESH, sktime, aeon  
- **Visualization:** Matplotlib, Seaborn, t-SNE, PCA  

---

### 👨‍💻 Authors  
- **Alessandro Falcetta**  
- **Riccardo Roselli**

---

📜 *Master’s in Data Science & Business Informatics – University of Pisa (A.Y. 2024–2025)*

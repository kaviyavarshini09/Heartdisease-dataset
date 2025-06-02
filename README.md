# Heartdisease-dataset
# 🧠 Task 5: Decision Trees and Random Forests - AI & ML Internship

## 📌 Objective
To explore and implement tree-based models such as **Decision Tree Classifier** and **Random Forest Classifier** on the Heart Disease dataset. The goal is to learn model training, visualization, evaluation, and feature importance interpretation.

---

## 🗃️ Dataset
**Heart Disease Dataset** from Kaggle:  
🔗 https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

---

## 🛠️ Tools & Libraries Used
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Graphviz (for decision tree visualization)

---

## 🚀 Steps Performed

### ✅ Data Preprocessing
- Loaded the dataset and explored features.
- Separated features (X) and target (y).
- Scaled features using `StandardScaler`.

### ✅ Model Training
- Trained a **Decision Tree Classifier** with 'max_depth=4'.
- Trained a **Random Forest Classifier** with 100 estimators.

### ✅ Visualization
- Visualized the trained Decision Tree using 'plot_tree()'.
- Plotted **feature importances** using Random Forest output.

### ✅ Evaluation
- Calculated accuracy for both models.
- Compared performance of Decision Tree vs Random Forest.
- Used 5-fold **Cross-Validation** for model stability.

---

## 📊 Results

| Model              | Accuracy (Test) |
|--------------------|-----------------|
| Decision Tree      |  **~83%**       |
| Random Forest      |  **~88%**       |
| Cross-Val (Random) |  **~85–90%**    |

---

## 🔍 Key Insights
- **Random Forest** performed better than a single decision tree.
- Limiting 'max_depth' helped reduce overfitting.
- Top predictive features were: 'cp', 'thal', and 'ca'.
- Ensemble methods like bagging increase model stability and accuracy.

---

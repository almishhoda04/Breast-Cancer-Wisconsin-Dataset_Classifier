# 🩺 Breast Cancer Prediction using Logistic Regression

This project implements a machine learning classification model using **Logistic Regression** to predict whether a tumor is **benign** or **malignant** based on medical diagnostic features.  
The project is built using the **Breast Cancer Wisconsin dataset** and evaluates model performance using various classification metrics and visualizations.

# 📊 Dataset Overview

- **Dataset Source:** [https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data?select=data.csv]
- **Number of Samples:** 569  
- **Features:** 30 numeric features 
- **Target Classes:**
  - `0` → Benign  
  - `1` → Malignant  

# 🚀 Project Workflow

1. **Import Libraries and Load Dataset**
2. **Exploratory Data Analysis (EDA)**
3. **Train-Test Split (80-20)**
4. **Feature Scaling using StandardScaler**
5. **Train Logistic Regression Model**
6. **Model Evaluation:**
   - Confusion Matrix
   - ROC Curve & AUC Score
   - Accuracy
   - Precision
   - Recall
   - F1-Score
7. **Threshold Tuning**
8. **Sigmoid Function Explanation & Visualization**

## 📊 Key Visualizations

- 📉 Confusion Matrix Heatmaps (with default and tuned thresholds)
- 📈 ROC Curve with AUC Score
- 📉 Sigmoid Function Graph (showing how Logistic Regression converts linear inputs into probabilities)

# 📦 Libraries and Tools Used

- Python 3.12
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn

# 📖 Learnings and Highlights

✅ Built an end-to-end classification workflow using Logistic Regression  
✅ Performed EDA, feature scaling, and train-test split  
✅ Applied performance evaluation using multiple classification metrics  
✅ Tuned classification threshold and observed its effect on predictions  
✅ Visualized the Sigmoid function and ROC Curve for better interpretability  

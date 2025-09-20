# 💳 Credit Card Fraud Detection Project

## 📌 Overview
This project applies **supervised** (Artificial Neural Networks) and **unsupervised** (PCA, t-SNE, K-Means) learning techniques to detect fraudulent credit card transactions.  
The dataset is highly imbalanced, so **SMOTE** is used for balancing.  
The goal is to build a model that can separate **fraudulent** from **genuine** transactions effectively.

---

## 🚀 Steps
1. **Load dataset** from Kaggle (credit card transactions).  
2. **Preprocess data**  
   - Scale `Amount` and `Time`.  
   - Handle class imbalance using **SMOTE**.  
3. **Dimensionality Reduction**  
   - Apply **PCA** (Week-4 concept).  
   - Use **t-SNE** for visualization.  
4. **Train-Test Split** with stratification.  
5. **Model Training**  
   - ANN with **Dropout** & **EarlyStopping**.  
6. **Evaluation**  
   - Classification Report  
   - Confusion Matrix  
   - ROC-AUC Score  
7. **Visualization**  
   - Accuracy & Loss curves  
   - Confusion matrix heatmap  
   - t-SNE scatter plots  
8. **Unsupervised Clustering**  
   - Apply **K-Means** to compare with actual labels.

---

## 🛠 Requirements
- Python 3  
- pandas, numpy  
- scikit-learn  
- imbalanced-learn (SMOTE)  
- matplotlib, seaborn  
- tensorflow / keras  

Install dependencies:
```bash
pip install -r requirements.txt


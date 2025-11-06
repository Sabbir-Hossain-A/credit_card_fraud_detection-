# 💳 Credit Card Fraud Detection using Deep Learning

A comprehensive **Deep Learning-based pipeline** to detect fraudulent credit card transactions using the famous [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).  
This project demonstrates advanced preprocessing, feature engineering, imbalance handling, and multiple neural architectures — all in one Colab-ready notebook.

---

## 🚀 Features

✅ Step-by-step Deep Learning workflow  
✅ Handles extreme class imbalance using **SMOTE**  
✅ Outlier handling & Feature scaling  
✅ Exploratory Data Analysis (EDA) with visualizations  
✅ Implements 4 individual DL models + 1 hybrid model  
✅ ROC-AUC curve comparison & performance summary  

---

## 🧩 Dataset
**Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

- **Total transactions:** 284,807  
- **Fraudulent transactions:** 492 (≈0.172%)  
- **Features:** 30 numerical (V1–V28 from PCA + Amount, Time)  
- **Target:** `Class` → 0 = Legit, 1 = Fraud  

---

## 🧠 Models Implemented

| # | Model | Description |
|---|--------|-------------|
| 1 | **MLP** | Baseline Deep Neural Network |
| 2 | **MLP + Focal Loss** | Improved loss function for imbalanced data |
| 3 | **Autoencoder** | Unsupervised anomaly detection |
| 4 | **1D CNN** | Convolution-based fraud pattern detection |
| 5 | **Hybrid (AE + MLP)** | Combines reconstruction error with supervised learning |

---

## ⚙️ Steps Performed
1. **Data Loading & Description**  
2. **Outlier Handling (IQR method)**  
3. **Exploratory Data Analysis (EDA)**  
4. **Feature Engineering** (rolling mean, scaling)  
5. **Data Scaling** using `RobustScaler` and `StandardScaler`  
6. **Imbalance Handling** using `SMOTE`  
7. **Model Training** (4 DL models + 1 Hybrid)  
8. **Evaluation Metrics:**  
   - Confusion Matrix  
   - Classification Report  
   - ROC-AUC Curve Comparison  
   - Precision, Recall, F1-score summary  

--


---

## 💡 Future Improvements
- Implement LSTM or Transformer-based sequence models  
- Integrate Explainable AI (XAI) methods for interpretability  
- Deploy as a Flask web app with real-time inference  

---

## 📚 References
- Dal Pozzolo, A., et al. “Calibrating Probability with Undersampling for Unbalanced Classification.”  
- Kaggle Dataset: [mlg-ulb/creditcardfraud](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

---

## 🧑‍💻 Author
**Md. Sabbir Hossain**  
Student, Daffodil International University  
Research interest: *Machine Learning | Deep Learning | NLP | AI Security*

---



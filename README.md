# 📊 Machine Learning: Classification & Regression Tasks  

This project is a **hands-on notebook** that explores multiple supervised learning problems using **Logistic Regression** and **k-Nearest Neighbors (k-NN)**.  
It covers **binary, multiclass classification, and regression tasks** — with proper preprocessing, model evaluation, and cross-validation for hyperparameter tuning.  

---

## 🎯 Motivation  
Machine Learning is not just about training a model — it’s about applying the right algorithm to the right problem.  
This notebook demonstrates **how the same ML pipeline** can be adapted for:  
- Email spam filtering 📨  
- Customer churn prediction 📉  
- Medical diagnosis 🏥  
- Flower species classification 🌸  
- Price prediction for rentals 🏡  

---

## 🛠 Workflow  

1. **Data Preprocessing**  
   - Cleaning & feature selection  
   - Standardization with `StandardScaler`  

2. **Model Training**  
   - Logistic Regression (binary & multiclass)  
   - k-NN (classification & regression)  

3. **Hyperparameter Tuning**  
   - 5-Fold Cross Validation for selecting the best `k` in k-NN  

4. **Evaluation**  
   - Classification: Accuracy, Precision, Recall, F1, ROC-AUC  
   - Regression: RMSE, R² Score  

---

## 📚 Tasks Overview  

### 1. 📧 Email Spam Classification  
- **Goal**: Classify emails as *spam* or *not spam*  
- **Model**: Logistic Regression  
- **Evaluation**: Accuracy, Precision, Recall, F1, ROC-AUC  

---

### 2. 📉 Customer Churn Prediction  
- **Goal**: Predict whether a customer will leave a company  
- **Model**: Logistic Regression  
- **Evaluation**: Accuracy, Precision, Recall, F1, ROC-AUC  

---

### 3. 🏥 Disease Stage Classification  
- **Goal**: Predict the stage of a disease (multiclass)  
- **Model**: Logistic Regression (multiclass mode)  
- **Evaluation**: Macro-F1, Weighted-F1, Confusion Matrix  

---

### 4. 🌸 Flower Species Classification  
- **Goal**: Identify flower species based on measurements  
- **Model**: k-NN Classifier  
- **Tuning**: Optimal `k` via 5-Fold CV  
- **Evaluation**: Accuracy  

---

### 5. 🏡 Airbnb Price Prediction  
- **Goal**: Predict rental price from features  
- **Model**: k-NN Regressor  
- **Tuning**: Optimal `k` via 5-Fold CV RMSE  
- **Evaluation**: RMSE, R²  

---

## ✅ Requirements  

Install dependencies with:  

```bash
pip install pandas numpy scikit-learn
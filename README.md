# 💳 Credit Card Fraud Detection using Machine Learning

During my internship at **CodSoft** as a **Machine Learning Intern**, I had the opportunity to work on a real-world problem that has a significant impact on the financial industry — **Credit Card Fraud Detection**.

## 🔍 Problem Statement

Credit card fraud is a major concern for financial institutions, leading to billions of dollars in losses annually. The goal of this project is to build a machine learning model that can accurately classify transactions as **fraudulent** or **legitimate**, with a strong emphasis on **precision and recall** due to the **highly imbalanced nature of the data**.

---

## 📊 Dataset

- **Source**: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- Contains **284,807 transactions**, of which **492 are frauds** (~0.17%)
- Features:
  - **Time**, **Amount**
  - **V1-V28**: PCA-transformed numerical features to protect confidentiality
  - **Class**: Target variable (0 → Legitimate, 1 → Fraud)

---

## 🧠 Machine Learning Workflow

### 1. **Data Preprocessing**
- Checked for missing/null values
- Scaled the `Amount` and `Time` features using `StandardScaler`
- Handled class imbalance using **SMOTE** (Synthetic Minority Over-sampling Technique)

### 2. **Model Selection**
Tried and tested multiple classification models:
- Logistic Regression
- Random Forest
- Decision Tree
- XGBoost (optional, for improved performance)

### 3. **Model Evaluation**
- Used **Confusion Matrix**, **Precision**, **Recall**, and **F1-Score**
- Emphasized **Recall** (true positive rate) since missing a fraudulent transaction is more costly than a false alarm

---

## 📈 Results

| Model              | Accuracy | Precision | Recall | F1-Score |
|-------------------|----------|-----------|--------|----------|
| Logistic Regression | 99.2%    | 86%       | 92%    | 89%      |
| Random Forest       | 99.6%    | 91%       | 94%    | 92%      |

✅ **Random Forest** performed best, offering high precision and recall — ideal for fraud detection where false negatives are critical.

---

## 📽️ Demo Video

Check out a short demo of the model in action (classification in real-time):

👉 [Attached Video File]

---

## 🧰 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib & Seaborn (for visualization)
- SMOTE (from imblearn)
- Jupyter Notebook

---

## 📌 Key Learnings
- Handling **imbalanced datasets** is crucial in fraud detection.
- **Evaluation metrics** like Precision and Recall are more meaningful than Accuracy in such cases.
- Learned how to build and optimize classification models in a high-risk domain like finance.

---

## 📫 Let's Connect!
Feel free to connect or reach out if you're working on similar problems or want to discuss machine learning applications in finance.

> 🔗 #CreditCardFraud #MachineLearning #CodSoftInternship #Python #AnomalyDetection #ImbalancedData #MLProject #FraudDetection #DataScience #LinkedInProjects


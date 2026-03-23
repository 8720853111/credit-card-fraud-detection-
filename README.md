# 💳 Credit Card Fraud Detection (End-to-End ML Project)

## 📌 Business Problem

Credit card fraud leads to significant financial losses. The goal is to build a machine learning model that can accurately identify fraudulent transactions.

## 📂 Dataset Source
Dataset obtained from [mention source, e.g., Kaggle]

---

## 📊 Dataset Overview

* Highly imbalanced dataset
* Fraud cases are rare compared to normal transactions

---

## 🔍 Key Steps

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Handling Imbalanced Data
* Feature Engineering
* Model Building

---

## 🤖 Models Used

* Logistic Regression
* Random Forest

## 🔍 Model Comparison

| Model | Strength |
|------|--------|
| Logistic Regression | Simple, interpretable |
| Random Forest | Better performance, handles imbalance well |
---

## 📈 Model Evaluation

Since the dataset is imbalanced:

* Accuracy is not reliable
* Focus on:

  * Precision
  * Recall
  * F1-score
## 📈 Model Performance

### Classification Report

| Class   | Precision | Recall | F1-Score | Support |
|---------|----------|--------|----------|---------|
| Normal  | 1.00     | 1.00   | 1.00     | 227449  |
| Fraud   | 0.92     | 0.66   | 0.77     | 396     |

---

### Overall Metrics

- **Accuracy:** 1.00  
- **Macro Avg:** Precision = 0.96, Recall = 0.83, F1-score = 0.88  
- **Weighted Avg:** Precision = 1.00, Recall = 1.00, F1-score = 1.00  

---

## 📊 Key Insights

* Fraud transactions follow different patterns than normal ones
* Certain features strongly influence fraud detection
* Model successfully identifies high-risk transactions

---

## 📷 Visualizations
<img width="408" height="278" alt="image" src="https://github.com/user-attachments/assets/6e02b4cc-d6be-414b-8a45-c205c12531ac" />
<img width="391" height="278" alt="image" src="https://github.com/user-attachments/assets/a6c6b084-0d03-470f-afae-fda1f2cce1c8" />
<img width="488" height="328" alt="image" src="https://github.com/user-attachments/assets/bfd41da1-99cf-4ba8-a652-1dd623a3f7a0" />
<img width="516" height="317" alt="image" src="https://github.com/user-attachments/assets/1a709d06-0f14-4024-8943-d83b8c0d6772" />


### Confusion Matrix

[[227427     22]
 [   135    261]]


### ROC Curve

<img width="338" height="333" alt="image" src="https://github.com/user-attachments/assets/bae5b83f-07ed-4731-a9a8-d16351272a74" />


---

## 🚀 How to Run

```bash id="pro3"
pip install -r requirements.txt
jupyter notebook notebooks/fraud_detection.ipynb
```

---

## 💡 Business Impact

* Reduces financial losses
* Improves fraud detection systems
* Enhances customer trust

---

## 👤 Author

Ashwini Khandelwal

# credit-card-fraud-detection-
Machine learning model to detect fraudulent transactions
# 💳 Credit Card Fraud Detection (End-to-End ML Project)

## 📌 Business Problem

Credit card fraud leads to significant financial losses. The goal is to build a machine learning model that can accurately identify fraudulent transactions.

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

---

## 📈 Model Evaluation

Since the dataset is imbalanced:

* Accuracy is not reliable
* Focus on:

  * Precision
  * Recall
  * F1-score

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

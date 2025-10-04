# Spam_Classification
classification_model
# 📧 Spam Classification using XGBoost and Decision Tree

This project applies **machine learning** to classify SMS or email messages as **spam** or **ham (not spam)** using two algorithms:
- **XGBoost Classifier**
- **Decision Tree Classifier**

We compare their performance on the same dataset to evaluate which performs better for spam detection.

---

## 🚀 Project Overview
The dataset is preprocessed and transformed into numerical features using **TF-IDF vectorization**.  
Both models are trained and evaluated using accuracy, precision, recall, and F1-score.

---

## 🧩 Steps

1. **Data Loading & Cleaning**
   - Lowercased text
   - Encoded target labels (ham = 0, spam = 1)

2. **Feature Extraction**
   - Used `TfidfVectorizer` (max 3000 features, English stopwords)

3. **Model Training**
   - Trained both **XGBoostClassifier** and **DecisionTreeClassifier** using an 80/20 train-test split

4. **Evaluation**
   - Compared performance with `classification_report`, `confusion_matrix`, and accuracy

---

## 📊 Results Summary

| Model | Accuracy |
|:------|:----------|
| **XGBoost** | 0.97 |
| **Decision Tree** | 0.96 |

 **XGBoost slightly outperformed Decision Tree**.

---

##  Visualizations
The notebook includes:
- Confusion matrices for both models
- Accuracy comparison bar chart

---

##  Dataset
Dataset: [SMS Spam Collection (Kaggle)](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

---



# 🧠 Text KNN Classifier

A simple yet powerful machine learning pipeline that classifies text using **TF-IDF vectorization** and a **K-Nearest Neighbors (KNN)** classifier. The model is evaluated using key metrics like **confusion matrix**, **ROC AUC**, **precision**, **recall**, and **F1-score**.

---

## 📌 Project Overview

This project demonstrates a machine learning pipeline to perform **binary text classification**. It includes:

- Text preprocessing using `TfidfVectorizer`
- Model training with `KNeighborsClassifier`
- Evaluation with:
  - Confusion Matrix
  - ROC AUC Score
  - Classification Report
- Visualization of results

---

## 🧰 Tech Stack

- Python 3.x
- scikit-learn
- pandas
- matplotlib / seaborn (for visualizations)

---

## 📊 Sample Metrics (on test set)

| Metric       | Value    |
|--------------|----------|
| Accuracy     | 95.6%    |
| Precision    | 97.3%    |
| Recall       | 87.1%    |
| F1 Score     | 91.9%    |
| ROC AUC      | 98.6%    |

---

## 🧪 How to Run

1. Clone this repo:
```bash
git clone https://github.com/yourusername/text-knn-classifier.git
cd text-knn-classifier

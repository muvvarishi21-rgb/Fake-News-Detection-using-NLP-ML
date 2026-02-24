# 📰 Fake News Detection using NLP & Machine Learning

## 📌 Overview
This project builds a Machine Learning model to classify news articles as **Real** or **Fake** using Natural Language Processing (NLP).  
It converts text data into numerical features using **TF-IDF Vectorization** and trains a **Logistic Regression** classifier to detect misinformation.

The system can evaluate model performance and predict whether new input news is real or fake.

---

## 🎯 Objectives
- Detect fake news using machine learning
- Apply NLP techniques for text preprocessing
- Convert text data into numerical form using TF-IDF
- Train and evaluate a classification model
- Predict real-time custom news input

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression

---

## 📂 Dataset Requirements

CSV file with the following columns:

- `text` → News article content
- `label` → 0 = Fake, 1 = Real

Example:

| text                               | label |
|------------------------------------|-------|
| Government announces tax reform    | 1     |
| Celebrity cloned by scientists     | 0     |

---

## ⚙️ Installation

1. Clone the repository:

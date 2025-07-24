# BBC News Text Classifier 📰

This project implements a **multi-class text classification** system using the [BBC News Dataset](https://www.kaggle.com/datasets/cpichot/bbc-news), which contains articles labeled into 5 categories: `business`, `entertainment`, `politics`, `sport`, and `tech`.

## 💡 Problem Statement

Classify a news article into one of the 5 predefined categories using machine learning models trained on article text.

## 📊 Dataset

- Source: Kaggle - BBC News Classification
- Columns:
  - `category`: The label
  - `text`: The article content

## 🛠️ Tech Stack

- Python
- Scikit-learn
- Pandas, NumPy
- TF-IDF Vectorizer
- Seaborn & Matplotlib for visualization

## 📈 Models Trained

- Multinomial Naive Bayes
- Logistic Regression
- Support Vector Machine (Linear)

## 🚀 How to Run

1. Clone the repo
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

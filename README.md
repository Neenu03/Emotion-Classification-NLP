# Sentiment/Emotion Classification using NLP

This project focuses on classifying text reviews into different emotion categories such as **joy, anger, fear, love, sadness, and surprise** using **Natural Language Processing (NLP)** and **Machine Learning** techniques.

## 🔍 Project Objective
The goal is to build a text classification model that can predict the underlying sentiment or emotion of a given review. This is a fundamental NLP task with practical applications in areas like social media monitoring, customer feedback analysis, and chatbot development.

## 📊 Exploratory Data Analysis (EDA)
EDA was performed to explore the distribution of sentiments and understand word frequency patterns using visualizations such as:
- Class distribution bar plots
- Word clouds for each emotion category

## 🧱 Components
| Step | Description |
|------|-------------|
| 1. Data Loading | Loaded raw text data using `pandas` |
| 2. Preprocessing | Lowercasing, punctuation removal |
| 3. Vectorization | Converted text to numeric features using TF-IDF |
| 4. Modeling | Trained models (Naive Bayes / SVM) on vectorized data |
| 5. Evaluation | Used classification report and confusion matrix |


## 📁 Files Included
- `train.txt` – Dataset with reviews and corresponding sentiments
- `notebook.ipynb` – Jupyter Notebook with all code, results, and EDA

## 🛠️ Requirements
Install dependencies via:
```bash
pip install -r requirements.txt

# Twitter_Sentiment_Analysis

---
title: "Twitter Sentiment Analysis"
author: "Aman Kumar"
description: "A machine learning project to analyze sentiments of tweets using NLP techniques."
tags: [machine learning, nlp, sentiment analysis, twitter, text classification]
date: 2025-07-11
license: MIT
---

# 🐦 Twitter Sentiment Analysis using NLP & Machine Learning

[![Python](https://img.shields.io/badge/python-3.9%2B-blue)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-green)]()

A machine learning project that performs sentiment analysis on tweets using Natural Language Processing (NLP). The system classifies tweets into **positive**, **negative**, or **neutral** sentiments.

---

## 📌 Features

- Preprocesses and cleans raw tweet text  
- Vectorizes text using TF-IDF  
- Trains Logistic Regression model for sentiment classification  
- Evaluates accuracy and classification metrics  
- Supports CSV input for batch predictions

---

## 🧠 Tech Stack

- **Language:** Python  
- **Libraries:** `pandas`, `numpy`, `scikit-learn`, `nltk`, `re`  
- **Model:** Logistic Regression  
- **NLP Techniques:** Stopword removal, stemming, TF-IDF  
- **Tools:** Jupyter Notebook  

---

## 📂 Project Structure

Twitter_Sentiment_Analysis/
│
├── Twitter_Sentiment_Analysis.ipynb # Main notebook with model pipeline
├── twitter_data.csv # Dataset used for training
├── requirements.txt # Python dependencies
├── screenshots/
│ └── sample_output.png # Prediction example (add if needed)
└── README.md # Project documentation


---

## 📊 Dataset Info

- **Source:** Pre-labeled tweet dataset  
- **Columns:** `tweet`, `label` (0 = Negative, 1 = Neutral, 2 = Positive)  
- **Samples:** ~5,000 tweets  
- **Class Distribution:** Balanced (ideal for classification)

---

## 📈 Model Pipeline

1. Load dataset  
2. Clean & preprocess tweet text  
3. Convert to numerical features using **TF-IDF Vectorizer**  
4. Train a **Logistic Regression** model  
5. Evaluate using **accuracy**, **confusion matrix**, and **classification report**

---

## ▶️ How to Run Locally

1. **Clone the repo**
   ```bash
   git clone https://github.com/Amankar003/Twitter_Sentiment_Analysis.git
   cd Twitter_Sentiment_Analysis



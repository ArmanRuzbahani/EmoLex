# 📊 Persian Sentiment & Emoji Analysis with NBSVM  

This repository implements the **NBSVM (Naive Bayes – Support Vector Machine)** model for **Persian sentiment analysis**.  
We use a diverse collection of Persian datasets (comments, tweets, food delivery reviews) as well as an **emoji dataset** for combined **text + emoji sentiment analysis**.  

---

## ⚡️ Model: NBSVM
**NBSVM** is a hybrid model that combines the statistical features of **Naive Bayes** with the discriminative power of **Support Vector Machine**.  

### Advantages:
- 🔹 High accuracy in short-text classification (tweets, reviews, comments)  
- 🔹 Faster than deep learning models for large-scale data  
- 🔹 Well-suited for Persian language and informal text  

The model is designed as **multi-class sentiment classification**, detecting emotions such as:  
🙂 Happy | 😢 Sad | 😡 Angry | 😐 Neutral | ❤️ Others  

---

## 📂 Datasets
The project is based on several Persian datasets from different domains:  

- 🛒 **DigiKala Product Reviews**  
  [DigiKala Comments & Products](https://www.kaggle.com/datasets/radeai/digikala-comments-and-products/data)  
  > ⚠️ Note: This dataset originally had **no sentiment labels**.  
  > We applied **K-Means clustering** to automatically group reviews and assign sentiment labels before training.  

- 🐦 **Persian Twitter Dataset**  
  [Persian Twitter Sentiment Analysis](https://www.kaggle.com/datasets/mohammadalimkh/persian-twitter-dataset-sentiment-analysis)

- 🍔 **SnappFood Reviews**  
  [SnappFood Persian Sentiment Analysis](https://www.kaggle.com/datasets/soheiltehranipour/snappfood-persian-sentiment-analysis)

- 😃 **Emoji Dataset**  
  [Persian Datasets on Kaggle](https://www.kaggle.com/datasets?tags=16993-Persian)

---

## 🚀 Features
- 🔍 Sentiment classification for **short Persian texts** (tweets, reviews, comments)  
- 😀 **Emoji-based sentiment detection**  
- 📑 Multi-class classification (Happy, Sad, Angry, Neutral, etc.)  
- ⚡️ Efficient on **large-scale datasets** (3M+ records)  
- 🤖 Semi-supervised learning using **K-Means clustering** for unlabeled datasets (DigiKala)  

---

## 📌 Use Cases
- Social media sentiment monitoring  
- Customer feedback analysis in **e-commerce** platforms  
- Food delivery app reviews (SnappFood, etc.)  
- Combined **text + emoji** sentiment analysis for higher accuracy  

---

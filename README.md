# Text-Sentiment-Analysis
Sentiment analysis on Persian text data using machine learning
# 📊 TextSentimentAnalysis

A machine learning project for sentiment analysis of Persian text comments using Natural Language Processing (NLP) and a Naive Bayes classifier.

---

## 🔍 Features

- Text preprocessing: lowercasing, punctuation removal, stopword filtering  
- Converts text into numerical features using `CountVectorizer`  
- Sentiment classification into `HAPPY` or `SAD`  
- Model evaluation using accuracy, precision, recall, and F1-score  

---

## 📁 Dataset

This project uses the [PNLPhub/snappfood-sentiment-analysis](https://huggingface.co/datasets/PNLPhub/snappfood-sentiment-analysis) dataset, which contains Persian customer comments labeled with sentiment.

---

## ⚙️ Requirements

Install the necessary Python libraries:

```bash
pip install pandas scikit-learn datasets

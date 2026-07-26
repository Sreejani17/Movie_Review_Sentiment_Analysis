# 🎬 Movie Review Sentiment Analysis

A machine learning project that classifies movie reviews as positive or 
negative, using text data (NLP) and comparing two different classification 
algorithms.

## 📊 Dataset
IMDB Dataset of 50K Movie Reviews (from Kaggle). Contains 50,000 movie 
reviews labeled as positive or negative.

## 🔧 Tech Stack
- Python
- pandas
- scikit-learn (TF-IDF, Logistic Regression, Naive Bayes)

## 🧠 Approach
1. Loaded and explored the IMDB reviews dataset
2. Cleaned raw text — removed HTML tags, punctuation, and lowercased all text
3. Converted text into numeric features using TF-IDF
4. Split data into training (80%) and test (20%) sets
5. Trained and compared two models: Logistic Regression and Naive Bayes
6. Evaluated using Accuracy, Confusion Matrix, and Classification Report
7. Tested the model on a custom, unseen sentence

## 📈 Results
- Logistic Regression Accuracy: **0.8835**
- Naive Bayes Accuracy: **0.8477**
- Logistic Regression performed better, likely because it can weigh words 
  more flexibly, while Naive Bayes assumes word occurrences are independent.

## 🚀 Next Steps
- Try word embeddings (Word2Vec) or deep learning models (LSTM/BERT) 
  for potentially higher accuracy
- Expand text cleaning (e.g., remove stopwords more aggressively, 
  handle negations like "not good")

## ▶️ Run it yourself
Open the notebook in Google Colab using the link included in the .ipynb file.

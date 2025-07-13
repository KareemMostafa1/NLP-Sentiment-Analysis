
---

## 🇬🇧 Task 1: English Sentiment Classification

- **Dataset**: Kaggle Dataset of Product reviews (Positive, Neutral and Negative)
- **Text Preprocessing**:
  - Lowercasing, punctuation removal
  - Tokenization, stopword removal
- **Model**: Logistic Regression
- **Vectorizer**: CountVectorizer (unigrams & bigrams)
- **Evaluation**:
  - Accuracy
  - Confusion Matrix
---

## 🇸🇦 Task 2: Arabic Sentiment Classification (Tweets)

- **Dataset**: Real Arabic tweets (binary labeled)
- **Extensive Text Preprocessing**:
  - Emoji demojizing
  - Diacritic removal
  - Arabic letter normalization
  - Stopword removal (using NLTK)
  - Optional stemming using ISRI
- **Model**: Logistic Regression
- **Vectorizer**: CountVectorizer (with cleaned & stemmed text)
- **Evaluation**:
  - Accuracy
  - Confusion Matrix (heatmap)
---

## 🔧 Tech Stack

- Python (pandas, scikit-learn, matplotlib, seaborn, nltk, emoji)
- Jupyter Notebook 

---

## 📊 Results Snapshot

| Task   | Accuracy | Model     
|--------|----------|-----------|
| English | 75.6%    | LogisticRegression |
| Arabic  | 94.2%    | LogisticRegression |

---

## 📌 Future Improvements

- Use embeddings (Word2Vec/BERT)
- Deep learning models (LSTM, transformers)
- Multiclass or fine-grained sentiment levels
- Expand datasets and handle sarcasm in tweets

---




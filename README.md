# 📧 Spam Message Classifier using Machine Learning

This project is a Natural Language Processing (NLP) application that uses supervised learning to automatically classify text messages as **Spam** or **Ham** (non-spam). The model is trained and evaluated using classic NLP techniques and machine learning algorithms.


## 📌 Problem Statement

Spam messages clutter inboxes, waste time, and sometimes serve as phishing or scam vectors. This project builds a classifier that can accurately detect spam using machine learning models trained on labeled text message data.


## 📊 Dataset

**Source**: [SMS Spam Collection Dataset (UCI)](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

- **Total Messages**: 5,574
- **Classes**: `spam`, `ham`
- **Features**: Single column text messages with a target label


## 🧠 Methods Used

- **Text Preprocessing**: Lowercasing, punctuation removal, stop word removal
- **Feature Engineering**: CountVectorizer, TfidfVectorizer
- **Algorithms**:
  - Naive Bayes
  - Decision Tree
  - Random Forest
  - Gradient Boosting
  - XGBoost
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score, Confusion Matrix


## 📈 Model Performance (Sample)

| Model             | Accuracy | Precision (Spam) | Recall (Spam) | F1-score (Spam) |
|------------------|----------|------------------|---------------|-----------------|
| Naive Bayes       | 99%      | 97%              | 95%           | 96%             |
| Random Forest     | 98%      | 94%              | 93%           | 93%             |
| XGBoost           | 98%      | 96%              | 91%           | 93%             |


## 🔮 Future Improvements

- Use deep learning (LSTM, BERT)
- Deploy as a web app using Flask or Streamlit
- Handle class imbalance using SMOTE or advanced resampling

### Author: 
Namshima B. Iordye

iordyebarnabas12@gmail.com

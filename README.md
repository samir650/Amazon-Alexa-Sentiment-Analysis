# 📊 Amazon Alexa Sentiment Analysis

## 📝 Overview
This project analyzes customer reviews of Amazon Alexa devices to predict sentiment (positive or negative feedback). The dataset used is `amazon_alexa.tsv`, and a machine learning model is built using logistic regression with text preprocessing techniques.

## 📂 Dataset
The dataset contains:
- 🗣️ `verified_reviews`: The customer review text.
- ✅ `feedback`: The sentiment label (1 for positive, 0 for negative).

## 🛠️ Preprocessing
The text data is preprocessed using:
- ✂️ Tokenization with spaCy.
- 🔍 Lemmatization.
- ❌ Removal of stop words and punctuation.

## 🔗 Model Pipeline
A machine learning pipeline is built using:
1. **🧹 Text Cleaning**: Custom transformer for text preprocessing.
2. **📊 Feature Extraction**: Bag of Words (BoW) and TF-IDF vectorization.
3. **🤖 Classification**: Logistic Regression.

## 🎯 Model Training & Testing
- 📊 The dataset is split into 70% training and 30% testing.
- 🏋️ The logistic regression model is trained and evaluated.

## 📈 Results
The model is evaluated using accuracy, precision, and recall metrics:
- ✅ **Accuracy**: Measures overall correctness.
- 🎯 **Precision**: Measures how many predicted positives are actually positive.
- 🔄 **Recall**: Measures how many actual positives were correctly predicted.

## 🔧 Requirements
To run this notebook, install the following dependencies:
```bash
pip install pandas scikit-learn spacy
python -m spacy download en_core_web_sm
```

## ▶️ Running the Notebook
1. 📥 Load the dataset (`amazon_alexa.tsv`).
2. 🛠️ Run the preprocessing steps.
3. 📈 Train the logistic regression model.
4. 📊 Evaluate the model's performance.

## 🏁 Conclusion
This project demonstrates sentiment analysis using NLP and machine learning techniques to classify customer reviews of Amazon Alexa products. 🚀


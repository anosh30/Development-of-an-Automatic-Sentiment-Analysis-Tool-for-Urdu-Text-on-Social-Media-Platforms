# 🔍 Development of an Automatic Sentiment Analysis Tool for Urdu Text on Social Media Platforms

## 📌 Project Overview

This repository contains a complete Natural Language Processing (NLP) pipeline built for **sentiment analysis of Urdu social media content**. The tool is capable of classifying Urdu posts from platforms like Twitter, Facebook, Instagram, and YouTube into **positive, negative, or neutral** sentiments.

This project is designed to help **brands**, **influencers**, and **businesses** gain deeper insights into Urdu-speaking audiences by automating sentiment classification.

---

## 💡 Key Features

- Custom Urdu **stopword removal**.
- Cleaning of **punctuation, emojis, hashtags**, and **URLs**.
- Handling **spelling variations** and **short conversations**.
- Implementation of **Urdu stemming and lemmatization**.
- Advanced **tokenization** tailored for Urdu script.
- **TF-IDF** and **Word2Vec**-based feature extraction.
- **N-gram** analysis (unigrams, bigrams, trigrams).
- **Machine Learning-based** sentiment classifier.
- Evaluation with **accuracy, precision, recall, and F1-score**.

---

## 🧠 NLP Pipeline Phases

### 🌀 Phase 1: Text Preprocessing
- Removal of Urdu stopwords (e.g., "اور", "کہ", "یہ").
- Emoji handling using sentiment dictionaries (😊 → positive).
- Cleansing of hashtags, URLs, and non-informative symbols.
- Filtering out very short or incomplete posts.

### 🪒 Phase 2: Stemming and Lemmatization
- Reduce gender/tense/plural word variants to base forms (e.g., "اچھا", "اچھی", "اچھے" → "اچھا").
- Lemmatization using Urdu root word dictionaries (e.g., "چل رہی" → "چل").

### 📊 Phase 3: Feature Extraction
- Urdu-friendly tokenization.
- Term Frequency-Inverse Document Frequency (TF-IDF).
- Word2Vec training and similarity results (e.g., most similar words to "اچھا").

### 🔗 Phase 4: N-gram Analysis
- Generate unigrams, bigrams, trigrams.
- Frequency analysis to identify common patterns.

### 🧮 Phase 5: Sentiment Classification
- Machine learning models: Logistic Regression, SVM, Naive Bayes.
- Classification of Urdu posts into sentiment labels.
- Performance metrics: Accuracy, Precision, Recall, F1-score.

### ✅ Phase 6: Evaluation & Reflection
- Model validation and error analysis.
- Discussion of Urdu-specific NLP challenges and future improvements.

---

## 🧪 Example Outputs

- **TF-IDF Top Terms:** List of highest scoring terms in the dataset.
- **Word2Vec Neighbors:** Top similar words for "اچھا".
- **Top Bigrams/Trigrams:** Most frequent multi-word expressions in the dataset.
- **Model Metrics:** Accuracy ~87%, Precision ~85%, Recall ~84%, F1-score ~84.5%.

---

## 📁 Project Structure


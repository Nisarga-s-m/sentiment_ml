# 🛍️ E-commerce Sentiment Analysis with Machine Learning & NLP

This project presents an advanced **AI-powered sentiment analysis system** designed to classify customer feedback from e-commerce platforms into **Positive**, **Neutral**, or **Negative** sentiments. The system supports real-time analysis, proactive decision-making, and enhanced customer satisfaction by extracting insights from unstructured review data.

---

## 🎯 Aim

To implement a sentiment analysis model that automatically classifies **e-commerce customer feedback** into sentiment categories—positive, negative, or neutral—enabling businesses to make **real-time**, **data-driven decisions** for improving service quality.

---

## ✅ Objectives

- Develop a robust sentiment analysis model using modern **NLP techniques**
- Evaluate both traditional ML models and deep learning approaches:
  - Naïve Bayes
  - Logistic Regression
  - Random Forest
  - LSTM (RNN)
  - BERT (transformer-based)
- Analyze sentiment trends across product categories (laptops, phones, TVs)
- Extract actionable business insights to support:
  - Product recommendations
  - Customer engagement
  - Marketing strategies

---

## 📈 Business Understanding

- Identified a real-world problem: **improving customer satisfaction** through feedback mining.
- Defined clear success metrics aligned with business goals.
- Focused on the **impact of online reviews** on brand reputation and customer retention.

---

## 📊 Dataset

- Source: **Amazon product reviews**
- Fields used:
  - Review text
  - Star ratings
  - Product category

---

## 🔍 Data Understanding

- Explored sentiment distribution across categories
- Identified data quality issues and class imbalance
- Gained insights into customer emotion triggers

---

## 🧹 Data Preparation

- **Text Preprocessing**:
  - Tokenization
  - Stopword removal
  - Normalization
- **Labeling**:
  - Converted star ratings to sentiment labels (Positive, Neutral, Negative)
- **Data Balancing**:
  - Applied oversampling/undersampling to address class imbalance

---

## 🤖 ML & AI Modeling

### ML Pipeline Overview

1. **Data Cleaning** – Removed HTML, punctuation, etc.
2. **Class Balancing** – Handled imbalance across sentiment categories
3. **Artificial Data** – Used OpenAI to generate synthetic reviews for model generalization
4. **Baseline Model** – Logistic Regression (tuned with GridSearchCV)
5. **Random Forest** – Achieved highest accuracy
6. **Naïve Bayes** – Used for baseline comparison
7. **LSTM (RNN)** – Implemented using Keras with word embeddings
8. **GPT-4 Hybrid Inference** – Integrated semantic search with generative reasoning

---

## 💬 Real-Time Chatbot Integration

A custom AI-powered **WhatsApp-style chat interface** was developed to visualize and test the model in real-time:

- User sends a message
- Bot performs sentiment analysis
- If **multiple negative messages**, it **escalates to a human assistant**
- Otherwise, bot continues the interaction

---

## 🧠 GPT-4 + Vector Store Integration

### What We Did:
- Converted feedback to dense vector embeddings
- Stored in **ChromaDB** along with sentiment labels
- Retrieved most similar reviews using vector similarity
- Prompted **GPT-4** with similar examples for few-shot sentiment classification

### Why This Works:
- Combines **semantic understanding** with **generative reasoning**
- Provides **explainable** and **context-aware** sentiment tagging
- Highly scalable and flexible architecture

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score

---

## 🚀 Future Enhancements

- Deploy as a Streamlit or Flask web app
- Integrate multilingual sentiment analysis
- Visual dashboards for product-wise sentiment trends
- Live monitoring for brand reputation tracking

---

#

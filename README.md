# 💰 FinBot – AI-Powered Financial Advisor Chatbot for Students

> An intelligent Retrieval-Augmented Generation (RAG) chatbot that provides personalized financial guidance for university students using NLP, Transformer models, FAISS Vector Search, and Google Gemini.

---

## 📌 Overview

Financial literacy is a major challenge for many university students. **FinBot** was developed to bridge this gap by providing AI-driven financial advice tailored to students' spending habits and financial queries.

The project combines traditional Natural Language Processing techniques with modern Large Language Models (LLMs) to build a smart financial assistant capable of understanding user intent, retrieving relevant financial knowledge, and generating context-aware responses.

---

## 🚀 Features

* 🤖 AI-powered conversational financial advisor
* 📊 Student spending analytics dashboard
* 🧠 Intent Classification using TF-IDF + Logistic Regression
* 🔍 Semantic Search using Sentence Transformers
* 📚 FAISS Vector Database
* 💬 Retrieval-Augmented Generation (RAG)
* ✨ Google Gemini powered response generation
* 📈 Financial health insights
* 💾 Multi-turn conversation memory
* 🌐 Interactive Streamlit Web Application

---

# 🏗 System Architecture

```
User Query
      │
      ▼
Text Preprocessing
      │
      ▼
Intent Classification
(Logistic Regression)
      │
      ▼
Sentence Transformer
Embedding
      │
      ▼
FAISS Vector Search
      │
      ▼
Relevant Financial Documents
      │
      ▼
Google Gemini
(RAG Prompt)
      │
      ▼
Personalized Financial Response
```

---

# 🛠 Tech Stack

### Programming Language

* Python

### Machine Learning & NLP

* TF-IDF
* Logistic Regression
* Linear SVM
* BERT (bert-base-uncased)
* Sentence Transformers (all-MiniLM-L6-v2)

### Vector Database

* FAISS

### Large Language Model

* Google Gemini 1.5 Flash

### Framework

* Streamlit

### Data Processing

* Pandas
* NumPy
* Scikit-learn
* NLTK

---

# 📂 Datasets

### Student Spending Dataset

* 1,000 student records
* Income, expenses, savings
* Financial behavior analysis

### Bitext Banking Dataset

* 25,545 banking queries
* 26 intent categories

### FiQA Financial Corpus

* 5,000 financial documents
* Used for semantic retrieval

---

# 📊 Model Performance

## Intent Classification

| Model               | Accuracy   |
| ------------------- | ---------- |
| Logistic Regression | **98.71%** |
| Linear SVM          | **98.81%** |

---

## FAISS Retrieval

* 5,000 indexed documents
* Average retrieval latency: **168 ms**
* 384-dimensional embeddings

---

# 📈 Project Modules

### NLP Pipeline

* Lowercasing
* Tokenization
* Stopword Removal
* Lemmatization
* TF-IDF Feature Extraction

---

### Intent Classification

Predicts one of **26 banking intents** before retrieval.

---

### Semantic Search

Uses Sentence Transformer embeddings to retrieve the most relevant financial documents from the FAISS index.

---

### RAG Pipeline

1. User asks a question
2. Intent is detected
3. Query is embedded
4. Relevant documents are retrieved
5. Gemini generates a grounded response

---

### Streamlit Dashboard

The application includes:

* 💬 AI Chat Interface
* 📈 Spending Dashboard
* 📊 Financial Analytics
* 📉 Savings Visualization
* 📚 Conversation History

---

# 📁 Project Structure

```
FinBot/

│── finbot_app.py
│── fiqa_faiss.index
│── fiqa_corpus.json
│── fiqa_cleaned.parquet
│── models/
│── assets/
│── notebooks/
│── requirements.txt
│── README.md
```

---

# 🎯 Future Improvements

* User Authentication
* Persistent Chat History
* Fine-tuned Financial Transformer
* Real-time Financial APIs
* Voice-based Assistant
* Budget Goal Tracking
* Investment Recommendation Module

---

# 👩‍💻 Team

**Fatima**
BS Data Science
University of Central Punjab

**Maryam**
BS Data Science
University of Central Punjab

Supervisor: **Mr. Zishan Hussain Chohan**

---

# ⭐ Project Highlights

* Retrieval-Augmented Generation (RAG)
* Google Gemini Integration
* Transformer-based Semantic Search
* FAISS Vector Database
* High Accuracy Intent Classification
* Interactive Streamlit Dashboard
* Personalized Financial Recommendations

---

## 📜 License

This project is developed for educational and research purposes as part of the **Deep Natural Language Processing** course at the **University of Central Punjab**.

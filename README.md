

#  Emotion Detection Chatbot

**A Conversational AI for Mental Health Support using NLP and Machine Learning**

## 🧠 Overview

This project presents a machine learning–based emotion detection chatbot designed to provide empathetic, real-time support in mental health contexts. It uses Natural Language Processing (NLP) techniques and both traditional ML (LinearSVC) and Transformer-based deep learning models (BERT) to classify user emotions from text input and respond with personalized emotional feedback.

## 🚀 Objectives

* Detect user emotions (joy, sadness, anger, fear, etc.) from free-text input
* Provide empathetic, context-aware responses
* Supplement mental health support with non-judgmental interaction
* Explore performance trade-offs between LinearSVC and BERT models

## 📁 Dataset

* **Name:** Emotion Detection Dataset
* **Size:** 34,792 text entries
* **Labels:** `joy`, `sadness`, `anger`, `fear`, `surprise`, `neutral`
* **Source:** Public NLP dataset for emotion classification

## ⚙️ Preprocessing

* Lowercasing and text cleaning
* Tokenization using NLTK
* Stopword removal
* Handling missing values

## 🛠️ Feature Engineering

| Method     | Details                                                            |
| ---------- | ------------------------------------------------------------------ |
| **TF-IDF** | For traditional ML (LinearSVC), captures word importance           |
| **BERT**   | Captures contextual meaning, negation, sarcasm, and subtle emotion |

## 🧪 Models Used

* **LinearSVC** (Lightweight, efficient, less accurate on nuanced emotions)
* **BERT** (Deep contextual understanding, higher accuracy but computationally heavy)

## 🎯 Results

| Metric   | LinearSVC         | BERT                               |
| -------- | ----------------- | ---------------------------------- |
| Accuracy | 62%               | 68%                                |
| Best Use | Fast environments | Nuanced text, emotional complexity |

## 🤖 Emotion Response System

* **Predefined Templates** for each emotion
* **Randomized Selection** to keep conversation natural
* **Context-aware Personalization**

## 🧪 Limitations & Future Work

* Struggles with mixed emotions or grammatical errors
* Future improvements: enhanced error handling, broader emotion spectrum, conversation memory

## 🧰 Tech Stack

* Python 🐍
* Scikit-learn
* Transformers (BERT via Hugging Face)
* NLTK
* Pandas / NumPy


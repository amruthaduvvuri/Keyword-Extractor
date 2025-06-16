# 🧠 Keyword Extraction from Text using NLP

This project implements a smart keyword extractor using Natural Language Processing (NLP) techniques to identify the most relevant and context-rich keywords from unstructured text. It is designed to assist in content tagging, SEO optimization, and summarization tasks.

## 📌 Objective

To build an automated system that extracts key terms and phrases from any given text corpus or document using statistical and semantic methods.

## 🛠 Tech Stack

- Python
- NLP Libraries: spaCy, NLTK, RAKE
- Pandas, re (Regex), NumPy

## 💡 Features

- Supports plain text and web content
- Removes stop words and performs POS tagging
- Extracts top-n keywords using:
  - TF-IDF / RAKE / spaCy noun-chunking
- Customizable filters: word length, frequency, POS
- Option to export keywords to CSV

## 🔍 Sample Input

```text
Machine learning is a subfield of artificial intelligence (AI) that focuses on the development of algorithms that can learn and make predictions or decisions without being explicitly programmed.
```
## 🔍 Sample Output
```text
["machine learning", "artificial intelligence", "algorithms", "predictions", "decisions"]

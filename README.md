# Text-Normalization-and-Stemming-with-NLTK

## NLP Text Preprocessing with NLTK 🧠📄

This project demonstrates fundamental **Natural Language Processing (NLP)** techniques using the **NLTK (Natural Language Toolkit)** library in Python.  
It focuses on converting raw text into a clean and normalized form that can be used for downstream machine learning and NLP tasks.

---

## 📌 Project Overview

Text data often contains noise such as stopwords, punctuation, and different word forms.  
This project performs essential preprocessing steps including:

- Sentence Tokenization
- Word Tokenization
- Stopword Removal
- Stemming using Porter Stemmer

These steps help improve the efficiency and accuracy of NLP and ML models.

---

## 🛠️ Technologies Used

- Python
- NLTK (Natural Language Toolkit)

---

## 🔄 NLP Pipeline Steps

1. **Sentence Tokenization**  
   Splits a paragraph into individual sentences.

2. **Word Tokenization**  
   Breaks sentences into individual words.

3. **Stopword Removal**  
   Removes commonly used words (e.g., *is, the, and*) that do not add meaningful information.

4. **Stemming**  
   Reduces words to their root form using **Porter Stemmer**.

---

## 📂 Code Explanation

- `nltk.sent_tokenize()` → Splits text into sentences  
- `nltk.word_tokenize()` → Tokenizes sentences into words  
- `stopwords.words('english')` → Removes irrelevant words  
- `PorterStemmer()` → Converts words to their base stem  

Each sentence is processed and reconstructed after cleaning.

---

## 📈 Output Example

Raw sentence:

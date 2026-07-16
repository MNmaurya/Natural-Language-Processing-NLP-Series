# Stemming

## 🎯 Objective

Learn the concept of **Stemming**, an important text preprocessing technique in Natural Language Processing (NLP). The goal is to reduce words to their root or base form, making text analysis more efficient.

---

## 📚 Concepts Covered

- What is Stemming?
- Why Stemming is used
- Porter Stemmer
- Regexp Stemmer
- Snowball Stemmer
- Comparison of different stemmers

---

## 🛠 Libraries Used

- Python
- NLTK

---

## 🔧 Classes & Functions Used

- `PorterStemmer()`
- `RegexpStemmer()`
- `SnowballStemmer()`
- `.stem()`
---

## 🚀 Bonus Challenge – Comparing Different Stemmers

To gain a better understanding of stemming algorithms, I compared the outputs of three different stemmers:

- Porter Stemmer
- Regexp Stemmer
- Snowball Stemmer

using the same list of words.

### Challenge Code

text =['Students','studying','happily','running','towards','university','adjustable','chairs','arranged','beautifully']


<img width="414" height="362" alt="image" src="https://github.com/user-attachments/assets/5d2754fa-1cb4-41cd-8cba-a0ed7bbbd6b0" />

---


## 🔍 Observation

- Porter Stemmer is one of the most widely used stemming algorithms.
- Regexp Stemmer removes suffixes based on custom regular expressions.
- Snowball Stemmer is an improved version of Porter Stemmer and often produces better stems.
- Different stemming algorithms may produce different outputs for the same word.

---

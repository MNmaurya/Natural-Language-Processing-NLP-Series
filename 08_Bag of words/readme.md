# Bag of Words (BoW)

## 🎯 Objective

Learn the concept of **Bag of Words (BoW)** and understand how textual data is converted into numerical vectors based on the frequency of words.

---

## 📚 Concepts Covered

- What is Bag of Words?
- Text Preprocessing
- Vocabulary Creation
- Word Frequency
- Binary Bag of Words
- Count-Based Bag of Words
- Advantages and Limitations

---

## 🛠 Prerequisites

- Tokenization
- Stop Words Removal
- Basic Text Preprocessing

---

## 📖 What is Bag of Words?

Bag of Words (BoW) is a text representation technique that converts text into numerical vectors by counting the occurrence of each word in a document.

It ignores the order of words and focuses only on whether a word exists or how many times it appears.

---

## 🔄 Steps Involved

1. Convert all text to lowercase.
2. Remove stop words.
3. Create a vocabulary of unique words.
4. Count the frequency of each word.
5. Represent each sentence as a numerical vector.

---

## 💡 Binary Bag of Words vs Count Bag of Words

### Binary Bag of Words

- Uses only **0** and **1**.
- **1** → Word is present.
- **0** → Word is absent.

### Count Bag of Words

- Stores the number of times a word appears.
- Values can be **0, 1, 2, 3...** depending on frequency.

---

## 💼 Real-World Applications

- Spam Detection
- Sentiment Analysis
- Document Classification
- Text Categorization
- Information Retrieval
- Search Engines

---

## 🚀 Bonus Challenge – Creating a Bag of Words Representation

Instead of directly applying the Bag of Words technique, I first preprocessed the text by converting all words to lowercase and removing stop words. Then, I created a vocabulary and calculated the frequency of each unique word.

### 📄 Challenge Dataset

Sentence 1:

> He is a good boy.

Sentence 2:

> She is a good girl.

Sentence 3:

> Boy and girl are good.

After preprocessing:

```text
S1 → good boy
S2 → good girl
S3 → boy girl good
```

Vocabulary:

```text
good
girl
boy
```

The Bag of Words vectors were then generated using the vocabulary.

---


## 🔍 Observation

- Words were converted to lowercase before processing.
- Stop words were removed to retain only meaningful words.
- A vocabulary was created from unique words.
- The order of words was ignored.
- Binary BoW represents only the presence or absence of words.
- Count BoW represents the frequency of words in each document.

---

## ⚠️ Limitations

- Produces sparse vectors for large vocabularies.
- Does not capture semantic meaning.
- Ignores word order.
- Suffers from the Out-of-Vocabulary (OOV) problem.
- Can lead to overfitting when the vocabulary becomes very large.

---

## 📚 Today's Learning

Today, I learned how the Bag of Words model converts text into numerical vectors using word frequencies. I also understood the difference between **Binary Bag of Words** and **Count Bag of Words**, along with their advantages, limitations, and practical applications in NLP.

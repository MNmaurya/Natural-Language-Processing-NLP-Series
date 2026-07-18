# One Hot Encoding

## 🎯 Objective

Understand the concept of **One Hot Encoding (OHE)** and learn how textual data can be converted into numerical vectors for Machine Learning and Natural Language Processing (NLP) tasks.

---

## 📚 Concepts Covered

- What is One Hot Encoding?
- Converting text into vectors
- Creating a unique vocabulary
- Vector representation of words
- Out-of-Vocabulary (OOV) problem
- Sparse Matrix
- Advantages and Limitations of One Hot Encoding

---

## 📖 What is One Hot Encoding?

One Hot Encoding is a technique used to convert categorical values or words into numerical vectors.

Each unique word in the vocabulary is assigned a unique position. A word is represented by placing **1** at its corresponding position and **0** at every other position.

Example:

```text
Vocabulary:
[The, food, is, good, bad, Burger, amazing]

The      → [1,0,0,0,0,0,0]
food     → [0,1,0,0,0,0,0]
good     → [0,0,0,1,0,0,0]
Burger   → [0,0,0,0,0,1,0]
```

---

## 💡 Why is One Hot Encoding Important?

- Converts text into numerical form.
- Easy to understand and implement.
- Widely used for categorical data.
- Useful for small datasets and basic Machine Learning models.

---

## ⚠️ Limitations

- Produces a **Sparse Matrix** (mostly zeros).
- Cannot capture semantic meaning between words.
- Fixed vocabulary size.
- Suffers from the **Out-of-Vocabulary (OOV)** problem when unseen words appear during testing.
- Can increase memory usage for large vocabularies.

---

## 💼 Real-World Applications

- Text Classification
- Sentiment Analysis
- Spam Detection
- Basic Machine Learning Models
- Encoding Categorical Features

---

## 🚀 Bonus Challenge – Understanding the Out-of-Vocabulary (OOV) Problem

Instead of encoding only a single sentence, I created multiple training sentences to build a vocabulary and then tested the model with a new sentence containing an unseen word.

### 📄 Challenge

Training Sentences:

- The food is good.
- The food is bad.
- Burger is amazing.

Testing Sentence:

> Pizza is good.

Since the word **Pizza** was not present in the training vocabulary, One Hot Encoding could not generate its vector representation. This demonstrates the **Out-of-Vocabulary (OOV)** problem, where unseen words cannot be encoded using the existing vocabulary.

---

### 📸 Notes

chechk out the attached image -----> one_hot_encoding.jpg

---

## 🔍 Observation

- Every unique word receives a unique binary vector.
- Vocabulary size determines the vector length.
- Unseen words cannot be represented.
- One Hot Encoding does not capture relationships or similarity between words.
- It is simple and effective for small vocabularies but becomes inefficient for larger datasets.

---

## 📚 Today's Learning

Today, I learned how One Hot Encoding converts words into binary vectors using a predefined vocabulary. I also understood its limitations, such as sparse matrices and the Out-of-Vocabulary (OOV) problem, which motivated the need for more advanced word representation techniques.

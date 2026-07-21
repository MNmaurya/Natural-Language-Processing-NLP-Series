# 🛑 Stop Words

## 🎯 Objective

Learn the concept of **Stop Words** in Natural Language Processing (NLP) and understand how removing them helps reduce unnecessary words while retaining meaningful information for text analysis.

---

## 📚 Concepts Covered   
- What are Stop Words?
- Why Stop Words are removed
- Stop Words in NLTK
- Removing Stop Words from text
- Applying Stop Word Removal before Stemming and Lemmatization

---

## 🛠 Libraries Used

- Python
- NLTK

---

## 🔧 Functions Used

- `stopwords.words('english')`
- `word_tokenize()`
- `set()`

---

## 📖 What are Stop Words?

Stop Words are frequently occurring words that usually do not contribute much meaning to a sentence. They are often removed during text preprocessing to reduce noise and improve the efficiency of NLP models.

Examples:

```text
the, is, are, am, was, were, in, on, at, of, to, and, for
```

---

## 💡 Why Remove Stop Words?

- Reduces unnecessary words from text.
- Decreases vocabulary size.
- Improves preprocessing efficiency.
- Helps machine learning models focus on meaningful words.
- Speeds up text processing.

---

## 🚀 Bonus Challenge – Stop Words Removal with Text Preprocessing

Instead of testing stop words on a short sentence, I experimented with a **real-world paragraph**. After removing stop words, I further applied **Snowball Stemming** and **Lemmatization** to observe how each preprocessing step transforms the same text.

### 📄 Challenge Text

> The boys were playing happily in the beautiful garden while the girls were singing and dancing. They were enjoying the sunny weather and eating delicious apples because they had been studying very hard for their examinations. The teachers were encouraging the students to work carefully, think creatively, and solve problems efficiently.

---

### 📸 Challenge Output

- output attached in ipynb file

---

## 🔍 Observation

- Common stop words such as **the, were, in, while, and, they, had, for** were successfully removed.
- Removing stop words made the remaining text shorter and focused on meaningful words.
- Applying **Snowball Stemming** further reduced words to their stem forms.
- Applying **Lemmatization** preserved meaningful dictionary words while reducing inflected forms.
- This experiment demonstrated that stop word removal is usually the first step in a complete NLP preprocessing pipeline.

---

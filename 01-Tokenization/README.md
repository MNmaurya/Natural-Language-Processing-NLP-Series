# 📖 Day 1 – Tokenization

## 🎯 Objective

Learn the fundamentals of **Tokenization**, the first preprocessing step in Natural Language Processing.

---

## 📚 Concepts Covered

- Sentence Tokenization
- Word Tokenization
- Why Tokenization is important

---

## 🛠 Library Used

- Python
- NLTK

---

## 🔧 Functions Used

- `sent_tokenize()`
- `word_tokenize()`
- `wordpunct_tokenize()`

---

## 📥 Sample Input

```text
Hello everyone!
Welcome to the world of NLP.
Let's learn tokenization.
```

---

## 📤 Sample Output

### Sentence Tokens

```python
[
'Hello everyone!',
'Welcome to the world of NLP.',
"Let's learn tokenization."
]
```

### Word Tokens

```python
[
'Hello',
'everyone',
'!',
'Welcome',
'to',
'the',
'world',
'of',
'NLP',
'.',
'Let',
"'s",
'learn',
'tokenization',
'.'
]
```

---

## 💡 Key Takeaways

- Tokenization is the first step in text preprocessing.
- Sentence tokenization splits text into sentences.
- Word tokenization splits sentences into individual words or tokens.
- Most NLP tasks begin with tokenization.

---

## 💼 Real-World Applications

- ChatGPT
- Google Translate
- Grammarly
- Voice Assistants
- Search Engines
- Spam Detection

---
## 🚀 Challenge I Tried

Instead of using only simple text, I experimented with a sentence containing:

- 😊 Emojis
- 🌐 URLs
- 📧 Email addresses
- 🔢 Numbers
- ❗ Punctuation

Example:

```text
Hi 😊! welcome to my https://github.com. Email me at muskannarainmaurya@gmail.com. I have a CGPA above 8.5!
```

### Observation
This experiment helped me understand how NLTK tokenizes different types of text, including punctuation, emojis, URLs, email addresses, and numbers.

**Challenge Output:**
---
<img width="414" height="353" alt="image" src="https://github.com/user-attachments/assets/d01c0f00-4745-4082-847c-78593d0fe4f5" />

---

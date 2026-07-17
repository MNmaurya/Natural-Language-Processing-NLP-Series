# 🏷️ Part of Speech (POS) Tagging

## 🎯 Objective

Learn the concept of **Part of Speech (POS) Tagging** in Natural Language Processing (NLP) and understand how words are assigned their grammatical roles within a sentence.

---

## 📚 Concepts Covered

- What is POS Tagging?
- Why POS Tagging is important
- Common POS Tags
- POS Tagging using NLTK
- Understanding grammatical roles of words

---

## 🛠 Libraries Used

- Python
- NLTK

---

## 🔧 Functions Used

- `word_tokenize()`
- `nltk.pos_tag()`

---

## 📖 What is Part of Speech (POS) Tagging?

Part of Speech (POS) Tagging is the process of assigning a grammatical category to every word in a sentence.

Some common grammatical categories include:

- Noun
- Verb
- Adjective
- Adverb
- Pronoun
- Preposition
- Conjunction
- Determiner

For example,

```text
The little boy is playing football.
```

POS Tags:

```text
The       → DT (Determiner)
little    → JJ (Adjective)
boy       → NN (Noun)
is        → VBZ (Verb)
playing   → VBG (Verb)
football  → NN (Noun)
```

---

## 💡 Why is POS Tagging Important?

- Helps understand sentence structure.
- Improves text preprocessing.
- Required for accurate Lemmatization.
- Used in Machine Translation.
- Helps in Named Entity Recognition (NER).
- Improves Chatbots and Question Answering systems.
---

## 🚀 Bonus Challenge – POS Tagging After Removing Stop Words

Instead of directly applying POS Tagging, I first removed the English stop words and then assigned POS tags to the remaining meaningful words. This helped me understand how POS Tagging works on cleaned text.

### 📄 Challenge Text

> The boys were playing happily in the beautiful garden while the girls were singing and dancing. They were enjoying the sunny weather and eating delicious apples because they had been studying very hard for their examinations. The teachers were encouraging the students to work carefully, think creatively, and solve problems efficiently.
---
### 📸 Challenge Output

Output is in attached in ipynb file.

---

## 🔍 Observation

- Stop words were removed before applying POS Tagging.
- Each remaining word was assigned its grammatical role such as Noun, Verb, Adjective, or Adverb.
- Words like **playing**, **singing**, and **studying** were identified as verbs.
- Words like **beautiful** and **delicious** were identified as adjectives.
- POS Tagging provides grammatical information that is useful for advanced NLP tasks like Lemmatization and Named Entity Recognition.

---

## 📚 Today's Learning

Today, I learned how POS Tagging assigns grammatical roles to words using NLTK. I also explored how applying POS Tagging after removing stop words helps focus on meaningful words, making text preprocessing more effective for downstream NLP tasks.

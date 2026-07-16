# Lemmatization using NLTK

## Overview
This project demonstrates **Lemmatization** in Natural Language Processing (NLP) using Python and the NLTK library.

Lemmatization reduces words to their **base or dictionary form (lemma)** by considering the word's meaning and its part of speech (POS). Unlike stemming, it produces valid English words.

## Features
- Tokenization
- Word Lemmatization
- Part-of-Speech (POS) support
- Comparison of original and lemmatized words

## Technologies Used
- Python
- NLTK (Natural Language Toolkit)

## Installation
Install the required package:
```bash
pip install nltk
```
Download the required NLTK datasets:
```python
import nltk
nltk.download('punkt')
nltk.download('wordnet')
nltk.download('omw-1.4')
```

## Example

### Input
```text
running
better
studies
wolves
```

### Output
```text
run
good
study
wolf
```

## Project Structure

```
Lemmatization/
│── lemmatization.ipynb
│── README.md
```

## What is Lemmatization?

Lemmatization is the process of converting words into their base (dictionary) form while considering grammar and context.

Example:

- Running → Run
- Better → Good
- Studies → Study
- Wolves → Wolf

## Difference Between Stemming and Lemmatization

| Stemming | Lemmatization |
|----------|---------------|
| Removes prefixes/suffixes | Uses vocabulary and grammar |
| Faster | Slightly slower |
| May produce invalid words | Produces meaningful words |
| Example: Studies → Studi | Example: Studies → Study |

## Author

Muskan Maurya

# Named Entity Recognition (NER) using NLTK

## Overview
This project demonstrates **Named Entity Recognition (NER)** in Natural Language Processing (NLP) using Python and the NLTK library.

Named Entity Recognition is the process of identifying and classifying named entities in text into predefined categories such as **Person, Organization, Location, Date, Time, Money, Percentage**, and more.

## Features
- Sentence Tokenization
- Word Tokenization
- Stopword Removal
- Part-of-Speech (POS) Tagging
- Named Entity Recognition (NER)
- Named Entity Visualization

## Technologies Used
- Python
- NLTK (Natural Language Toolkit)

## Installation

Download the required NLTK resources:

```python
import nltk

nltk.download('punkt')
nltk.download('stopwords')
nltk.download('maxent_ne_chunker_tab')
nltk.download('words')
nltk.download('averaged_perceptron_tagger_eng')
```

## Example

### Input

```text
Sundar Pichai is the CEO of Google and lives in California.
```

### Output

```text
Sundar Pichai → PERSON
Google → ORGANIZATION
California → GPE (Location)
```

## Project Structure

```
Named-Entity-Recognition/
│── Named_Entity_Recognition.ipynb
│── README.md
```

## What is Named Entity Recognition (NER)?

Named Entity Recognition (NER) is an NLP technique used to identify and classify important entities in text into predefined categories.

Common entity types include:

- PERSON
- ORGANIZATION
- GPE (Countries, Cities, States)
- LOCATION
- DATE
- TIME
- MONEY
- PERCENT
- FACILITY

## Applications

- Information Extraction
- Chatbots & Virtual Assistants
- Search Engines
- Resume Parsing
- News Article Analysis
- Question Answering Systems
- Healthcare Text Analysis

## Advantages

- Extracts meaningful information from text
- Improves search and recommendation systems
- Automates document analysis
- Enhances NLP applications

## Author

Muskan Maurya

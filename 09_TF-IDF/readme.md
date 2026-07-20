# TF-IDF (Term Frequency – Inverse Document Frequency) 

## 📌 Overview
TF-IDF (Term Frequency–Inverse Document Frequency) is a feature extraction technique used in Natural Language Processing (NLP). It assigns a numerical weight to each word based on how frequently it appears in a document (TF) and how unique it is across all documents (IDF). This helps identify the most important words while reducing the impact of very common terms.

## 🧠 What I Learned
- Concept of Term Frequency (TF)
- Concept of Inverse Document Frequency (IDF) 
- TF and IDF formulas    
- Manual calculation of TF values   
- Manual calculation of IDF values
- Creating the final TF-IDF matrix (feature vector)
- Understanding how TF-IDF highlights important words

## 📖 Formulas

**Term Frequency (TF):**
```
TF = (Number of times a word appears in a document)
     ----------------------------------------------
       Total number of words in that document
```

**Inverse Document Frequency (IDF):**
```
IDF = log(Total number of documents
          --------------------------
          Number of documents containing the word)
```

**TF-IDF:**
```
TF-IDF = TF × IDF
```

## 📊 Example
Documents:
- S1: good boy
- S2: good girl
- S3: boy girl good

Vocabulary:
- good
- boy
- girl

After calculating TF and IDF for each word, the final TF-IDF matrix is generated, where higher values indicate more important words in a document.

## ✅ Advantages
- Simple and easy to understand
- Highlights important words in documents
- Produces a fixed-size feature vector
- Reduces the influence of very common words
- Widely used in information retrieval and text classification

## ❌ Disadvantages
- Creates sparse vectors
- Cannot handle Out-of-Vocabulary (OOV) words
- Ignores word order and context
- Not suitable for capturing semantic meaning

## 🚀 Applications
- Search Engines
- Document Ranking
- Text Classification
- Information Retrieval
- Keyword Extraction
- Spam Detection
- Document Similarity Analysis

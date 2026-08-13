# Fake News Detection with Source Attribution using LLMs

## Overview

This project presents an evidence-based fake news detection system that combines Large Language Models (LLMs), semantic retrieval, and source attribution to verify the authenticity of news articles.

Unlike traditional fake news classifiers that only predict whether a news article is fake or real, this system retrieves evidence from credible online sources, verifies individual claims, and provides explanations with supporting references.

The project was developed as part of my M.Tech in Computer Science & Engineering (Data Science & Artificial Intelligence).

---

## Features

- News article verification
- Automatic claim extraction
- Semantic query generation
- Evidence retrieval from credible sources
- Source credibility scoring
- Semantic similarity ranking
- LLM-based claim verification
- Source attribution
- Explainable verdict generation

---

## Workflow

Input News Article

↓

Claim Extraction

↓

Query Generation

↓

Web Evidence Retrieval

↓

Evidence Ranking

↓

LLM-based Claim Verification

↓

Final Verdict & Source Attribution

---

## Technologies Used

- Python
- Hugging Face Transformers
- Sentence Transformers
- DuckDuckGo Search
- PyTorch
- Scikit-learn
- NumPy
- Pandas
- BeautifulSoup
- NLP
- Large Language Models (LLMs)

---

## Repository Structure

```
Fake-News-Detection-with-Source-Attribution/
│
├── notebooks/
│   ├── User_Testing.ipynb
│   ├── Evaluation_1.ipynb
│   ├── Evaluation_2.ipynb
│   ├── Evaluation_3.ipynb
│   ├── Evaluation_4.ipynb
│
├── images/
├── outputs/
├── docs/
├── requirements.txt
└── README.md
```

---

## Datasets Used

- FEVER
- LIAR
- ISOT


---

## Sample Output

The system provides:

- Final Verdict
- Confidence Score
- Claim-wise Verification
- Evidence Explanation
- Credible Source Links

---

## Future Improvements

- RAG-based Retrieval
- Knowledge Graph Integration
- Multilingual News Verification
- Real-time News Monitoring
- Cross-lingual Fact Verification

---

## Author

**Sona V P**


---
title: "Knowledge Base Question Answering (RAG)"
layout: single
permalink: /student-projects/nlp/question-answering/knowledge-base-qa/
excerpt: "A retrieval-augmented question answering system built on SQuAD using TF-IDF and T5."
image: /assets/images/student-projects/nlp/knowledge-base-qa/hero.jpg
toc: false
---

## Overview

This project builds a question answering system that retrieves relevant information and generates a natural language answer.

The system follows a retrieval-augmented generation approach, combining a traditional information retrieval method with a neural text generation model. The goal is to return a direct answer rather than a list of documents.

---

## Data

The system uses the Stanford Question Answering Dataset (SQuAD v1.1).

- Over 100,000 question-answer pairs  
- Contexts drawn from Wikipedia articles  
- Each question is paired with a passage containing the answer  

For this project, the dataset is preprocessed into a retrieval corpus by deduplicating contexts and mapping each question to its source passage.

One limitation is that SQuAD assumes the answer is always present in the provided context. This simplifies the task compared to real-world systems.

---

## Approach

The system is organized as a two-stage pipeline.

Retrieval:

- TF-IDF vectorization of all context passages  
- Cosine similarity used to retrieve top-k relevant passages  

Generation:

- Retrieved passages are combined into a single context  
- A T5-small model generates an answer conditioned on the question and context  

In general, the system separates the problem into finding relevant information and then generating a response from that information.

---

## Tech Stack

- Hugging Face transformers (T5-small)  
- scikit-learn (TF-IDF, cosine similarity)  
- Hugging Face datasets (SQuAD loading)  
- PyTorch  
- NLTK and ROUGE for evaluation  

The design keeps the components simple and interpretable, which makes it easier to analyze performance.

---

## Evaluation

The system is evaluated on a held-out test set using multiple metrics.

Results:

- Exact Match: 0.5800  
- F1 Score: 0.7061  
- BLEU: 0.1199  
- ROUGE-1: 0.7077  
- ROUGE-2: 0.3792  
- ROUGE-L: 0.7077  
- Retrieval Accuracy: 0.9200  

These metrics capture different aspects of performance. Exact match is strict, while F1 and ROUGE allow for partial overlap.

---

## Results

The retrieval component performs well, with over 90 percent accuracy in identifying relevant context passages.

The generation component produces answers that are often close to the ground truth but not exact matches. This is reflected in the gap between Exact Match and F1.

At that point, the main limitation becomes answer phrasing rather than information access.

---

## Takeaways

This project highlights a useful baseline for question answering systems.

- Retrieval quality strongly influences overall performance  
- Simple methods like TF-IDF can still be effective  
- Smaller models like T5-small can generate reasonable answers when given good context  
- Multiple evaluation metrics are needed to understand system behavior  

This provides a solid foundation for extending to more advanced retrieval methods or larger models.

---
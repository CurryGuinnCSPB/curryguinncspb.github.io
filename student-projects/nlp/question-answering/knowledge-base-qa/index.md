---
title: "Knowledge Base Question Answering (RAG)"
layout: single
permalink: /student-projects/nlp/question-answering/knowledge-base-qa/
excerpt: "A retrieval-augmented question answering system built on SQuAD using TF-IDF and T5."
image: /assets/images/student-projects/nlp/knowledge-base-qa/hero.jpg
toc: false
---

## Overview

This project builds a question answering system that retrieves relevant information and generates a natural language response.

The system follows a retrieval-augmented generation (RAG) approach, combining document retrieval with neural text generation. Rather than returning a list of documents, the system produces a direct answer grounded in retrieved context.

---

## Data and Approach

The system is built on the Stanford Question Answering Dataset (SQuAD v1.1), which contains over 100,000 question-answer pairs derived from Wikipedia articles. Each question is associated with a passage that contains the answer, making it well-suited for training and evaluation.

The model is structured as a two-stage pipeline.

In the retrieval stage, all context passages are vectorized using TF-IDF, and cosine similarity is used to retrieve the top-k relevant passages for a given question. In the generation stage, the retrieved passages are combined into a single context and passed, along with the question, to a T5-small model that generates the final answer.

This separation between retrieval and generation makes the system both interpretable and modular. Improvements can be made to either stage without redesigning the entire pipeline.

---

## Results

The system performs well across both retrieval and generation components.

- Retrieval Accuracy: **0.9200**  
- Exact Match: **0.5800**  
- F1 Score: **0.7061**  
- ROUGE-1: **0.7077**  
- ROUGE-2: **0.3792**  
- ROUGE-L: **0.7077**

The retrieval stage consistently identifies relevant passages, providing strong input to the generator. The gap between Exact Match and F1 reflects the nature of generative models, where answers are often correct but phrased differently from the reference.

Taken together, these results show that even a relatively lightweight architecture can produce useful answers when retrieval is effective.

---

## Why This Matters

Question answering systems are one of the most direct ways people interact with modern NLP systems. Instead of searching through documents, users can ask a question and receive a concise response.

This project illustrates a practical and widely used design pattern. Retrieval narrows the search space, and generation produces a human-readable answer. The approach scales naturally to larger corpora and more advanced models, making it a foundation for many real-world systems.

At the same time, the results highlight an important idea. Strong retrieval often matters as much as, or more than, the choice of generation model. When the right information is available, even a smaller model can produce effective answers.
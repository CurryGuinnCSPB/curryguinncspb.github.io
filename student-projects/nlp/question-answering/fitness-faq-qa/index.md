---
title: "Fitness FAQ Question Answering"
layout: single
permalink: /student-projects/nlp/question-answering/fitness-faq-qa/
excerpt: "Answers fitness questions using a domain-specific dataset."
image: /assets/images/student-projects/nlp/fitness-faq-qa/hero.jpg
toc: false
---

## Overview

This project focuses on answers fitness questions using a domain-specific dataset.

This project presents a hybrid Question Answering (QA) system tailored to the fitness domain, aiming to provide accurate, relevant responses to user questions about exercise, nutrition, and wellness. The system combines traditional information retrieval methods, TF-IDF and Word2Vec, with a transformer-based extractive QA model (DistilBERT) fine- tuned on the SQuAD 2.0 dataset.

---

## Data and Approach

The project draws on SQuAD, X, Hugging Face Dataset.

The core system is built around BERT, RoBERTa, DistilBERT, TF-IDF. The pipeline separates retrieval from generation so the system can first identify useful context and then produce an answer from that material.

The implementation uses Hugging Face, transformers, scikit-learn, NLTK, TensorFlow.

---

## Results

The project reports qualitative or comparative results rather than a single headline metric. The results show a clear improvement over the comparison baseline or over simpler alternatives.

---

## Why This Matters

Question answering remains one of the most direct ways people interact with NLP systems. This project shows how retrieval and generation can be combined to return focused answers instead of a list of documents.

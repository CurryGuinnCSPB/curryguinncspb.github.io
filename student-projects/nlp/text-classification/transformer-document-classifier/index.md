---
title: "Transformer-Based Document Classifier"
layout: single
permalink: /student-projects/nlp/text-classification/transformer-document-classifier/
excerpt: "Uses transformer models for document classification tasks."
image: /assets/images/student-projects/nlp/transformer-document-classifier/hero.jpg
toc: false
---

## Overview

This project focuses on uses transformer models for document classification tasks.

This project aims to fine-tune transformers for textual classification using training data and labels specific to the domain of stock analysis. There are typically five labels stock analysts ascribe to securities: “Strong Sell”, “Sell”, “Hold”, “Buy”, and “Strong Buy”.

---

## Data and Modeling

The project uses X as its primary dataset.

The core system is built around BERT, DistilBERT, Naive Bayes, RAG. The model combines contextual language modeling with domain-specific signals so that structured entities are easier to detect.

The implementation uses transformers, NLTK, TensorFlow.

---

## Results

Reported evaluation includes F1: **0.37879**, F1: **0.54003**, Accuracy: **0.40659**, and Accuracy: **0.53846**. The results suggest that the system is effective on the target task and provides a useful baseline for future work.

---

## Why This Matters

Classification projects like this matter because they turn large collections of text into signals that can actually be used. That can support moderation, decision-making, or domain analysis depending on the setting.

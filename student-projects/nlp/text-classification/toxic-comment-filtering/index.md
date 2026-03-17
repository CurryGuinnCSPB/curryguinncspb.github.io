---
title: "Toxic Comment Filtering"
layout: single
permalink: /student-projects/nlp/text-classification/toxic-comment-filtering/
excerpt: "Detects toxic language in online comment threads."
image: /assets/images/student-projects/nlp/toxic-comment-filtering/hero.jpg
toc: false
---

## Overview

This project focuses on detects toxic language in online comment threads.

My project consisted of building two different toxic comment filtering models. The first was a BERT-based pre-trained transformer model and the second was a Word2Vec + LSTM custom built model.

---

## Data and Modeling

The project draws on Wikipedia, SARC, Twitter.

The core system is built around BERT, LSTM, RAG, transformer. The model combines contextual language modeling with domain-specific signals so that structured entities are easier to detect.

The implementation uses Hugging Face, transformers, PyTorch, scikit-learn, pandas.

---

## Results

Reported evaluation includes Accuracy: **96.95**, Precision: **83.10**, and Recall: **82.17**. The results show a clear improvement over the comparison baseline or over simpler alternatives.

---

## Why This Matters

Classification projects like this matter because they turn large collections of text into signals that can actually be used. That can support moderation, decision-making, or domain analysis depending on the setting.

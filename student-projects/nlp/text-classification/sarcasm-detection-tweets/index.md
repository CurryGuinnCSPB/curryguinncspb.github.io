---
title: "Sarcasm Detection in Tweets"
layout: single
permalink: /student-projects/nlp/text-classification/sarcasm-detection-tweets/
excerpt: "Detects sarcasm in social media posts using transformer models."
image: /assets/images/student-projects/nlp/sarcasm-detection-tweets/hero.jpg
toc: false
---

## Overview

This project focuses on detects sarcasm in social media posts using transformer models.

Sarcasm is a subtle and context-dependent way of communication, which largely depends on the intricacies of the linguistic cues, cultural knowledge, or implied meaning. Automatically detecting sarcasm in social media posts such as tweets has become an important task in applications like sentiment analysis and intent understanding.

---

## Data and Modeling

The project draws on SARC, X. Reported data sizes include 3,800 training, 1,800 test.

The core system is built around BERT, RoBERTa, TF-IDF, Logistic Regression. The pipeline separates retrieval from generation so the system can first identify useful context and then produce an answer from that material.

The implementation uses Hugging Face, transformers, PyTorch, scikit-learn, pandas.

---

## Results

The project reports qualitative or comparative results rather than a single headline metric. The results show a clear improvement over the comparison baseline or over simpler alternatives.

---

## Why This Matters

Classification projects like this matter because they turn large collections of text into signals that can actually be used. That can support moderation, decision-making, or domain analysis depending on the setting.

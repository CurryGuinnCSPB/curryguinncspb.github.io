---
title: "Multi-Class Emotion Detection"
layout: single
permalink: /student-projects/nlp/text-classification/multiclass-emotion-detection/
excerpt: "Classifies emotional categories in text."
image: /assets/images/student-projects/nlp/multiclass-emotion-detection/hero.jpg
toc: false
---

## Overview

This project focuses on classifies emotional categories in text.

This project compares three approaches to six-way emotion classification on short social-media texts: a compact feed-forward neural network (FFNN) baseline with learned embeddings, DistilBERT-base-uncased, and BERT-base-uncased. Each model is built using Hugging Face’s transformer library.

---

## Data and Modeling

The project draws on Twitter, X. Reported data sizes include 333,447 training, 41,681 validation, 41,681 test.

The core system is built around BERT, RoBERTa, DistilBERT, transformer. The model combines contextual language modeling with domain-specific signals so that structured entities are easier to detect.

The implementation uses Hugging Face, transformers, PyTorch, pandas, TensorFlow.

---

## Results

Reported evaluation includes F1: **0.8393**, F1: **0.9406**, and Accuracy: **0.8899**. The results show a clear improvement over the comparison baseline or over simpler alternatives.

---

## Why This Matters

Classification projects like this matter because they turn large collections of text into signals that can actually be used. That can support moderation, decision-making, or domain analysis depending on the setting.

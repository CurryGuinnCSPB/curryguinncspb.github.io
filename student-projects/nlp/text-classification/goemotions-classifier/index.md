---
title: "Emotion Classification with GoEmotions"
layout: single
permalink: /student-projects/nlp/text-classification/goemotions-classifier/
excerpt: "Fine-tunes BERT for emotion classification."
image: /assets/images/student-projects/nlp/goemotions-classifier/hero.jpg
toc: false
---

## Overview

This project focuses on fine-tunes BERT for emotion classification.

1. The problem addressed by my project was learning how to tune a deep learning model, expanding on the Hugging Face demo work we did in class, to become more comfortable with working with LLMs.

---

## Data and Modeling

The project draws on GoEmotions, X, Tuning BERT for Emotion Classification with the GoEmotions Dataset.

The core system is built around bert-base-cased, BERT, RAG, transformer. The pipeline separates retrieval from generation so the system can first identify useful context and then produce an answer from that material.

The implementation uses Hugging Face, transformers, PyTorch, scikit-learn, pandas.

---

## Results

The project reports qualitative or comparative results rather than a single headline metric. The results show a clear improvement over the comparison baseline or over simpler alternatives.

---

## Why This Matters

Classification projects like this matter because they turn large collections of text into signals that can actually be used. That can support moderation, decision-making, or domain analysis depending on the setting.

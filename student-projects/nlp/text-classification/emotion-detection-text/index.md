---
title: "Emotion Detection in Text"
layout: single
permalink: /student-projects/nlp/text-classification/emotion-detection-text/
excerpt: "Identifies emotional states expressed in written language."
image: /assets/images/student-projects/nlp/emotion-detection-text/hero.jpg
toc: false
---

## Overview

This project focuses on identifies emotional states expressed in written language.

Emotion is one of the crucial human feedback mechanisms that is difficult to transmit with it's full potential in the written form. This project, demonstrates the efficacy of a fine-tuned BERT model at detecting and distinguishing between six core human emotions (sadness, joy, love, anger, fear, and surprise) in textual data.

---

## Data and Modeling

The project draws on GoEmotions, Twitter, X. Reported data sizes include 2,000 validation, 2,000 test.

The core system is built around BERT, LSTM, RAG, transformer. The model combines contextual language modeling with domain-specific signals so that structured entities are easier to detect.

The implementation uses Hugging Face, transformers, PyTorch, pandas.

---

## Results

Reported evaluation includes F1: **0.932**, and Accuracy: **93.3**. The results point to a workable solution for the target task and a clear path for refinement.

---

## Why This Matters

Classification projects like this matter because they turn large collections of text into signals that can actually be used. That can support moderation, decision-making, or domain analysis depending on the setting.

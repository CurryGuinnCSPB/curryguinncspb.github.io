---
title: "Human vs. AI Text Detection"
layout: single
permalink: /student-projects/nlp/text-classification/human-ai-text-detection/
excerpt: "Classifies whether text was written by humans or LLMs."
image: /assets/images/student-projects/nlp/human-ai-text-detection/hero.jpg
toc: false
---

## Overview

This project focuses on classifies whether text was written by humans or LLMs.

Two classifier models N1 and P1 are developed to identify the human-generated and the LLM- generated texts. N1 involves finetuning a pretrained RoBERTa model and P1 incorporates POS tags in the finetuning RoBERTa process.

---

## Data and Modeling

The project draws on SQuAD, X.

The core system is built around BERT, RoBERTa, RAG, transformer. The model combines contextual language modeling with domain-specific signals so that structured entities are easier to detect.

The implementation uses Hugging Face, transformers, PyTorch, scikit-learn, pandas.

---

## Results

The project reports qualitative or comparative results rather than a single headline metric. The results show a clear improvement over the comparison baseline or over simpler alternatives.

---

## Why This Matters

Classification projects like this matter because they turn large collections of text into signals that can actually be used. That can support moderation, decision-making, or domain analysis depending on the setting.

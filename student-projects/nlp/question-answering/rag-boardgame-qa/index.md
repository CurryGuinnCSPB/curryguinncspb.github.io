---
title: "RAG Question Answering for Board Games"
layout: single
permalink: /student-projects/nlp/question-answering/rag-boardgame-qa/
excerpt: "Uses retrieval-augmented generation to answer board game questions."
image: /assets/images/student-projects/nlp/rag-boardgame-qa/hero.jpg
toc: false
---

## Overview

This project focuses on uses retrieval-augmented generation to answer board game questions.

This project addresses the problem of text autocomplete systems, comparing three different approaches: n-gram models, LSTM models, and transformers. Specifically, the three approaches range from simple to complex and from cheap to expensive in terms of time and compute.

---

## Data and Approach

The project uses X as its primary dataset.

The core system is built around LSTM, transformer, PyTorch. The model combines contextual language modeling with domain-specific signals so that structured entities are easier to detect.

The implementation uses Hugging Face, transformers, PyTorch, NLTK, TensorFlow.

---

## Results

The project reports qualitative or comparative results rather than a single headline metric. The results show a clear improvement over the comparison baseline or over simpler alternatives.

---

## Why This Matters

Question answering remains one of the most direct ways people interact with NLP systems. This project shows how retrieval and generation can be combined to return focused answers instead of a list of documents.

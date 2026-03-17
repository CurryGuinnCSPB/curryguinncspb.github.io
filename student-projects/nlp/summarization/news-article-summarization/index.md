---
title: "News Article Summarization"
layout: single
permalink: /student-projects/nlp/summarization/news-article-summarization/
excerpt: "Generates concise summaries of long news articles."
image: /assets/images/student-projects/nlp/news-article-summarization/hero.jpg
toc: false
---

## Overview

This project focuses on generates concise summaries of long news articles.

Text summarization refers to the process of condensing lengthy text into shorter summaries that make it easy to grasp while preserving the main topics in a document. Prior work such as Abstractive vs Extractive Summarization argue that while abstractive summaries tend to resemble human-written text more closely compared to extractive, these approaches still lack contextual representation needed to form fluent summaries.This raises the broader question of how existing methods can be improved to better support natural language understanding.

---

## Data and Approach

The project draws on X, HuggingFace Dataset, A Large-Scale Dataset.

The core system is built around BERT, DistilBERT, TF-IDF, RAG. The pipeline separates retrieval from generation so the system can first identify useful context and then produce an answer from that material.

The implementation uses transformers, scikit-learn, NLTK, ROUGE.

---

## Results

The project reports qualitative or comparative results rather than a single headline metric. The results show a clear improvement over the comparison baseline or over simpler alternatives.

---

## Why This Matters

Summarization is one of the clearest ways to make NLP useful for real readers. A good summarization system reduces the amount of text someone needs to process while preserving the main information.
